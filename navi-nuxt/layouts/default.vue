<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="conainer mx-auto p-4 flex justify-between ">
                <NuxtLink to="/" class="font-bold custom-color">Sneak-Hers</NuxtLink>
                <ul class="flex gap-4">
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/about">About us</NuxtLink></li>
                    <li><NuxtLink to="/contact">Contact us</NuxtLink></li>
                    <li><NuxtLink to="/products">Products</NuxtLink></li>
                </ul>
            </nav>
        </header>
    </div>

    <div class="container mx-auto p-4">
        <slot/>
    </div>
</template>

<style scoped>
    .router-link-exact-active{
        color: #12b488;
    }
    .custom-color{
        color: #12b488;
    }
</style>