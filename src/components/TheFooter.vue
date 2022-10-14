<template>
  <div class="footer-wrapper">
    <contact-form></contact-form>
  </div>
</template>

<script>
import ContactForm from "@/components/ContactForm.vue";
export default {
  components: {
    ContactForm,
  },
};
</script>

<style scoped>
.footer-wrapper {
  min-height: 5rem;
  border-top: 3px solid black;
  padding: 1rem;
  background-color: rebeccapurple;
  position: absolute;
  bottom: 0;
  width: 100%;
}
</style>
