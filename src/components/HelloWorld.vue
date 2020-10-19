<template>
  <div class="hello">
    <p><router-link :to="{ name: 'Home' }">Router Link</router-link></p>
    <p><b-link :to="{ name: 'Home' }">Bootstrap Link</b-link></p>
  </div>
</template>

<script lang="ts">
import Vue from 'vue';

import {BLink } from 'bootstrap-vue';

export default Vue.extend({
  components: {
    BLink: BLink
  }
});
</script>
