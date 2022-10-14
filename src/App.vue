<template>
  <div class="main-container">
    <the-footer></the-footer>
  </div>
</template>

<script>
import TheFooter from "@/components/TheFooter.vue";
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: "App",
  components: { TheFooter },
};
</script>

<style>
body {
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}
</style>
