<template>
    <div>
        <nav class="p-6 flex items-center justify-between bg-teal-800">
            <NuxtLink to="/" class="text-xl text-white">Djob</NuxtLink>

            <div class="flex items-center space-x-4">
                <NuxtLink to="/" class="text-white hover:text-teal-300">Home</NuxtLink>
                <NuxtLink to="/browse" class="text-white hover:text-teal-300">Browse</NuxtLink>
            </div>
        </nav>

        <slot />

        <footer class="flex flex-wrap justify-between items-center p-6 bg-gray-900">
            <p class="text-gray-300">Copyright (c) 2023 - Djob</p>

            <div class="flex mt-6 md:mt-0 items-center space-x-4">
                <NuxtLink to="/login" class="py-4 px-6 bg-teal-900 hover:bg-teal-700 text-white rounded-xl">
                    Login
                </NuxtLink>
                <NuxtLink to="/signup" class="py-4 px-6 bg-teal-600 hover:bg-teal-700 text-white rounded-xl">
                    Sign Up
                </NuxtLink>
            </div>
        </footer>
    </div>
</template>