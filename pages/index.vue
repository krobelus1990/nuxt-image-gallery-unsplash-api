<template>
  <div>
    <div class="bg-green-600">
      <div class="p-4">
        <h1 class="text-center text-3xl text-white font-bold">
          Unsplash Image Gallery
        </h1>
      </div>
    </div>
    <GalleryVue />
  </div>
</template>

<script>
import GalleryVue from "../components/Gallery.vue";

export default {
  name: "IndexPage",
  head() {
    return {
      title: "Unsplash image gallery",
    };
  },
  components: {
    GalleryVue,
  },
};
</script>
