<template>
  <div class="outer-container">
    <app-header/>
    <app-nav/>
    <nuxt/>
  </div>
</template>

<script>
import AppHeader from '~/components/AppHeader.vue';
import AppNav from '~/components/AppNav.vue';

export default {
  components: {
    AppHeader,
    AppNav
  }
}
</script>

<style>

</style>

