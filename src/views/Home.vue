<template>
  <div class="home">
    <Nav />
    <Content />
    <Features />
    <Technology />
    <Aplication />
  </div>
</template>

<script>
import Aplication from "@/components/Aplication.vue";
import Features from "@/components/Features.vue";
import Nav from "@/components/Nav.vue";
import Content from "@/components/Content.vue";
import Technology from "@/components/Technology.vue";
export default {
  name: "Home",
  components: {
    Nav,
    Content,
    Aplication,
    Features,
    Technology
  }
};
</script>

<style scoped>
</style>
