<template>
  <div class="flex items-center justify-around h-screen w-screen bg-gray-800">
    <neon-one></neon-one>
    <neon-two></neon-two>
  </div>
</template>

<script>
import NeonOne from "./NeonOne.vue";
import NeonTwo from "./NeonTwo.vue";
export default {
  components: {
    "neon-one": NeonOne,
    "neon-two": NeonTwo
  }
};
</script>

<style scoped>
</style>