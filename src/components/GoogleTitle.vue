<template>
  <div class="google-title">
    <div class="img-conteiner">
      <img
        class="google-img"
        alt="Google"
        height="92"
        src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_light_color_272x92dp.png"
        srcset="
          https://www.google.com/images/branding/googlelogo/1x/googlelogo_light_color_272x92dp.png 1x,
          https://www.google.com/images/branding/googlelogo/1x/googlelogo_light_color_272x92dp.png 2x
        "
        width="272"
        data-iml="1679465670338"
        data-atf="1"
        data-frt="0"
      />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.google-title {
  height: calc(100% - 560px);
  min-height: 92px;
  max-height: 290px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.img-conteiner {
  max-height: 92px;
  position: relative;
  height: 100%;
  margin-top: auto;
}
.google-img {
  max-height: 100%;
  max-width: 100%;
  object-fit: contain;
  object-position: center bottom;
  width: auto;
}
</style>
