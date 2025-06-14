<template>
    <div class="flex flex-col items-center justify-center h-screen">
        <h1 class="text-3xl font-bold">Home Page</h1>

    <div class="flex justify-center items-center gap-4">
        <router-link to="/about" class="bg-blue-400 text-white px-4 py-2 rounded-md">About</router-link>
            <router-link to="/contact" class="bg-blue-400 text-white px-4 py-2 rounded-md">Contact</router-link>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Home',
    };
</script>
