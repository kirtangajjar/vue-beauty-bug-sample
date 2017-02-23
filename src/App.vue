<template>
    <v-layout id="app">
      <v-header><h1 class="red-5">My Project</h1 ></v-header>
      <v-layout>
        <v-slider>Slider</v-slider>
        <v-content>Content</v-content>
      </v-layout>
      <v-footer>Copyright &copy; All rights reserved</v-footer>
    </v-layout>
</template>

<script>
import Hello from './components/Hello'

export default {
  name: 'app',
  components: {
    Hello
  }
}
</script>

<style>
.bg-primary {
  background: #555 !important;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /*text-align: center;*/
  color: #aaa;
  height: 100%;
}

.ant-layout-footer {
  text-align: center;
}
</style>
