<template>
    <div>
        <header class="shadow-bg bg-white">
            <nav class="container mx-auto p-4">
                <NuxtLink to="/products" class="font-bold">JEK</NuxtLink>
            </nav>
        </header>

        <div class="container mx-auto p-4">
            <slot />
        </div>
        <footer class="container mx-auto p-4 flex justify-between border-t-2">
            <ul class="flex gap-4">
                <li>
                    <NuxtLink to="/">Home</Nuxtlink>
                </li>
                <li>
                    <NuxtLink to="/about">About</Nuxtlink>
                </li>
                <li>
                    <NuxtLink to="/products">Products</Nuxtlink>
                </li>
            </ul>
        </footer>
    </div>
</template>

<style scoped>
.router-link-exact-active {
    color: rgb(10, 252, 62);
}
</style>