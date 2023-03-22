<template>
  <div class="main-input">
    <div class="container">
      <div class="input-container">
        <div class="input-items">
          <div class="imput-item__icon">
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
          <div class="imput-item__input"></div>
          <div></div>
        </div>
      </div>
      <div class="actions-container">
        <button>AAA</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.main-input {
  display: flex;
  height: 160px;
  padding: 20px;
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
  height: 44px;
  background: #202124;
  border: 1px solid #5f6368;
  box-shadow: none;
  border-radius: 24px;
  margin: 0 auto;
  width: 638px;
  width: auto;
  max-width: 584px;
}
.input-items {
  display: flex;
  flex: 1;
  padding: 5px 8px 0 14px;
}
.imput-item__icon {
  display: flex;
  align-items: center;
  padding: 0 13px 0 0;
  margin-top: -5px;
}
.imput-item__icon div {
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
</style>
