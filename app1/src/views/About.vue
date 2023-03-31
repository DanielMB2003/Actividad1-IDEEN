<template>
  <v-container>
    <v-col elevation="10" class="text-center">
      <h1 style="color: #384FFE">
        MATERIAS INSCRITAS
      </h1>
    </v-col>
    <v-sheet
      class="mt-10"
      color="white"
      rounded
      elevation="6"
      height="100"
      width="100%"
    >
      <v-row>
        <v-col cols="12">
          <p style="color: #384FFE; font-size: large"
             class="text-left font-weight-black pl-10 pt-2">Título de la materia</p>
        </v-col>
        <v-col cols="12">
          <p style="font-size: large"
             class="text-left font-weight-black text--disabled mt-n10 ml-10">
            Profesor: Cristiano Ronaldo</p>
        </v-col>
        <v-col cols="3"></v-col>
        <v-col cols="3"></v-col>
        <v-col cols="3"></v-col>
        <v-col class="align-content-end" cols="3">
          <v-dialog
            v-model="dialog"
            width="500"
          >
            <template v-slot:activator="{ on, attrs }">
              <v-btn
                class="mt-n12"
                color="#384FFE"
                dark
                v-bind="attrs"
                v-on="on"
              >
                Ver Detalles
              </v-btn>
            </template>

            <v-card>
              <v-card-title style="color: #384FFE; font-size: large"
                            class="text-center font-weight-black">
                Título de la Materia
              </v-card-title>

              <v-card-text>
                <v-col cols="12" class="text-left ml-n3">
                  <p style="font-size: large"
                     class="text-lg-left font-weight-black text--disabled">Profesor: Cristiano Ronaldo</p>
                </v-col>
                <v-col cols="12" class="text-left ml-n3 mt-n7">
                  <p style="font-size: large"
                     class="text-lg-left font-weight-black text--disabled">Salón: La Congeladora</p>
                </v-col>
                <v-col cols="12" class="text-left ml-n3 mt-n7">
                  <p style="font-size: large"
                     class="text-lg-left font-weight-black text--disabled">Días: Lunes, Miércoles y Viernes</p>
                </v-col>
                <v-col cols="12" class="text-left ml-n3 mt-n7">
                  <p style="font-size: large"
                     class="text-lg-left font-weight-black text--disabled">Horario: 7:00 a 9:00 a.m</p>
                </v-col>
              </v-card-text>
            </v-card>
          </v-dialog>
        </v-col>
      </v-row>
    </v-sheet>
    <v-sheet
      class="mt-10"
      color="white"
      rounded
      elevation="6"
      height="100"
      width="100%"
    >
      <v-row>
        <v-col cols="12">
          <p style="color: #384FFE; font-size: large"
             class="text-left font-weight-black pl-10 pt-2">Título de la materia</p>
        </v-col>
        <v-col cols="12">
          <p style="font-size: large"
             class="text-left font-weight-black text--disabled mt-n10 ml-10">
            Profesor: Cristiano Ronaldo</p>
        </v-col>
        <v-col cols="3"></v-col>
        <v-col cols="3"></v-col>
        <v-col cols="3"></v-col>
        <v-col class="align-content-end" cols="3">
          <v-dialog
            v-model="dialog"
            width="500"
          >
            <template v-slot:activator="{ on, attrs }">
              <v-btn
                class="mt-n12"
                color="#384FFE"
                dark
                v-bind="attrs"
                v-on="on"
              >
                Ver Detalles
              </v-btn>
            </template>

            <v-card>
              <v-card-title style="color: #384FFE; font-size: large"
                            class="text-center font-weight-black">
                Título de la Materia
              </v-card-title>

              <v-card-text>
                <v-col cols="12" class="text-left ml-n3">
                  <p style="font-size: large"
                     class="text-lg-left font-weight-black text--disabled">Profesor: Cristiano Ronaldo</p>
                </v-col>
                <v-col cols="12" class="text-left ml-n3 mt-n7">
                  <p style="font-size: large"
                     class="text-lg-left font-weight-black text--disabled">Salón: La Congeladora</p>
                </v-col>
                <v-col cols="12" class="text-left ml-n3 mt-n7">
                  <p style="font-size: large"
                     class="text-lg-left font-weight-black text--disabled">Días: Lunes, Miércoles y Viernes</p>
                </v-col>
                <v-col cols="12" class="text-left ml-n3 mt-n7">
                  <p style="font-size: large"
                     class="text-lg-left font-weight-black text--disabled">Horario: 7:00 a 9:00 a.m</p>
                </v-col>
              </v-card-text>
            </v-card>
          </v-dialog>
        </v-col>
      </v-row>
    </v-sheet>
    <v-sheet
      class="mt-10"
      color="white"
      rounded
      elevation="6"
      height="100"
      width="100%"
    >
      <v-row>
        <v-col cols="12">
          <p style="color: #384FFE; font-size: large"
             class="text-left font-weight-black pl-10 pt-2">Título de la materia</p>
        </v-col>
        <v-col cols="12">
          <p style="font-size: large"
             class="text-left font-weight-black text--disabled mt-n10 ml-10">
            Profesor: Cristiano Ronaldo</p>
        </v-col>
        <v-col cols="3"></v-col>
        <v-col cols="3"></v-col>
        <v-col cols="3"></v-col>
        <v-col class="align-content-end" cols="3">
          <v-dialog
            v-model="dialog"
            width="500"
          >
            <template v-slot:activator="{ on, attrs }">
              <v-btn
                class="mt-n12"
                color="#384FFE"
                dark
                v-bind="attrs"
                v-on="on"
              >
                Ver Detalles
              </v-btn>
            </template>

            <v-card>
              <v-card-title style="color: #384FFE; font-size: large"
                            class="text-center font-weight-black">
                Título de la Materia
              </v-card-title>

              <v-card-text>
                <v-col cols="12" class="text-left ml-n3">
                  <p style="font-size: large"
                     class="text-lg-left font-weight-black text--disabled">Profesor: Cristiano Ronaldo</p>
                </v-col>
                <v-col cols="12" class="text-left ml-n3 mt-n7">
                  <p style="font-size: large"
                     class="text-lg-left font-weight-black text--disabled">Salón: La Congeladora</p>
                </v-col>
                <v-col cols="12" class="text-left ml-n3 mt-n7">
                  <p style="font-size: large"
                     class="text-lg-left font-weight-black text--disabled">Días: Lunes, Miércoles y Viernes</p>
                </v-col>
                <v-col cols="12" class="text-left ml-n3 mt-n7">
                  <p style="font-size: large"
                     class="text-lg-left font-weight-black text--disabled">Horario: 7:00 a 9:00 a.m</p>
                </v-col>
              </v-card-text>
            </v-card>
          </v-dialog>
        </v-col>
      </v-row>
    </v-sheet>
    <v-sheet
      class="mt-10"
      color="white"
      rounded
      elevation="6"
      height="100"
      width="100%"
    >
      <v-row>
        <v-col cols="12">
          <p style="color: #384FFE; font-size: large"
             class="text-left font-weight-black pl-10 pt-2">Título de la materia</p>
        </v-col>
        <v-col cols="12">
          <p style="font-size: large"
             class="text-left font-weight-black text--disabled mt-n10 ml-10">
            Profesor: Cristiano Ronaldo</p>
        </v-col>
        <v-col cols="3"></v-col>
        <v-col cols="3"></v-col>
        <v-col cols="3"></v-col>
        <v-col class="align-content-end" cols="3">
          <v-dialog
            v-model="dialog"
            width="500"
          >
            <template v-slot:activator="{ on, attrs }">
              <v-btn
                class="mt-n12"
                color="#384FFE"
                dark
                v-bind="attrs"
                v-on="on"
              >
                Ver Detalles
              </v-btn>
            </template>

            <v-card>
              <v-card-title style="color: #384FFE; font-size: large"
                            class="text-center font-weight-black">
                Título de la Materia
              </v-card-title>

              <v-card-text>
                <v-col cols="12" class="text-left ml-n3">
                  <p style="font-size: large"
                     class="text-lg-left font-weight-black text--disabled">Profesor: Cristiano Ronaldo</p>
                </v-col>
                <v-col cols="12" class="text-left ml-n3 mt-n7">
                  <p style="font-size: large"
                     class="text-lg-left font-weight-black text--disabled">Salón: La Congeladora</p>
                </v-col>
                <v-col cols="12" class="text-left ml-n3 mt-n7">
                  <p style="font-size: large"
                     class="text-lg-left font-weight-black text--disabled">Días: Lunes, Miércoles y Viernes</p>
                </v-col>
                <v-col cols="12" class="text-left ml-n3 mt-n7">
                  <p style="font-size: large"
                     class="text-lg-left font-weight-black text--disabled">Horario: 7:00 a 9:00 a.m</p>
                </v-col>
              </v-card-text>
            </v-card>
          </v-dialog>
        </v-col>
      </v-row>
    </v-sheet>
  </v-container>
</template>
