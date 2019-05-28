<template>
    <v-toolbar app id="blog-toolbar">
      <v-toolbar-title class="headline text-uppercase">
        <!-- TITLE -->
      </v-toolbar-title>
      <v-spacer></v-spacer>
    </v-toolbar>
</template>

<script>
export default {
  name: "Titlebar",
  props: {},
  components: {
    Logo,
    Droplet
  },
  methods: {
    toggleTitleBar () {
      // If showTitlebar is false, set #blog-toolbar 'width' property to 0%
      // Else, set #blog-toolbar 'width' property to 100%
      // Invert the value of showTitlebar
    }
  },
  data () {
    return {
      showTitlebar: false
    }
  }
}
</script>

<style lang="less" scoped>
  #blog-toolbar {
    display: flex;
    flex-flow: row nowrap;
    height: 6%;
    width: 100%;
  }
</style>


