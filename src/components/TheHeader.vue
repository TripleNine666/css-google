<template>
  <div class="google-header header-height">
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
            href="https://www.google.nl/imghp?hl=ru&amp;ogbl"
            ><i class="material-symbols-outlined">Apps</i></a
          >
        </div>
        <div class="icon__item"><a href="#">Иконка2</a></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.google-header {
  display: flex;
  justify-content: flex-end;
  align-items: center;
}
.header-height {
  height: 60px;
  padding: 6px;
}
.actions {
  display: flex;
  height: 48px;
  align-items: center;
  padding-left: 48px;
  vertical-align: middle;
  float: right;
}
.links {
  font-family: arial, sans-serif;
  line-height: normal;
  padding-right: 15px;
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
  background-color: rgba(136, 140, 143, 0.363);
  border-radius: 50%;
}

.material-symbols-outlined {
  font-variation-settings: "FILL" 0, "wght" 600, "GRAD" 25, "opsz" 48;
}
</style>
