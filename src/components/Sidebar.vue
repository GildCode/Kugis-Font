<template>
    <div class="sidebar">
        <h2>Barra lateral</h2>
        <ul>
            <li>
                <router-link to="/contador">contador</router-link>
            </li>
            <li>
                <router-link to="/ListaDeTareas">Lista de tareas</router-link>
            </li>
        </ul>
      
    </div>
</template>

<script setup></script>


<style>
.sidebar{
    width: 200px;
    background-color: aqua;
    padding: 20px;
}

</style>