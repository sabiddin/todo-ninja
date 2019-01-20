<template>
  <v-app>
    <v-content>
      <v-menu offset-y>
        <v-btn slot="activator"  color="primary" dark >  Dropdown </v-btn>
        <v-list>
          <v-list-tile>
            <v-list-tile-title>Choice 1</v-list-tile-title>
          </v-list-tile>
          <v-list-tile>
            <v-list-tile-title>Choice 1</v-list-tile-title>
          </v-list-tile>
        </v-list>
      </v-menu>
      
      <v-btn color="secondary" v-on:click="clickMe()">Click me!</v-btn>
    </v-content>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue';
export default Vue.extend({
  name: 'ContactDemo',
  props: {
    //msg: String,
  },  
  methods: {
    clickMe() {
    alert('Thanks for clicking me');
  }
  }
});
</script>

<style scoped>
  #input-usage .v-input__prepend-outer,
  #input-usage .v-input__append-outer,
  #input-usage .v-input__slot,
  #input-usage .v-messages {
    border: 1px dashed rgba(0,0,0, .4);
  }
</style>

