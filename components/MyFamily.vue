<script lang="ts" setup></script>

<template>
    <section id="family" class="flex flex-col">
        <div>
            <p class="text-4xl text-white flex justify-center mb-4 p-4">
                My Family
            </p>
        </div>
        <div class="flex flex-col place-self-center my-10 mx-4 sm:mx-0">
            <img
                src="/images/andy-rachel-mom.png"
                class="max-h-96 rounded-2xl"
            />
            <p class="flex p-2 text-white text-2xl justify-center">
                My wife and mom
            </p>
        </div>
        <div
            class="grid grid-cols-1 lg:grid-cols-3 gap-16 mx-16 items-center place-content-evenly"
        >
            <div class="flex flex-col justify-center">
                <img src="/images/dibbles.png" class="max-h-96 rounded-2xl" />
                <p class="flex p-2 text-white text-2xl justify-center">
                    Dee Dee "The Dibbles"
                </p>
            </div>
            <div class="flex flex-col justify-center">
                <img src="/images/puffcatty.png" class="max-h-96 rounded-2xl" />
                <p class="flex p-2 text-white text-2xl justify-center">
                    Puff Catty or "P Kitty"
                </p>
            </div>
            <div class="flex flex-col justify-center">
                <img src="/images/meowmeow.png" class="max-h-96 rounded-2xl" />
                <p class="flex p-2 text-white text-2xl justify-center">
                    Moo Moo
                </p>
            </div>
        </div>
    </section>
</template>

<style scoped></style>
