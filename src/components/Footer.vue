<template>
        <v-footer class="text-center d-flex justify-center">
            <p>Copyright ©{{ currentYear }} All rights reserved </p>
        </v-footer>

</template>

<script lang="ts" setup>

    let currentYear = new Date().getFullYear()

</script>