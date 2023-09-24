<template>
  <v-app>
    <NavBar/>
    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

import { defineComponent } from 'vue';

// Components
import NavBar from './components/NavBar.vue';

export default defineComponent({
  name: 'App',

  components: {
    NavBar
  },
});
</script>
