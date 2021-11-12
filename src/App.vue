<template>
  <div id="app">
    <div id="nav">
      <tete />
    </div>
    <router-view />
  </div>
</template>

<script>
import Tete from "@/components/Tete.vue";
export default {
  name: "app",
  components: {
    Tete,
  },
};
</script>

<style></style>
