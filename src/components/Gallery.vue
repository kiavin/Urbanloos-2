<script setup>
</script>
<template>
    <div class="bg-white dark:bg-gray-800 h-full py-6 sm:py-8 lg:py-12">
        <div class="flex flex-col items-center gap-4">
            <h2 class="text-2xl font-bold text-gray-800 lg:text-3xl dark:text-white">Gallery</h2>

            <p class="max-w-screen-sm text-gray-500 dark:text-gray-300 text-center md:block">
                This is a section of some simple filler text, also known as placeholder text. It shares some
                characteristics of real written text.
            </p>
        </div>

        <div class="mx-auto max-w-screen-2xl px-4 md:px-8">
            <div class="mb-4 flex items-center justify-between gap-8 sm:mb-8 md:mb-12">
                <RouterLink to="/gallery"
                    class="inline-block rounded-lg border bg-white dark:bg-gray-700 dark:border-none px-4 py-2 text-center text-sm font-semibold text-gray-500 dark:text-gray-200 outline-none ring-indigo-300 transition duration-100 hover:bg-gray-100 focus-visible:ring active:bg-gray-200 md:px-8 md:py-3 md:text-base">
                    More
                </RouterLink>
            </div>

            <div class="grid grid-cols-2 gap-4 sm:grid-cols-3 md:gap-6 xl:gap-8">
                <!-- image - start -->
                <a href="#"
                    class="group relative flex h-48 items-end overflow-hidden rounded-lg bg-gray-100 shadow-lg md:h-80">
                    <img src="https://www.andyloos.co.uk/img/range/standard01.jpg"
                        loading="lazy" alt="Photo by Minh Pham"
                        class="absolute inset-0 h-full w-full object-cover object-center transition duration-200 group-hover:scale-110" />

                    <div
                        class="pointer-events-none absolute inset-0 bg-gradient-to-t from-gray-800 via-transparent to-transparent opacity-50">
                    </div>

                    <span class="relative ml-4 mb-3 inline-block text-sm text-white md:ml-5 md:text-lg">VR</span>
                </a>
                <!-- image - end -->

                <!-- image - start -->
                <a href="#"
                    class="group relative flex h-48 items-end overflow-hidden rounded-lg bg-gray-100 shadow-lg md:col-span-2 md:h-80">
                    <img src="https://www.andyloos.co.uk/img/luxury02.jpg"
                        loading="lazy" alt="Photo by Magicle"
                        class="absolute inset-0 h-full w-full object-cover object-center transition duration-200 group-hover:scale-110" />

                    <div
                        class="pointer-events-none absolute inset-0 bg-gradient-to-t from-gray-800 via-transparent to-transparent opacity-50">
                    </div>

                    <span class="relative ml-4 mb-3 inline-block text-sm text-white md:ml-5 md:text-lg">Tech</span>
                </a>
                <!-- image - end -->

                <!-- image - start -->
                <a href="#"
                    class="group relative flex h-48 items-end overflow-hidden rounded-lg bg-gray-100 shadow-lg md:col-span-2 md:h-80">
                    <img src="https://www.urbanloos.com/assets/images/standard1.jpg"
                        loading="lazy" alt="Photo by Martin Sanchez"
                        class="absolute inset-0 h-full w-full object-cover object-center transition duration-200 group-hover:scale-110" />

                    <div
                        class="pointer-events-none absolute inset-0 bg-gradient-to-t from-gray-800 via-transparent to-transparent opacity-50">
                    </div>

                    <span class="relative ml-4 mb-3 inline-block text-sm text-white md:ml-5 md:text-lg">Dev</span>
                </a>
                <!-- image - end -->

                <!-- image - start -->
                <a href="#"
                    class="group relative flex h-48 items-end overflow-hidden rounded-lg bg-gray-100 shadow-lg md:h-80">
                    <img src="https://www.andyloos.co.uk/img/range/shower-steps.jpg"
                        loading="lazy" alt="Photo by Lorenzo Herrera"
                        class="absolute inset-0 h-full w-full object-cover object-center transition duration-200 group-hover:scale-110" />

                    <div
                        class="pointer-events-none absolute inset-0 bg-gradient-to-t from-gray-800 via-transparent to-transparent opacity-50">
                    </div>

                    <span class="relative ml-4 mb-3 inline-block text-sm text-white md:ml-5 md:text-lg">Retro</span>
                </a>
                <!-- image - end -->
            </div>
        </div>
    </div>
</template>