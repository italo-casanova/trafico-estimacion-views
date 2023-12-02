<template>
    <v-app>
      <v-container style="border-color: red;">
        <div style="border-color: green;">
            <traffic-view />
        </div>
      </v-container>
      <traffic-footer />
    </v-app>
  </template>
  

<script lang="ts" setup>

    import TrafficView from './View.vue'
    import TrafficFooter from '@/components/Footer.vue';


</script>