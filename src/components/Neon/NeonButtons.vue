<template>
  <div class="flex items-center justify-around h-screen w-screen bg-gray-800">
    <neon-one></neon-one>
    <neon-two></neon-two>
    <neon-three></neon-three>
    <neon-four></neon-four>
    <neon-five></neon-five>
  </div>
</template>

<script>
import NeonOne from "./NeonOne.vue";
import NeonTwo from "./NeonTwo.vue";
import NeonThree from "./NeonThree.vue";
import NeonFour from "./NeonFour.vue";
import NeonFive from "./NeonFive.vue";
export default {
  components: {
    "neon-one": NeonOne,
    "neon-two": NeonTwo,
    "neon-three": NeonThree,
    "neon-four": NeonFour,
    "neon-five": NeonFive
  }
};
</script>

<style scoped>
</style>