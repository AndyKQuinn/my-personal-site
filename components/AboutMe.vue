<script lang="ts" setup></script>

<template>
    <section class="">
        <p class="flex justify-center text-4xl pt-6 text-white">About Andy</p>
        <div
            class="flex grid sm:grid-cols-1 md:grid-cols-3 gap-12 md:gap-24 p-8 mt-2"
        >
            <div class="h-96 rounded-2xl shadow-2xl bg-purple-600 m-4">
                <img
                    src="/images/cat-guy-gazing-to-right.png"
                    alt="card-image"
                    class="h-1/2 w-full"
                />
                <p
                    class="flex text-white text-2xl justify-center font-mono p-2"
                >
                    Cat lover
                </p>
                <p
                    class="text-white flex justify-center items-center text-center text-sm"
                >
                    Cats! I love them! How many is too many? Who knows? Who
                    cares? Give me cats!
                </p>
            </div>
            <div class="h-96 rounded-2xl shadow-2xl bg-purple-600 m-4">
                <img
                    class="h-1/2 w-full"
                    src="/images/possum-tinkerer.png"
                    alt="card-image"
                />
                <p
                    class="flex text-white text-2xl justify-center font-mono p-2"
                >
                    Tinkerer
                </p>
                <p
                    class="text-white flex justify-center items-center text-center text-sm p-1"
                >
                    I can code in any language as long as you are willing to
                    give me at least 5x longer than a zoomer to make me build
                    your thing. I may be slow, but I'll sure get `er done!
                </p>
            </div>
            <div class="h-96 rounded-2xl shadow-2xl bg-purple-600 m-4">
                <img
                    src="/images/sloth-gamer.png"
                    alt="card-image"
                    class="h-1/2 w-full"
                />
                <div class="mx-2">
                    <p
                        class="flex text-white text-2xl justify-center font-mono p-2"
                    >
                        Gamer
                    </p>
                    <p
                        class="text-white flex justify-center items-center text-center text-sm p-1"
                    >
                        Recently coined the "Meat Grinder", I will probably
                        wreck you at most any video game. Unless your name is
                        Ian and want to play Rocket League...
                    </p>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped></style>
