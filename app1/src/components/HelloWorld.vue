<template>
  <v-container>
    <v-col elevation="10" class="text-center">
      <h1 style="color: #384FFE">
        INFORMACIÓN DEL ALUMNO
      </h1>
    </v-col>

    <v-row class="text-center">
      <v-col cols="12">
        <v-avatar size="178">
          <img src="@/assets/juan-escutia2.jpeg">
        </v-avatar>
      </v-col>
    </v-row>
    <v-row class="align-center mt-7">
      <v-col cols="3"></v-col>
      <v-col class="" cols="3">
        <p style="color: #384FFE; font-size: large" class="text-center font-weight-black">Nombre Completo</p>
      </v-col>
      <v-col cols="3">
        <p style="color: #384FFE; font-size: large" class="text-center font-weight-black">Matrícula</p>
      </v-col>
      <v-col cols="3"></v-col>
    </v-row>
    <v-row class="align-center mt-n5">
      <v-col cols="3"></v-col>
      <v-col class="text-lg-right mt-n6" cols="3">
        <p style="color: #384FFE; font-size: large" class="text-center font-weight-black text--disabled">Juan Escutia</p>
      </v-col>
      <v-col class="mt-n6" cols="3">
        <p style="color: #384FFE; font-size: large" class="text-center font-weight-black text--disabled">A01361234</p>
      </v-col>
      <v-col cols="3"></v-col>
    </v-row>
    <v-row class="align-center mt-2">
      <v-col cols="3"></v-col>
      <v-col class="" cols="3">
        <p style="color: #384FFE; font-size: large" class="text-center font-weight-black">Correo Institucional</p>
      </v-col>
      <v-col cols="3">
        <p style="color: #384FFE; font-size: large" class="text-center font-weight-black">Carrera</p>
      </v-col>
      <v-col cols="3"></v-col>
    </v-row>
    <v-row class="align-center mt-n5">
      <v-col cols="3"></v-col>
      <v-col class="text-lg-right mt-n6" cols="3">
        <p style="color: #384FFE; font-size: large" class="text-center font-weight-black text--disabled">A01361234@itesm.mx</p>
      </v-col>
      <v-col class="mt-n6" cols="3">
        <p style="color: #384FFE; font-size: large" class="text-center font-weight-black text--disabled">ISC</p>
      </v-col>
      <v-col cols="3"></v-col>
    </v-row>
    <v-row class="align-center mt-6" cols="12">
      <v-col class="mt-n6" cols="12">
        <p style="color: #384FFE; font-size: large" class="text-center font-weight-black">Correo Personal</p>
      </v-col>
      <v-col class="mt-n11" cols="12">
        <p style="color: #384FFE; font-size: large" class="text-center font-weight-black text--disabled">murioporlapatria@gmail.com</p>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>
