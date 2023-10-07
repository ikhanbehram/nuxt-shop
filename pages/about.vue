<template>
    <div>
        {{ data.aboutMessage }}
    </div>
</template>

<script setup>
const {data} = await useFetch('/api/about')
</script>

<style scoped></style>