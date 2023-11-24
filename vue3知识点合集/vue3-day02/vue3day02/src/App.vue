<script>
import HomeView from "./components/HomeView.vue";
export default {
  data() {
    return {
      message: "helloworld",
    };
  },
  components: {
    HomeView,
  },
};
</script>

<template>
  <div>
    <HomeView></HomeView>
  </div>
</template>

<style>
</style>
