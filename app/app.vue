<script setup>
console.log("Hallo Vercel");

const counter = ref(0);
</script>

<template>
    <div class="">
        <button @click="counter++">Increment</button>
        <p>{{ counter }}</p>
    </div>
</template>
