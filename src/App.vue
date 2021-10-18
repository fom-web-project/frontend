<template>
  <div class="bg-gray-100">
    <header>
      <Navigation />
    </header>

    <router-view />
  </div>
</template>

<script>
import Navigation from "./components/Navigation.vue";

export default {
  components: {
    Navigation,
  },
};
</script>
