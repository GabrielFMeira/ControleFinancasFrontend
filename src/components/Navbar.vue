<template>
    <div id="navbar-container">
        <div class="btn-container">
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
        background-color: #023f23;
        display: flex;
        padding: 15px;
        align-items: center;
        border-bottom: 4px solid #010f08;
    }
    
    .btn-container a{
        text-decoration: none;
        padding: 5px;
        margin: 5px;
        font-weight: bold;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        color: #e6f7ef;
        transition: .2s;
    }

    .btn-container a:hover{
        color: #fff;
        text-align: center;
        text-shadow: 0 0 5px #fff, 0 0 10px #25252594;
    }

    .btn-container {
        margin-left: 20px;
        width: 100%;
    }


</style>