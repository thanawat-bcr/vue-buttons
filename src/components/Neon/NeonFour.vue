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
  background-color: #fff;
  z-index: -1;
}

a:hover {
  color: #2d3748;
  box-shadow: 0 0 10px white, 0 0 40px white, 0 0 50px white;
  transition-delay: 300ms;
}

a span:nth-child(1) {
  top: 0%;
  left: -300%;
  width: 400%;
  height: 400%;
  transform: rotate(45deg);
}

a:hover span:nth-child(1) {
  left: -150%;
}

a span:nth-child(2) {
  bottom: 0%;
  right: -300%;
  width: 400%;
  height: 400%;
  transform: rotate(45deg);
}

a:hover span:nth-child(2) {
  right: -150%;
}
</style>