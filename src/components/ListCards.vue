<template>
    <main>
      <v-content>
        <v-container fluid>
            <div v-for="card in cards">
                    <Card />
                </div>
        </v-container>
      </v-content>
    </main>
</template>

<script>
import Card from './Card'

export default {
  components: {
    Card
  },
  data () {
    return {
      cards: [{
        id: 1,
        title: 'Título'
      }]
    }
  }
}
</script>
