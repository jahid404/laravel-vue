<template>
    <div class="flex flex-col items-center justify-center h-screen">
        <h1 class="text-3xl font-bold">Home Page</h1>

        <div class="flex justify-center items-center gap-4 mt-5">
            <router-link to="/about" class="btn btn-primary"
                >About
            </router-link>
            <router-link to="/contact" class="btn btn-primary"
                >Contact
            </router-link>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Home',
    };
</script>
