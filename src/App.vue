<template>
  <v-app>
    <tool-bar></tool-bar>
    <v-content>
      <router-view></router-view>
    </v-content>
    <Footer/>
  </v-app>
</template>

<script>

export default {
  name: "App",
  components: {
    
  },
  data() {
    return {
      //
    };
  }
};
</script>
<style lang="scss">
@import "App.scss";
</style>
