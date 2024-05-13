<template>
    <div>
        <title>Product</title>
        <div class="container flex justify-center">
            <h1 class="font-semibold custom-color text-3xl">Products</h1>
        </div>
        <div>
            <div class="container flex justify-center">
                <div class="shadow-xl p-2.5 rounded-lg">
                    <div class="picture ">  
                    </div>
                    <p class="font-bold">P59,000.00</p>
                    <p class="text-xs">
                        Lorem ipsum dolor sit amet <br>
                        consectetur adipisicing elit. <br>
                        Necessitatibus eveniet nobis <br> 
                        qui quis. Facere modi ipsa <br>
                        quidem in magni amet?
                    </p>
                    <div class="flex justify-center mt-4">
                        <button class="p-1 rounded-md bg-custom text-center">
                            <NuxtLink to="/products/shoes" class="text-white font-semibold">Details</NuxtLink>
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
    definePageMeta({
        layout: 'products',
    })
    
</script>

<style scoped>
    .custom-color{
        color: #12b488;
    }
    .picture{
        width: 150px;
        height: 100px;
        border: rgb(167, 167, 167) solid;
    }
    .bg-custom{
        background-color: #12b488;
    }
</style>