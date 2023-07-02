<script lang="ts" setup></script>

<template>
    <MyHeroSection />
    <section class="bg-gradient-to-bl from-slate-900 to-purple-600">
        <p class="flex justify-center text-4xl pt-6 text-white">About Andy</p>
        <div
            class="flex grid sm:grid-cols-1 md:grid-cols-3 gap-6 md-gap-0 p-8 mt-2"
        >
            <div class="h-96 bg-white rounded-2xl shadow-2xl bg-purple-600">
                <nuxt-img
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
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                    Minus ad natus eum ipsa, et eveniet cupiditate dolor vitae
                    nostrum. Nobis omnis quisquam quis ex cumque incidunt
                    voluptate ut esse placeat?
                </p>
            </div>
            <div class="h-96 bg-white rounded-2xl shadow-2xl bg-purple-600">
                <nuxt-img
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
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                    Minus ad natus eum ipsa, et eveniet cupiditate dolor vitae
                    nostrum. Nobis omnis quisquam quis ex cumque incidunt
                    voluptate ut esse placeat?
                </p>
            </div>
            <div class="h-96 bg-white rounded-2xl shadow-2xl bg-purple-600">
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
                        Lorem ipsum dolor sit amet consectetur, adipisicing
                        elit. Minus ad natus eum ipsa, et eveniet cupiditate
                        dolor vitae nostrum. Nobis omnis quisquam quis ex cumque
                        incidunt voluptate ut esse placeat?
                    </p>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped></style>
