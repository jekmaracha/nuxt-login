<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4 flex justify-between">
                <NuxtLink to="/" class="font-bold">JEK</NuxtLink>
                <ul class="flex gap-4">
                    <li>
                        <NuxtLink to="/">Home</Nuxtlink>
                    </li>
                    <li>
                        <NuxtLink to="/about">About</Nuxtlink>
                    </li>
                    <li>
                        <NuxtLink to="/products" class="btn">Products</Nuxtlink>
                    </li>
                </ul>
            </nav>
        </header>

        <div class="container mx-auto p-4">
            <slot />
        </div>
    </div>
</template>

<style scoped>
.router-link-exact-active {
    color: rgb(10, 252, 62);
}
</style>