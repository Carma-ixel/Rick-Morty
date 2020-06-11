<template>
  <v-layout>
    <v-flex>
      <v-container my-5>
        <v-row>
          <v-col v-for="pj in figure" :key="pj" cols="12" lg="4" md="4">
            <v-card class="pa-2 x" width="500">
              <v-img class="white--text align-end" height="200px" :src="pj.image"></v-img>
              <v-card-text class="text--primary">
                <div>{{pj.name}}</div>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-flex>
  </v-layout>
</template>
<script>
export default {
  data: () => ({
    figure: [
      {
        id: 1,
        name: 'Morty',
        image: 'https://rickandmortyapi.com/api/character/avatar/2.jpeg'
      },
      {
        id: 2,
        name: 'Rick',
        image: 'https://rickandmortyapi.com/api/character/avatar/1.jpeg'
      },
      {
        id: 3,
        name: 'Summer',
        image: 'https://rickandmortyapi.com/api/character/avatar/3.jpeg'
      },
      {
        id: 4,
        name: 'Beth',
        image: 'https://rickandmortyapi.com/api/character/avatar/4.jpeg'
      },
      {
        id: 5,
        name: 'Jerry',
        image: 'https://rickandmortyapi.com/api/character/avatar/5.jpeg'
      }
    ]
  })
}
</script>
<style  scoped>
.x{
  background-color:  rgb(55, 56, 56);;
}
</style>
