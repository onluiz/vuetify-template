<template>
  <v-app>
    <Header />
    <ListCards />
    <Footer />
  </v-app>
</template>

<script>
  import Header from './components/Header'
  import ListCards from './components/ListCards'
  import Footer from './components/Footer'
  
  export default {
    components: {
      Header,
      ListCards,
      Footer
    }
  }

</script>
