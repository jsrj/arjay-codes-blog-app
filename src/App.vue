<template>
  <v-app>

    <Titlebar />

    <v-content>
      <router-view />
    </v-content>
  </v-app>
</template>

<script>
import Titlebar from "@/components/layout/navigation/Titlebar.vue";
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    Titlebar,
    HelloWorld
  },
  data () {
    return {
      //
    }
  }
}
</script>
