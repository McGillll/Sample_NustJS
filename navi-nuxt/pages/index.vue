<template>
    <title>Home</title>
    <div class="container flex flex-col justify-center mt-12">
        <div>
            <h1 class="font-bold text-center text-6xl custom-color">
                WELCOME TO<br> 
                SNEAK-HERS
            </h1>
        </div>
        <div class="mt-4">
            <h3 class="text-center text-s">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. <br>
                Dolore doloribus eligendi, quos numquam at modi iste animi <br>
                incidunt est nobis officiis dolorum.
            </h3>
        </div>
        <div class="container flex justify-center mt-8 custom-color font-semibold text-lg">
            <button class="shadow-lg p-2.5 rounded-lg">
                <NuxtLink to="/products">Get Started</NuxtLink>
            </button>
        </div>
    </div>

</template>

<script setup >

</script>

<style scoped>
    .custom-color{
        color: #12b488;
    }
</style>