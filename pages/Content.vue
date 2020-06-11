<template>
 <v-layout>
   <v-container >
     <v-row align="center" justify="center">
      <v-col cols="12" md="4" sm="8">
       <h1 class="m">Narrativa</h1>
        <v-card max-width="500" pa-10>
          <v-card-text color="grey" >
            <h3>Dan Harmon ha escrito en muchas ocasiones sobre la narrativa audiovisual.La más importante que se plasma en Rick y Morty es la diferencia entre la narrativa básica de formato largometraje. El esquema circular es dividido en 8 pasos: </h3>
              <p>
              1. Un personaje está en su zona de confort.<br>
              2. Pero quiere algo.<br>
              3. Entra en una situación no reconocida.<br>
              4. Se adapta a ello.<br>
              5. Consigue lo que quiere.<br>
              6. Pero paga un alto precio.<br>
              7. Vuelve a la situación de partida, cómoda.<br>
              8. Ha cambiado.<br>
              </p>
              <p>La creación de este círculo estructural ha sido claramente influenciada por El héroe de las mil caras, de Joseph Campbell. También se puede apreciar similitudes con las teorías del guion cinematográfico que el autor Robert McKee revela en su obra El guion. </p>
          </v-card-text>
        </v-card>
        <v-btn flat nuxt class="m-2" to="/">
          Volver
        </v-btn>
      </v-col>
    </v-row>
   </v-container>
</v-layout>
</template>
<style scoped>
.m-2{
  margin-top: 1rem;
}
.m{
  margin-bottom: 1rem;
}
</style>
