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
      <accaunt-menu
        v-if="accWinVisible"
        v-click-outside="closeWindow"
        class="accaunt-window"
      ></accaunt-menu>
    </div>
  </div>
</template>

<script>
import AccauntMenu from "./AccauntMenu.vue";

export default {
  components: { AccauntMenu },
  data() {
    return {
      accWinVisible: false,
    };
  },
  methods: {
    displayAccount() {
      this.accWinVisible = !this.accWinVisible;
    },
    closeWindow() {
      this.accWinVisible = false;
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
</style>
