<script setup>
import Card from '../CardVue.vue'
</script>
<template>
    <div class="home">
        <div class="home-card">
            <Card />
            <Card />
            <Card />
        </div>
        <div style="border-top: 3px solid black; width: 80%; background-color: blue; margin: 10px auto;"></div>
        <div class="home-card">
            <Card />
            <Card />
            <Card />
        </div>
        <div style="border-top: 3px solid black; width: 80%; background-color: blue; margin: 10px auto;"></div>

    </div>
</template>

<style>
.home {
    width: 100%;
    flex-grow: 1;
    background-color: rgb(176, 189, 191);

}

.home-card {
    width: 100%;
    flex-grow: 1;
    display: flex;
    justify-content: space-evenly;
    margin-top: 25px;
    padding-bottom: 15px;
}
</style>