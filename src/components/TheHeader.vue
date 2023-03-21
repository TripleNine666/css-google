<template>
  <div class="google-header">
    <div class="actions">
      <div class="links">
        <div class="link__item">
          <a href="https://mail.google.com/mail/&amp;ogbl">Почта</a>
        </div>
        <div class="link__item">
          <a href="https://www.google.nl/imghp?hl=ru&amp;ogbl">Картинки</a>
        </div>
      </div>
      <div>
        <div>Иконка1</div>
        <div>Иконка2</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.google-header {
  height: 60px;
  display: flex;
  border: 2px solid white;
  padding: 10px;
  justify-content: flex-end;
  align-items: center;
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
.links a {
  display: inline-block;
  padding: 10px;
  font-family: arial, sans-serif;
  font-stretch: 100%;
  text-decoration: none;
  color: white;
}
.links a:hover {
  text-decoration: underline;
}
</style>
