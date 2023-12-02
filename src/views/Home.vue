<template>
  <v-container style="border-color: green;">
    <v-row justify="center" class="flex-wrap">
      <v-col cols="auto" class="grow d-flex flex-column mr-16  ">
        <v-row class="d-flex flex-column">
          <h1>Estimación de transito peatonal</h1>
          <p>Eliga opción</p>
        </v-row>
        <v-row justify="space-between" class="d-flex align-end mb-4">
          <v-btn
          width="200px"
          height="50px"
          color="#922729"
          >
            Histórico
          </v-btn>
          <v-btn 
          width="200px"
          height="50px"
          color="#922729"
          >
            Tiempo real
          </v-btn>
        </v-row>
      </v-col>
      <v-col cols="auto">
        <v-img
        src="@/assets/logoUNI.png"
        alt="Logo UNI"
        width="200"
        height="auto"
        >

        </v-img>
      </v-col>
    </v-row>
  </v-container>

</template>

<script lang="ts" setup>


</script>

<style>

/* *{
  border: solid 1px;
} */
</style>