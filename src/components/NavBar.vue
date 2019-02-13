<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <router-link class="navbar-brand" :to="{ name: 'Home', params: {} }" id="brand_name">LERN</router-link>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarColor01" aria-controls="navbarColor01" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarColor01">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item">
                    <router-link class="nav-link" :to="{ name: 'Home', params: {} }">Accueil</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link" :to="{ name: 'Home', params: {} }">Array</router-link>
                </li>
            </ul>
            <ul class="nav navbar-nav navbar-right">
                <li class="nav-item">
                    <router-link class="nav-link" :to="{ name: 'Home', params: {} }">Compte</router-link>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<style scoped lang="css">
    nav {
        overflow: hidden;
        background-color: #333;
        font-family: Arial,sans-serif;
    }
    nav #brand_name{
        font-size: 1.7rem;
    }
    nav a {
        float: left;
        font-size: 16px;
        line-height: 16px;
        color: white;
        text-align: center;
        margin-left: 1.8rem;
        text-decoration: none;
    }
</style>
