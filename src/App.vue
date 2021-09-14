<template>
  <v-app>
    <div id="app">
      <div class="nav">
        <Appbar/>
      </div>
      <router-view/>
      <div>
        Footer div
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
<style scoped>
#app{
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #5f6368;
}
.nav{
  margin-top: 10px;
}
</style>
