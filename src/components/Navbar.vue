<template>
    <div id="nav">
        <router-link to="/">
            <img src="" id="logo">
        </router-link>
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
    </div>
    <router-view/>
    

</template>

<script>
    export default {
        name: "Navbar"
    }

</script>

<style scoped>

</style>