<template>
  <div class="home">    
    <NavBar></NavBar>
    <!-- <AnimeCard></AnimeCard> -->
    <AnimeCoverPage></AnimeCoverPage>
    <Footer></Footer>
  </div>
</template>

<script>
// @ is an alias to /src
import NavBar from "@/components/NavBar.vue";
import Footer from "@/components/Footer.vue";
import HelloWorld from "@/components/HelloWorld.vue";
import AnimeCard from "@/components/AnimeCard.vue";
import AnimeCoverPage from "@/components/AnimeCoverPage.vue";

export default {
  name: "navbar",
  components: {
    NavBar,
    Footer,
    HelloWorld,
    AnimeCard,
    AnimeCoverPage
  }
};
</script>
