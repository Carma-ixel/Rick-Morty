<template>
  <v-footer
    color="dark"
    padless
  >
    <v-row
      justify="center"
      no-gutters>
     <v-btn
        v-for="(item, i) in links"
        :key="i"
        :to="item.to"
        router
        exact
        color="white"
        text
        rounded
        class="my-2">
        {{ item.title }}
      </v-btn>
      <v-col
        class="dark lighten-2 py-4 text-center white--text"
        cols="12"
      >
        {{ new Date().getFullYear() }} — <strong>Rick and Morty</strong>
      </v-col>
    </v-row>
  </v-footer>
</template>
<script>
export default {
  data: () => ({
    links: [
      {
        title: 'Home',
        to: '/'
      },
      {
        title: 'Narrativa',
        to: '/content'
      }
    ]
  })
}
</script>
