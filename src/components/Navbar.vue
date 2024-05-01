<template>
    <div class="sticky top-0 z-10 w-full h-12 p-2 border border-gray-400 border-opacity-25">
        <div class="flex items-center justify-between">
            <div class="text-lg font-bold">Boilerplate</div>
            <div class="flex space-x-4">
                <router-link to="/" class="hover:text-blue-500">Home</router-link>
                <router-link to="/about" class="hover:text-blue-500">About</router-link>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'Navbar'
}
</script>