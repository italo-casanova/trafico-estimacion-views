<template>
  <v-app>
    <div class="fill-height d-flex flex-column align-center justify-center" >
      <default-view/>
      
    </div>
    <div  class='.self-alingn-end' style="height: 100px;">
      <default-footer />
    </div>
  </v-app>
</template>

<script lang="ts" setup>

  import DefaultView from './View.vue'
  import DefaultFooter from '@/components/Footer.vue'
  import DefaultSideBar from './SideBar.vue'

</script>

<style>

*{
  border: solid 1px;
}
</style>
