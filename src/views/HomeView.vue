<template>
  <div class="home">
    <BuscarCancion msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import BuscarCancion from "@/components/BuscarCancion.vue";

export default {
  name: "HomeView",
  components: {
    BuscarCancion,
  },
};
</script>
<style>
.body {
  margin: 0;
  padding: 0;
}
</style>
