<template>
  <div class="home">
    <Nav />
    <Content />
    <Features />
    <Technology />
    <Invitation />
  </div>
</template>

<script>
import Invitation from "@/components/Invitation.vue";
import Features from "@/components/Features.vue";
import Nav from "@/components/Nav.vue";
import Content from "@/components/Content.vue";
import Technology from "@/components/Technology.vue";
export default {
  name: "Home",
  components: {
    Nav,
    Content,
    Invitation,
    Features,
    Technology
  }
};
</script>

<style scoped>
</style>
