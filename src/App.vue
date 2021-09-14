<template>
  <v-app>
    <div id="app">
      <div class="nav">
        <Appbar/>
      </div>
    </div>

  </v-app>
</template>

<script>

import Appbar from './components/Appbar';

export default {
  name: 'App',

components: {
  Appbar,
},

  data: () => ({
    //
  }),
};
</script>
