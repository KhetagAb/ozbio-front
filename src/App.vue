<template>
  <v-app>
    <v-main>
      <Header/>
      <Middle/>
      <Footer/>
    </v-main>
  </v-app>
</template>

<script>
import Header from "@/components/Header";
import Footer from "@/components/Footer";
import Middle from "@/components/Middle";

export default {
  name: 'App',

  components: {
    Middle,
    Footer,
    Header,
  },

  data: () => ({
    //
  }),
};
</script>
