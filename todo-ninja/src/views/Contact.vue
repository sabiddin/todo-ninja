<template>
  <div class="text-xs-center">
    <v-badge left>
      <span slot="badge">2</span>
      <span>Examples</span>
    </v-badge>

    &nbsp;&nbsp;

    <v-badge color="green">
      <v-icon slot="badge" dark small>list</v-icon>
      <span>Lists</span>
    </v-badge>
  </div>
</template>
<script lang="ts">
import Vue from 'vue';
import ContactDemo from '@/components/ContactDemo.vue';
export default Vue.extend({
    name: 'contact',
  components: {
    ContactDemo,
  },
});
</script>
