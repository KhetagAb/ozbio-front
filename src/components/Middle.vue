<template>
  <div class="middle">
<!--    <Sidebar :posts="sidePosts"/>-->
    <main>
      <Scheme v-if="page==='Map'"></Scheme>
    </main>
  </div>
</template>

<script>

import Scheme from "@/components/scheme/Scheme";
export default {
  name: "Middle",
  components: {Scheme},
  data: function () {
    return {
      page: "Map",
    }
  },
}
</script>

<style scoped>

</style>
