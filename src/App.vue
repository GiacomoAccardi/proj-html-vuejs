<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default{
  components: {
    AppHeader,
    AppMain, 
    AppFooter
  },
  data() {
    return {
      headerMenu: [
        { 
          id: 1,
          name: "Home",
          url: "#" 
        },
        { 
          id: 2,
          name: "Hop",
          url: "#" 
        },
        { 
          id: 3,
          name: "Products",
          url: "#" 
        },
        { 
          id: 4,
          name: "Categories",
          url: "#" 
        },
        { 
          id: 5,
          name: "News",
          url: "#" 
        },
        { 
          id: 6,
          name: "Elements",
          url: "#" 
        }
      ],

      footerMenu: [
        {
          id: 1,
          name: "© Copyright 2012 - 2020 |",
          url: "#"
        },
        {
          id: 2,
          name: "Avada Theme by Theme Fusion |",
          url: "#"
        },
        {
          id: 3,
          name: "All Rights Reserved |",
          url: "#"
        },
        {
          id: 4,
          name: "Powered by WordPress",
          url: "#"
        },
      ],
    }
  }
}
</script>

<template>
  <AppHeader :headerMenu="headerMenu" />
  <AppMain />
  <AppFooter :footerMenu="footerMenu" />
</template>

<style lang="scss">
@import "./styles/generals.scss";
</style>
