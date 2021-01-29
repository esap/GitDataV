<template>
  <div class="personal-box">
    <div class="personal-body">
      <div class="left">
        <div class="img">
          <img :style="{ background: 'url(' + personalData.img + ')' }" />
        </div>
      </div>
      <div class="right">
        <div class="name">Fullwin</div>

        <div class="year">
          <a class="date">2021</a>
          <a class="time">Loading...</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "personal",
  props: {
    personalData: Object
  }
};
</script>

<style lang="scss">
@import "./index";
</style>
