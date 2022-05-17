<template>
  <div id="app">
    <!-- Header -->
    <header>
      <AppHeader />
    </header>
    <!-- /Header -->
    <!-- Main -->
    <main>questo è il main</main>
    <!-- /Main -->
    <!-- Footer -->
    <footer>questo è il footer</footer>
    <!-- /Footer -->
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";

export default {
  name: "App",
  components: {
    AppHeader,
  },
};
</script>

<style lang="scss"></style>
