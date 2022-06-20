<template>
  <div>
    <PageTitle></PageTitle>
    <JumboHero></JumboHero>
  </div>
</template>

<script>
  import PageTitle from "./components/PageTitle.vue";
  import JumboHero from "./components/JumboHero.vue";

  export default {
    name: 'App',
    components: {
    PageTitle,
    JumboHero
}
  };
</script>

<style lang="scss">
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
