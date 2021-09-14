<template>
    <v-container>
    <v-col cols="12" sm="8" md="6" class="body_inputContainer">
      <img class="google_logo" src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png"/>
    </v-col>
    <v-col cols="12" sm="8" md="6" class="body_inputContainer">
      <Search/>
    </v-col>
    </v-container>
</template>

<script>
  import Search from '../components/Search.vue'

  export default {
    name: 'Home',

    components: {
     Search,
    },
  }
</script>

<style scoped>
.google_logo {
  padding-top: 105px;
}
.body_inputContainer {
  margin-left: auto;
  margin-right: auto;

}
</style>
