<template>
    <header>
        <nav>
            <NuxtLink to="/">Nuxt Shop</NuxtLink>
            <ul>
                <li>
                    <NuxtLink to="/">Home</NuxtLink>
                    <NuxtLink to="/about">About</NuxtLink>
                    <NuxtLink to="/products">Products</NuxtLink>
                </li>
            </ul>
        </nav>
    </header>
    <slot />
</template>

<style scoped>
.router-link-exact-active{
    color: #12b488;
}
</style>