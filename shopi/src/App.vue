<template>
<v-app>
    <!-- <v-app-bar></v-app-bar> -->
    <v-main>
        <v-container>
            Hello World
        </v-container>
        <!-- creating alerts -->
        <v-alert type="success" border>
            Application successfull
        </v-alert>
        <v-alert color="red lighten-2" border="top"></v-alert>
        <v-alert border="top" type="success" colored-border color="deep-purple accent-4" elevation="2"></v-alert>

        <!-- avatars -->
        <v-avatar color="indigo" size="50">
            <span class="white--text">20</span>
        </v-avatar>

    </v-main>
</v-app>
</template>

<script>
export default {

}
</script>

<style>

</style>
