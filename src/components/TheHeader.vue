<template>
  <div class="google-header header-height">
    <div></div>
    <div class="actions">
      <div class="links">
        <div class="link__item">
          <a href="https://mail.google.com/mail/&amp;ogbl">Почта</a>
        </div>
        <div class="link__item">
          <a href="https://www.google.nl/imghp?hl=ru&amp;ogbl">Картинки</a>
        </div>
      </div>
      <div class="icons">
        <div class="icon__item">
          <a
            class="material-symbols-outlined"
            href="https://about.google/products/"
            title="Приложения Google"
            ><i class="material-symbols-outlined">Apps</i></a
          >
        </div>
        <div class="icon__item img__item" @click="displayAccount">
          <a
            :class="{
              'material-symbols-outlined': true,
              active: accWinVisible,
            }"
            title="Аккаунт Google"
            role="button"
            ><img
              class="icon__item__img"
              src="https://lh3.google.com/u/0/ogw/AAEL6sim8jiWhL9yZjht3Uofxl4tXtxuHR8rSeh68wCK=s32-c-mo"
              srcset="
                https://lh3.google.com/u/0/ogw/AAEL6sim8jiWhL9yZjht3Uofxl4tXtxuHR8rSeh68wCK=s32-c-mo 1x,
                https://lh3.google.com/u/0/ogw/AAEL6sim8jiWhL9yZjht3Uofxl4tXtxuHR8rSeh68wCK=s64-c-mo 2x
              "
          /></a>
        </div>
      </div>
      <div v-if="accWinVisible" class="accaunt-window">
        <div class="accaunt-window-container">
          <div class="accaunt-window-container__main">
            <div>
              <div class="accaunt-window__items">
                <div class="account-manage-item">
                  <div class="account-manage-item-set">
                    <div class="manage-item__block">
                      <div class="accaunt-control">
                        <div class="accaunt-control__name">
                          <div class="accaunt-control__name__photo">
                            <img
                              jsname="wsYqfb"
                              alt="Изображение профиля"
                              class="JZFjpd"
                              src="https://lh3.googleusercontent.com/a/AGNmyxZzBqUOiFWwjAgIbrjiPZAFyjm_wgFTtfjTMZ3h=s83-c-mo"
                              srcset="
                                https://lh3.googleusercontent.com/a/AGNmyxZzBqUOiFWwjAgIbrjiPZAFyjm_wgFTtfjTMZ3h=s83-c-mo  1x,
                                https://lh3.googleusercontent.com/a/AGNmyxZzBqUOiFWwjAgIbrjiPZAFyjm_wgFTtfjTMZ3h=s192-c-mo 2x
                              "
                            />
                            <svg
                              xmlns="http://www.w3.org/2000/svg"
                              width="64"
                              height="64"
                              viewBox="0 0 64 64"
                              fill="none"
                            >
                              <mask id="path-1-inside-1_824_12075" fill="white">
                                <path
                                  fill-rule="evenodd"
                                  clip-rule="evenodd"
                                  d="M62.5796 41.4569C63.5029 38.468 64 35.2921 64 32C64 14.3269 49.6731 0 32 0C14.3269 0 0 14.3269 0 32C0 49.6731 14.3269 64 32 64C35.2921 64 38.468 63.5029 41.4569 62.5796C39.2981 59.9812 38 56.6422 38 53C38 44.7157 44.7157 38 53 38C56.6422 38 59.9812 39.2981 62.5796 41.4569Z"
                                ></path>
                              </mask>
                              <path
                                d="M62.5796 41.4569L61.9406 42.2261L63.0929 43.1835L63.5351 41.7521L62.5796 41.4569ZM41.4569 62.5796L41.7521 63.5351L43.1835 63.0929L42.2261 61.9406L41.4569 62.5796ZM63 32C63 35.1909 62.5182 38.2674 61.6241 41.1618L63.5351 41.7521C64.4875 38.6687 65 35.3933 65 32H63ZM32 1C49.1208 1 63 14.8792 63 32H65C65 13.7746 50.2254 -1 32 -1V1ZM1 32C1 14.8792 14.8792 1 32 1V-1C13.7746 -1 -1 13.7746 -1 32H1ZM32 63C14.8792 63 1 49.1208 1 32H-1C-1 50.2254 13.7746 65 32 65V63ZM41.1618 61.6241C38.2674 62.5182 35.1909 63 32 63V65C35.3933 65 38.6687 64.4875 41.7521 63.5351L41.1618 61.6241ZM42.2261 61.9406C40.2109 59.515 39 56.4003 39 53H37C37 56.8841 38.3853 60.4474 40.6877 63.2186L42.2261 61.9406ZM39 53C39 45.268 45.268 39 53 39V37C44.1634 37 37 44.1634 37 53H39ZM53 39C56.4003 39 59.515 40.2109 61.9406 42.2261L63.2186 40.6877C60.4474 38.3853 56.8841 37 53 37V39Z"
                                fill="currentColor"
                                mask="url(#path-1-inside-1_824_12075)"
                              ></path>
                            </svg>
                            <div class="camera-icon">
                              <button class="camera-icon">
                                <svg
                                  width="18"
                                  height="18"
                                  viewBox="0 0 24 24"
                                  focusable="false"
                                  class="camera-svg"
                                >
                                  <path
                                    d="M20 5h-3.17L15 3H9L7.17 5H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2zm0 14H4V7h16v12z"
                                  ></path>
                                  <path
                                    d="M12 9c-2.21 0-4 1.79-4 4s1.79 4 4 4 4-1.79 4-4-1.79-4-4-4z"
                                  ></path>
                                </svg>
                              </button>
                            </div>
                          </div>
                          <div class="accaunt-control__name__info"></div>
                        </div>
                        <div></div>
                      </div>
                      <div class="accaunt-control-line"></div>
                    </div>
                    <div class="manage-item__block"></div>
                  </div>
                  <div class="account-exit-item"></div>
                  <div class="account-additional-item"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      accWinVisible: false,
    };
  },
  methods: {
    displayAccount() {
      this.accWinVisible = !this.accWinVisible;
    },
  },
};
</script>

