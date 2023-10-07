<template>
    <header class="shadow-sm bg-white">
        <nav class="container mx-auto p-4">
            <NuxtLink to="/products" class="font-bold">Nuxt Products</NuxtLink>

        </nav>
    </header>

    <div class="container mx-auto p-4">
        <slot />
    </div>

    <footer class="container mx-auto flex justify-between p-4 border-t-2">
        <ul class="flex gap-4">
            <li>
                <NuxtLink to="/" class="font-bold">Home</NuxtLink>
            </li>
            <li>
                <NuxtLink to="/about" class="font-bold">About</NuxtLink>
            </li>
            <li>
                <NuxtLink to="/products" class="font-bold">Products</NuxtLink>
            </li>
        </ul>
    </footer>
</template>

<style scoped>
.router-link-exact-active {
    color: #12b488;
}
</style>