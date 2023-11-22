<script setup>
import { RouterView } from 'vue-router'
</script>

<template>
    <div id="nav">
<Router-Link to="/">Inicio</Router-Link>|
<Router-Link to="/Brazil">Brazil</Router-Link>|
<Router-Link to="/about">Acerca de</Router-Link>
    </div>
<br>
<div class="container">
<RouterView/>
</div>
</template>

<style scoped>

</style>
