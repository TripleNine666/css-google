<template>
  <div class="google-lang">
    <div class="google-lang__block">
      <div class="google-lang__block__message">
        Сервисы Google доступны на этих языках:
        <a
          href="https://www.google.com/setprefs?sig=0_UNqi2arej5sf__cG7xIE1UDE9xs%3D&amp;hl=be&amp;source=homepage&amp;sa=X&amp;ved=0ahUKEwi7_fKVr_T9AhUXhFwKHXmdDR8Q2ZgBCBM"
          >Беларуская</a
        >
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.google-lang {
  flex-grow: 1;
}
.google-lang__block {
  display: flex;
  justify-content: center;
}
.google-lang__block__message {
  color: #bdc1c6;
  line-height: 28px;
  font-size: small;
}
.google-lang__block__message a {
  text-decoration: none;
  color: #8ab4f8;
}
.google-lang__block__message a:hover,
.google-lang__block__message a:active {
  text-decoration: underline;
}
</style>
