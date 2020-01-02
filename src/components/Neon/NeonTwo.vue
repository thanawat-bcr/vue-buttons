<template>
  <a class="relative inline-block overflow-hidden uppercase text-white text-2xl cursor-pointer">
    <span></span>
    <span></span>
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
  padding: 15px 30px;
  letter-spacing: 4px;
  transition: 200ms;
}
a:hover {
  background: white;
  color: #2d3748;
  box-shadow: 0 0 20px white, 0 0 40px white, 0 0 80px white;
  transition-delay: 1000ms;
}

a span {
  position: absolute;
  display: block;
}

a span:nth-child(1) {
  top: 0;
  left: -100%;
  width: 100%;
  height: 2px;
  background: linear-gradient(90deg, transparent, white);
}

a:hover span:nth-child(1) {
  left: 100%;
  transition: 500ms;
}

a span:nth-child(2) {
  top: -100%;
  right: 0;
  width: 2px;
  height: 100%;
  background: linear-gradient(180deg, transparent, white);
}

a:hover span:nth-child(2) {
  top: 100%;
  transition: 500ms;
  transition-delay: 250ms;
}

a span:nth-child(3) {
  bottom: 0;
  right: -100%;
  width: 100%;
  height: 2px;
  background: linear-gradient(270deg, transparent, white);
}

a:hover span:nth-child(3) {
  right: 100%;
  transition: 500ms;
  transition-delay: 500ms;
}

a span:nth-child(4) {
  bottom: -100%;
  left: 0;
  width: 2px;
  height: 100%;
  background: linear-gradient(360deg, transparent, white);
}

a:hover span:nth-child(4) {
  bottom: 100%;
  transition: 500ms;
  transition-delay: 750ms;
}
</style>