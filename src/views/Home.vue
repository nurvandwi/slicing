<template>
  <div class="home">
    <Nav />
    <Content />
  </div>
</template>

<script>
// @ is an alias to /src
import Nav from "@/components/Nav.vue";
import Content from "@/components/Content.vue";
export default {
  name: "Home",
  components: {
    Nav,
    Content
  }
};
</script>
