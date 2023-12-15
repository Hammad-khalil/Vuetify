<template>
  <VApp>
    <!-- Sidebar -->
    <SideBar />
    <VMain>
      <ImageGallery />
    </VMain>
  </VApp>
</template>
<script>
import SideBar from "./components/SideBar.vue";
import ImageGallery from "./components/ImageGallery.vue";
export default {
  components: {
    SideBar,
    ImageGallery,
  },
};
</script>