<template>

    <v-container  fluid style="border-color: red;"  >
        <v-row  class="color-red">
            <v-col cols="8" class="d-flex">
                <v-col>
                    <label for="" class="">Facultad</label>
                    <v-select
                    :items="items_facultad"
                    density="compact"
                    >
                    </v-select>
                </v-col>
                
                <v-col>
                    <label for="">Zona</label>
                    <v-select
                    :items="items_zona"
                    density="compact"
                    >
                    </v-select>
                </v-col>
                
                <v-col>
                    <label for="">Vía</label>
                    <v-select
                    :items="items_via"
                    density="compact"
                    >
                    </v-select>
                </v-col>
            </v-col>
            <v-col cols="4" class="d-flex align-center justify-center" >
                <v-btn >
                    Buscar
                </v-btn>
            </v-col>
        </v-row>

    </v-container>


    <v-container fluid class="fill-height" style="border-color: green;">

    </v-container>

</template>

<script lang="ts" setup>

    const items_facultad=['A','B','C']
    const items_zona=['A','B','C']
    const items_via=['A','B','C']



</script>