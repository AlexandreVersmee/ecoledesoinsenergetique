<template>
    <html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
        <link rel="stylesheet" href="./assets/bootstrap-4.5.2/css/bootstrap.min.css">
    </head>
    <body>
        <NavBar/>
        <div id="app">
            <router-view></router-view>
        </div>
    </body>
    </html>
</template>

<script>
    import NavBar from './components/NavBar.vue'

    export default {
        name: 'App',
        components: {
            NavBar
        }
    }
</script>

<style></style>
