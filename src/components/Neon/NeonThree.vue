<template>
  <a
    href="#"
    class="py-4 px-12 border-2 border-white border-solid relative z-0 overflow-hidden uppercase text-white text-2xl"
  >
    <span></span>
    <span></span>
    Button
  </a>
</template>

<script>
export default {};
</script>

<style scoped>
a {
  letter-spacing: 4px;
  transition: 200ms;
}

a span {
  position: absolute;
  display: block;
  transition: 1000ms;
}

a span:nth-child(1) {
  top: 0;
  left: -200%;
  width: 200%;
  height: 200%;
  transform: rotate(30deg);
  background: linear-gradient(transparent, white, transparent);
}

a:hover span:nth-child(1) {
  left: 200%;
}
</style>