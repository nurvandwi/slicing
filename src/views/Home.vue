<template>
  <div class="home">
    <Nav />
    <Content />
    <Video />
    <Invitation />
  </div>
</template>

<script>
import Invitation from "@/components/Invitation.vue";
import Video from "@/components/Video.vue";
import Nav from "@/components/Nav.vue";
import Content from "@/components/Content.vue";
export default {
  name: "Home",
  components: {
    Nav,
    Content,
    Invitation,
    Video
  }
};
</script>
