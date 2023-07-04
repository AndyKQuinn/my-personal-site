<script lang="ts" setup></script>

<template>
    <section>
        <div class="grid pt-12 sm:pt-0 mx-auto lg:grid-cols-12">
            <div class="mr-auto place-self-center lg:col-span-7">
                <h1
                    class="sm:mt-6 max-w-2xl mb-4 ml-6 text-5xl font-extrabold tracking-tight leading-none md:text-5xl xl:text-6xl dark:text-white"
                >
                    Andy K Quinn
                </h1>
                <p
                    class="max-w-2xl mb-6 ml-6 font-light text-gray-500 lg:mb-8 md:text-lg lg:text-xl dark:text-gray-200"
                >
                    Full-stack developer and CICD enthusiast. I make cool things
                    using Golang, JavaScript, Python and whatever else sounds
                    fun to learn.
                </p>
                <NuxtLink
                    to="/portfolio"
                    class="inline-flex items-center justify-center px-5 py-3 mr-3 ml-10 text-base font-medium text-center text-white rounded-lg bg-purple-700 dark:hover:bg-gray-200 dark:hover:text-black focus:ring-4 focus:ring-blue-300 dark:focus:ring-blue-900"
                >
                    My Portfolio
                </NuxtLink>
                <NuxtLink
                    href="#family"
                    class="inline-flex items-center justify-center px-5 py-3 text-base font-medium text-center text-gray-900 border border-gray-300 rounded-lg hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 dark:text-white dark:border-gray-700 dark:hover:bg-gray-200 dark:hover:text-black dark:focus:ring-gray-800"
                >
                    My family
                </NuxtLink>
            </div>
            <div class="hidden lg:mt-0 lg:col-span-5 lg:flex">
                <img src="/images/hackathon-smile.png" alt="andy-image" />
            </div>
        </div>
    </section>
</template>

<style scoped></style>
