<template>
    <header>
        <nav>
            <NuxtLink to="/products">Nuxt Products</NuxtLink>

        </nav>
    </header>

    <div>
        <slot />
    </div>

    <footer>
        <ul>
            <li>
                <NuxtLink to="/">Home</NuxtLink>
                <NuxtLink to="/about">About</NuxtLink>
                <NuxtLink to="/products">Products</NuxtLink>
            </li>
        </ul>
    </footer>
</template>

<style scoped>
.router-link-exact-active {
    color: #12b488;
}
</style>