<template>
    <v-toolbar fixed app :clipped-left="clipped">
      <v-toolbar-side-icon></v-toolbar-side-icon>
      <v-toolbar-title v-text="title"></v-toolbar-title>
    </v-toolbar>
</template>

<script>
  export default {
    data () {
      return {
        clipped: false,
        title: 'vuetify template'
      }
    }
  }
</script>