<style scoped>
.google-header {
  display: flex;
  justify-content: flex-end;
  align-items: center;
  vertical-align: middle;
}
.header-height {
  height: 60px;
  padding: 6px;
}
.actions {
  display: flex;
  flex-wrap: nowrap;
  height: 48px;
  align-items: center;
  padding-left: 48px;
  vertical-align: middle;
  float: right;
}
.links {
  display: flex;
  font-family: arial, sans-serif;
  line-height: normal;
  padding-right: 11px;
}
.link__item {
  display: inline-block;
}
.link__item a {
  display: inline-block;
  padding: 8px;
  font: 13px/27px Roboto, Arial, sans-serif;
  text-decoration: none;
  color: white;
}
.icon__item a {
  display: inline-block;
  padding: 8px;
  text-decoration: none;
  color: white;
}
.img__item {
  padding: 8px;
}
.img__item a {
  padding: 4px;
  cursor: pointer;
}
i {
  display: inline-block;
}
.icons {
  display: flex;
  height: 48px;
  align-items: center;
  vertical-align: middle;
}
.links a:hover {
  text-decoration: underline;
}
.icon__item {
  display: inline-block;
}
.icon__item a:hover {
  background-color: rgba(232, 234, 237, 0.08);
  border-radius: 50%;
}
.active {
  background-color: rgba(232, 234, 237, 0.12);
  border-radius: 50%;
}
.icon__item__img {
  border-radius: 50%;
}

.material-symbols-outlined {
  font-variation-settings: "FILL" 0, "wght" 600, "GRAD" 25, "opsz" 48;
}
.accaunt-window {
  position: absolute;
  top: 0px;
  right: 0px;
  margin-right: 4px;
  margin-top: 57px;
  width: 400px;
  height: 328px;

  z-index: 991;
}
.accaunt-window-container {
  height: 100%;
  -webkit-font-smoothing: antialiased;
  color: rgba(0, 0, 0, 0.87);
  font-family: Roboto, RobotoDraft, Helvetica, Arial, sans-serif;
  margin: 0;
  text-size-adjust: 100%;
}
.accaunt-window-container__main {
  max-width: 400px;
  padding: 8px 12px 16px;
  height: 100%;
}
.accaunt-window-container__main > div {
  background: #2d2e30;
  overflow-y: auto;
  border: none;
  border-radius: 28px;
  box-shadow: 0 4px 8px 3px rgba(0, 0, 0, 0.15), 0 1px 3px rgba(0, 0, 0, 0.3);
  overflow-x: auto;
  height: 100%;
}
.accaunt-window__items {
  overflow-y: overlay;
  height: 100%;
  min-width: 240px;
  padding-top: 4px;
}
.account-manage-item {
  border-radius: 24px;
  margin: 4px 8px 0;
}
.account-manage-item-set {
  border-radius: inherit;
  overflow: hidden;
  padding: 0;
  position: relative;
  text-align: left;
  white-space: nowrap;
}
.manage-item__block {
  background: #1f1f1f;
  border-radius: 4px;
  margin-bottom: 2px;
}
.manage-item__block:first-child {
  border-top-left-radius: inherit;
  border-top-right-radius: inherit;
}
.manage-item__block:last-child {
  border-bottom-left-radius: inherit;
  border-bottom-right-radius: inherit;
}
.accaunt-control {
  display: inline-block;
  padding: 16px 16px 0;
  vertical-align: top;
  width: calc(100% - 32px);
}
.accaunt-control-line {
  box-sizing: content-box;
  left: 0;
  min-height: 15px;
  width: auto;
}
.accaunt-control__name {
  display: inline-block;
  margin-bottom: 1px;
  position: relative;
  vertical-align: top;
  width: 100%;
}
.accaunt-control__name__photo {
  display: inline-block;
  position: relative;
  text-align: center;
  height: 64px;
  width: 64px;
  float: left;
  margin: 0;
}
.accaunt-control__name__photo img {
  height: 64px;
  width: 64px;
  padding: 0;
  border-radius: 50%;
  fill: none;
}
.accaunt-control__name__photo > svg {
  color: rgba(241, 243, 244, 0.12);
  left: 0;
  top: 0;
  border-radius: 50%;
  position: absolute;
}
.camera-icon {
  border-radius: 50%;
  bottom: -4px;
  height: 30px;
  position: absolute;
  right: -4px;
  width: 30px;
  background: #1f1f1f;
}
.camera-icon button {
  border-color: #444746;
  margin: 3px;
  background: rgb(31, 31, 31);
  border: 1px solid #444746;
  box-sizing: border-box;
  position: relative;
  bottom: 0;
  box-shadow: none;
  right: 0;
  z-index: auto;
  color: #3c4043;
  height: 24px;
  width: 24px;
  outline: 0;
  padding: 0;
  cursor: pointer;
  border-radius: 50%;
}
.camera-icon button:hover {
  background: rgba(227, 227, 227, 0.08);
}
.camera-svg {
  color: #c4c7c5;
  fill: currentColor;
}
.accaunt-control__name__info {
  display: inline-block;
  margin-bottom: 0;
  margin-left: 14px;
  margin-top: 13px;
  max-width: calc(100% - 78px);
  overflow: hidden;
  text-overflow: ellipsis;
  vertical-align: top;
}
</style>
