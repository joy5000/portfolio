<template>
  <Header />
  <imgandaddress />
  <education />
  <projects />
  <experience />
  <contuct />
  
  <footer1 />
  <router-view/>
</template>


<script>
import Header from "@/components/Header";
import imgandaddress from "@/components/imgandaddress";
import Education from "./components/education.vue";
import Projects from "./components/projects.vue";
import Experience from "./components/experience.vue";
import Contuct from "./components/contuct.vue";
import footer from "./components/footer.vue";
import Footer1 from "./components/footer.vue";


export default {

    components: {
    Header,
    imgandaddress,
    Education,
    Projects,
    Experience,
    Contuct,
    footer,
    Footer1
},

}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}


</style>
