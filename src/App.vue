<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

export default {
  name: "Main",
  components: {
    AppTitle,
    AppHero,
  },
};
</script>

<template>
  <AppTitle />
  <AppHero />
</template>
