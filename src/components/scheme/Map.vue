<template>
  <svg-map :map="Taiwan" />
</template>

<script>
import { SvgMap } from "vue-svg-map";
import Taiwan from "@svg-maps/japan";

export default {
  name: "" +
      "Map",
  components: {
    SvgMap
  },
  data() {
    return {
      Taiwan
    };
  }
};
</script>

<style src="../../../node_modules/vue-svg-map/dist/index.css"></style>