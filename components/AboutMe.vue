<script lang="ts" setup></script>

<template>
    <section class="">
        <Divider />
        <p class="flex justify-center text-4xl p-6 sm:my-6 text-white">
            About Andy Quinn
        </p>
        <ClientOnly>
        <p className="bg-slate-900 text-white text-2xl text-center p-6 mx-12 rounded-2xl">
            I'm a Windows and Unix Systems Engineer that accidentally fell in love
            with application development and systems automation. I'm married to
            my high school best friend and live in a house with my three
            fabulous cats.
            <div class="m-4" />
            I'm passionate about building software and helping
            others try to discover a passion for coding. I am a full-stack
            developer that writes apps using <span class="text-green-600">Golang</span>, <span class="text-purple-600">JavaScript</span> and <span class="text-red-600">Python</span>.
        </p>
        </ClientOnly>
        <Divider />
        <p class="flex justify-center text-4xl p-6 sm:mt-6 text-white">
            What I'm Like
        </p>
        <div
            class="flex grid sm:grid-cols-1 lg:grid-cols-3 gap-12 md:gap-24 p-8 mt-2"
        >
            <div class="h-96 rounded-2xl shadow-2xl bg-purple-600 m-4">

                <img
                    src="/images/cat-guy-gazing-to-right.png"
                    alt="card-image"
                    class="h-1/2 w-full"
                />
                <p
                    class="flex text-white text-2xl justify-center font-mono p-3"
                >
                    Cat lover
                </p>
                <p
                    class="text-white flex justify-center items-center text-center text-lg"
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
                    class="flex text-white text-2xl justify-center font-mono p-3"
                >
                    Tinkerer
                </p>
                <p
                    class="text-white flex justify-center items-center text-center text-lg lg:text-sm p-2"
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
                        class="flex text-white text-2xl justify-center font-mono p-3"
                    >
                        Gamer
                    </p>
                    <p
                        class="text-white flex justify-center items-center text-center text-lg lg:text-sm p-1"
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
