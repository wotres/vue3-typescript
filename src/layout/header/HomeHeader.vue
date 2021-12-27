<template>
  <div class="home-header">
    <div class="home-header__button">
      <div class="home-header__button-image"/>
    </div>
    <div class="home-header__title">
      <span>Vue3 with Typescript</span>
    </div>
  </div>
</template>
<script lang="ts">
export default {
  name: 'HomeHeader',
};
</script>
<style lang="scss">
.home-header {
  display: flex;
  flex-direction: row;
  height: 50px;
  border-bottom: 1px solid black;
  font-weight: bold;
  font-size: 36px;
  &__button {
    width: 100px;
    &-image {
      width: 50px;
      height: 50px;
      background-image: url('~@/assets/images/home_black.svg');
      background-size: cover;
      background-repeat: no-repeat;
    }
  }
  &__title {
    width: 100%;
    display: flex;
    justify-content: center;
    padding-right: 100px;
  }
}
</style>
