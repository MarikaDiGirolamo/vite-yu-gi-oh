<script>
import AppHeader from './components/AppHeader.vue';
import AppComponent from './components/AppComponent.vue';
import AppCard from './components/AppCard.vue';

export default {
  name: "App",
  components: {
    AppHeader,
    AppComponent,
    AppCard
  }
}
</script>

<template>
  <AppHeader />
  <AppComponent />
  <AppCard />
</template>

<style lang="scss" scoped>
@use './styles/general.scss' as *;
@use './styles/partials/_mixins.scss' as *;
@use './styles/partials/_variables.scss' as *;
</style>
