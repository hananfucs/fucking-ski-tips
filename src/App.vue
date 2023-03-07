<template>
  <v-app class="hello">
    <v-main>
      <HelloWorld class="hello"/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
}
</script>
<style scoped>
.hello {
  width: 100%;
}
</style>