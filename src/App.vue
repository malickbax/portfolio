<template>
  <div id="app">
    <NavBar></NavBar>
    <HeroHome></HeroHome>
    <SubHeroHome></SubHeroHome>
    <ApiHome></ApiHome>
    <FooterHome></FooterHome>
  </div>
</template>

<script>
import NavBar from "@/components/Navigation.vue";
import HeroHome from "@/components/Hero.vue";
import SubHeroHome from "@/components/SubHero.vue";
import ApiHome from "@/components/ApiHome.vue";
import FooterHome from "@/components/FooterHome.vue";
export default {
  name: 'App',
  components: {
    NavBar,
    HeroHome,
    SubHeroHome,
    ApiHome,
    FooterHome
  }
}
</script>
<style>
  @import "@/assets/css/theme.min.css";
  @import "@/assets/css/snippets.min.css"
</style>