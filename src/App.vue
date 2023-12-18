<template>
  <VApp>
    <TitleBar />
    <!-- Sidebar -->
    <SideBar />
    <VMain>
      <ImageGallery />
    </VMain>
    <BottomFooter />
  </VApp>
</template>
<script>
import SideBar from "./components/SideBar.vue";
import ImageGallery from "./components/ImageGallery.vue";
import TitleBar from "./components/TitleBar.vue";
import BottomFooter from "./components/BottomFooter.vue";
export default {
  components: {
    SideBar,
    ImageGallery,
    TitleBar,
    BottomFooter,
  },
};
</script>
<style>
h1 {
  text-align: center;
  font-family: cursive;
  color: tomato;
}
</style>