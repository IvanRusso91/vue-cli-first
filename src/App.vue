<template>
  <div>
    <HeaderComp />
    <HeroComp />
  </div>
</template>

<script>

import HeaderComp from "./components/HeaderComp.vue";
import HeroComp from './components/HeroComp';

export default {
  name: 'app',
  components: {
   HeaderComp,
   HeroComp,
  }
}
</script>

<style>

</style>
