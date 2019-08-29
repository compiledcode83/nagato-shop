// shopping card here
<template>
  <div class="cart">
    <Title msg="Your Shopping Cart" />
  </div>
</template>

<script>
import Title from "@/components/Title.vue";

export default {
  name: "cart",
  components: {
    Title
  }
};
</script>

<style>
</style>