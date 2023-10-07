<template>
    <div class="mt-7 max-w-sm mx-auto text-center card">
        <p class="mt-7 text-7xl font-bold">{{ error.statusCode }}</p>
        <p class="mt-7 text-6xl ">Oops.</p>
        <p class="mt-7">{{ error.message }}</p>
        <button class="my-7 btn" @click="handleGoHome">Go home..</button>
    </div>
</template>

<script setup>
 defineProps(['error'])

 const handleGoHome = () => clearError({
    redirect: '/'
 })
</script>

<style  scoped>

</style>