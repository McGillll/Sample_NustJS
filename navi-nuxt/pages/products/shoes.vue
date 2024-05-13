<template>
    <div class="container flex flex-col items-center">

        <div class="rounded-lg picture "></div>
        <div class="custom-width">
            <h1 class="font-bold text-lg">Shoes</h1>
            <p class="font-semibold">P59,000.00</p>
            <p class="text-xs">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Necessitatibus eveniet nobis qui quis. Facere modi ipsa 
                quidem in magni amet?
            </p>
            <p class="text-xs">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Necessitatibus eveniet nobis qui quis. Facere modi ipsa 
                quidem in magni amet?
            </p>
            <div class="mt-4">
                <button class="p-1 rounded-md bg-custom text-center text-white">Place Order</button>
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
    .picture{
        width: 75%;
        height: 250px;
        border: rgb(167, 167, 167) solid;
    }
    .custom-width{
        width: 75%;
    }
    .bg-custom{
        background-color: #12b488;
    }
</style>