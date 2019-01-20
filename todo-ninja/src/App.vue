<template>
  <div id="app">
    <v-app class="grey lighten-4">
      <Navbar/>
      <v-content class="mx-4 mb-4">
        <router-view></router-view>
      </v-content>>
    </v-app>
  </div>
</template>
<script>
import Navbar from "@/components/Navbar.vue";
export default {
  name: "app",
  components: {
    Navbar
  },
  data() {
    return {
      text: ""
    };
  },
  methods: {
    appendIconCallback() {},
    prependIconCallback() {}
  }
};
</script>