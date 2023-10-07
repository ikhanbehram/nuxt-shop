<template>
    <header class="shadow-sm bg-white">
        <nav class="container mx-auto p-4 flex justify-between">
            <NuxtLink to="/" class="font-bold">Nuxt Shop</NuxtLink>
            <ul class="flex gap-4">
                <li>
                    <NuxtLink to="/" class="font-bold">Home</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/about" class="font-bold">About</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/products" class="font-bold btn">Products</NuxtLink>
                </li>
            </ul>
        </nav>
    </header>
    <div class="container mx-auto p-4">
        <slot />
    </div>
</template>

<style scoped>
.router-link-exact-active {
    color: #12b488;
}
</style>