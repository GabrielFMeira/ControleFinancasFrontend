<template>
    <div id="navbar-container">
        <div id="btn-container">
            <router-link to="/">Home</router-link>
            <router-link to="/contas">Contas</router-link>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Navbar'
    }
</script>

<style>

    #navbar-container {
        height: 50px;
        background-color: aqua;
        display: flex;
        padding: 15px;
        text-decoration: none;
    }

</style>