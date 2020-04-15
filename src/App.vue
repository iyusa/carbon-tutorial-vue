<template>
  <div id="app">
    <CvButton>Button</CvButton>
  </div>
</template>

<style lang="scss">
  @import "./styles/carbon";
</style>

<script>
import { CvButton } from '@carbon/vue';
export default {
  components: {
    CvButton,
  }
};
</script>