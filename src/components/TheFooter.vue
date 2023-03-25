<template>
  <div class="footer">
    <div class="contry">Беларусь</div>
    <div class="footer-items footer-block">
      <div class="footer-block">
        <a
          href="https://about.google/?utm_source=google-BY&amp;utm_medium=referral&amp;utm_campaign=hp-footer&amp;fg=1"
          >Всё о Google</a
        >
        <a href="#">Реклама</a>
        <a href="#">Для бизнеса</a>
        <a href="#">Как работает Google Поиск</a>
      </div>
      <div class="footer-block">
        <a
          href="https://about.google/?utm_source=google-BY&amp;utm_medium=referral&amp;utm_campaign=hp-footer&amp;fg=1"
          >Конфиденциальность</a
        >
        <a href="#">Условия</a>
        <a href="#">Настройки</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  background: #171717;
  flex-shrink: 0;
}
.contry {
  padding: 15px 30px;
  color: #9aa0a6;
  font-size: 15px;
  border-bottom: 1px solid #3c4043;
}
.footer-items {
  padding: 0 20px;
}
.footer-block {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.footer-block a {
  text-decoration: none;
  color: #9aa0a6;
  padding: 15px;
}
@media screen and (max-width: 1200px) {
  .footer-block {
    justify-content: space-evenly;
  }
}
</style>
