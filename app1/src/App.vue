<template>
  <v-app>
    <v-app-bar
      app
      color="#384FFE"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Logo Tec"
          class="shrink mr-2"
          contain
          src="@/assets/logoTec.png"
          transition="scale-transition"
          width="200"
        />
      </div>

      <v-spacer></v-spacer>
      <v-btn
        target="_blank"
        text
      >
        <router-link style="color: white" to="/">Inicio</router-link>
      </v-btn>

      <p> </p>
      <v-btn
        target="_blank"
        text
      >
        <router-link style="color: white" to="/about">Lista de Materias</router-link>
      </v-btn>

    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App'
}
</script>
