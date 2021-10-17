<template>
  <navbar />
  <div class="flex md:flex flex-wrap">
    <hello-world />

    <div class="w-full md:w-4/5 bg-grey-lightest">
      <div class="container bg-grey-lightest pt-16 px-6">
        Main Con
      </div>
    </div>
  </div>
</template>

<script>
import HelloWorld from "./components/Sidebar.vue";
import Navbar from "./components/Navbar.vue";
export default {
  name: "App",
  components: {
    HelloWorld,
    Navbar,
  },
};
</script>

<style>
#app {
}
</style>
