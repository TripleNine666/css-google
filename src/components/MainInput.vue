<template>
  <div class="main-input">
    <div class="container">
      <div class="input-container">
        <div class="input-items">
          <div class="input-item__icon">
            <div>
              <span class="icon-span">
                <svg
                  focusable="false"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                >
                  <path
                    d="M15.5 14h-.79l-.28-.27A6.471 6.471 0 0 0 16 9.5 6.5 6.5 0 1 0 9.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z"
                  ></path>
                </svg>
              </span>
            </div>
          </div>
          <div class="input-item__input">
            <input type="text" title="Поиск" />
          </div>
          <div class="input-item__img">
            <div class="keyboard input-item__img__item">
              <span class="keyboard-span" title="Экранная клавиатура"></span>
            </div>
            <div class="micro input-item__img__item" title="Голосовой поиск">
              <svg>
                <path
                  fill="#4285f4"
                  d="m12 15c1.66 0 3-1.31 3-2.97v-7.02c0-1.66-1.34-3.01-3-3.01s-3 1.34-3 3.01v7.02c0 1.66 1.34 2.97 3 2.97z"
                ></path>
                <path fill="#34a853" d="m11 18.08h2v3.92h-2z"></path>
                <path
                  fill="#fbbc04"
                  d="m7.05 16.87c-1.27-1.33-2.05-2.83-2.05-4.87h2c0 1.45 0.56 2.42 1.47 3.38v0.32l-1.15 1.18z"
                ></path>
                <path
                  fill="#ea4335"
                  d="m12 16.93a4.97 5.25 0 0 1 -3.54 -1.55l-1.41 1.49c1.26 1.34 3.02 2.13 4.95 2.13 3.87 0 6.99-2.92 6.99-7h-1.99c0 2.92-2.24 4.93-5 4.93z"
                ></path>
              </svg>
            </div>
            <div
              class="img-search input-item__img__item"
              title="Поиск по картинке"
            >
              <svg viewBox="0 0 192 192">
                <rect fill="none" height="192" width="192"></rect>
                <g>
                  <circle fill="#4285f4" cx="96" cy="104.15" r="28"></circle>
                  <path
                    fill="#ea4335"
                    d="M160,72v40.15V136c0,1.69-0.34,3.29-0.82,4.82v0v0c-1.57,4.92-5.43,8.78-10.35,10.35h0v0 c-1.53,0.49-3.13,0.82-4.82,0.82H66l16,16h50h12c4.42,0,8.63-0.9,12.46-2.51c3.83-1.62,7.28-3.96,10.17-6.86 c1.45-1.45,2.76-3.03,3.91-4.74c2.3-3.4,3.96-7.28,4.81-11.44c0.43-2.08,0.65-4.24,0.65-6.45v-12V96.15V84l-6-19l-10.82,2.18 C159.66,68.71,160,70.31,160,72z"
                  ></path>
                  <path
                    fill="#4285f4"
                    d="M32,72c0-1.69,0.34-3.29,0.82-4.82c1.57-4.92,5.43-8.78,10.35-10.35C44.71,56.34,46.31,56,48,56 h96c1.69,0,3.29,0.34,4.82,0.82c0,0,0,0,0,0L149,45l-17-5l-16-16h-13.44H96h-6.56H76L60,40H48c-17.67,0-32,14.33-32,32v12v20l16,16 V72z"
                  ></path>
                  <path
                    fill="#34a853"
                    d="M144,40h-12l16.83,16.83c1.23,0.39,2.39,0.93,3.47,1.59c2.16,1.32,3.97,3.13,5.29,5.29 c0.66,1.08,1.2,2.24,1.59,3.47v0L176,84V72C176,54.33,161.67,40,144,40z"
                  ></path>
                  <path
                    fill="#fbbc04"
                    d="M48,168h39.89l-16-16H48c-8.82,0-16-7.18-16-16v-23.89l-16-16V136C16,153.67,30.33,168,48,168z"
                  ></path>
                </g>
              </svg>
            </div>
          </div>
        </div>
      </div>
      <div class="actions-container">
        <div class="action">
          <a href="https://www.google.com/">Поиск в Google</a>
        </div>
        <div class="action">
          <a href="https://www.google.com/doodles">Мне повезёт!</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.main-input {
  max-height: 160px;
  padding: 20px;
  flex-shrink: 0;
}
.container {
  margin: 0 auto;
  padding-top: 6px;
  width: auto;
  max-width: 580px;
  position: relative;
}
.input-container {
  display: flex;
  z-index: 3;
  height: 46px;
  background: #202124;
  border: 1px solid #5f6368;
  box-shadow: none;
  border-radius: 24px;
  margin: 0 auto;
  width: 638px;
  width: auto;
  max-width: 584px;
}
.input-container:hover {
  background-color: #303134;
  box-shadow: 0 1px 6px 0 #171717;
  border-color: #303134;
}
.input-items {
  display: flex;
  flex: 1;
  padding: 5px 8px 0 14px;
}
.input-item__icon {
  display: flex;
  align-items: center;
  padding: 0 13px 0 0;
  margin-top: -5px;
}
.input-item__icon div {
  margin: auto;
}
.icon-span {
  height: 20px;
  line-height: 20px;
  width: 20px;
  display: inline-block;
  fill: currentColor;
  margin-top: 3px;
  color: #9aa0a6;
  position: relative;
}
.icon-span svg {
  display: block;
  height: 100%;
  width: 100%;
}
.input-item__input {
  display: flex;
  flex-wrap: wrap;
  flex: 1;
}
.input-item__input input {
  background: transparent;
  border: none;
  word-wrap: break-word;
  height: 34px;
  padding: 0;
  margin: 0;
  display: flex;
  flex: 100%;
  font-size: 16px;
}
.input-item__input input:active .input-item__input input:hover,
.input-item__input input:focus {
  outline: 0;
  outline-offset: 0;
}
.input-item__img {
  display: flex;
  align-items: stretch;
  margin-top: -5px;
}
.input-item__img__item {
  padding: 0 8px;
  display: flex;
  align-items: center;
  cursor: pointer;
  vertical-align: middle;
}
.keyboard-span {
  background: url(//www.gstatic.com/inputtools/images/tia.png) no-repeat center;
  width: 24px;
  height: 24px;
}
.input-item__img__item svg {
  height: 24px;
  width: 24px;
}

.actions-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 70px;
  padding-top: 24px;
}
.action {
  padding: 9px 16px;
  margin: 0 6px;
  border: 1px solid #303134;
  background-color: #303134;
  border-radius: 5px;
}
.action:hover {
  border: 1px solid #9aa0a6;
}
.action a {
  text-decoration: none;
  color: white;
}
</style>
