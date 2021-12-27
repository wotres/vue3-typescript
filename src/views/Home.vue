<template>
  <div class="home">
    <home-header />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HomeHeader from '@/layout/header/HomeHeader.vue';

export default defineComponent({
  name: 'Home',
  components: {
    HomeHeader,
  },
});
</script>
