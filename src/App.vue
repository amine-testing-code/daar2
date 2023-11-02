<template>
  <v-app>
    <NavBar />
    <v-content class="ma-4">
      <router-view></router-view>
    </v-content>
    <AppFooter />
  </v-app>
</template>
<script>

import NavBar from "@/components/NavBar";
import AppFooter from "@/components/AppFooter";
export default {
  name: "App",

  components: {
   NavBar,
   AppFooter,
  },

  data: () => ({
    //
  }),
};

</script>