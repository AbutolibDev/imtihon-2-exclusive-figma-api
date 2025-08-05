<template>
    <div class="mx-auto w-[1400px] flex flex-col min-h-screen">
        <Navbar></Navbar>
        <main class="flex-grow">
<router-view></router-view>
</main>
<Footer></Footer>
    </div>
</template>

<script setup>
import Navbar from "./components/Navbar.vue"
import Footer from "./components/Footer.vue"
</script>

<style lang="scss" scoped>
// person1 changes
</style>

