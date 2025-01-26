<script setup>
</script>
<template>
    <section>
        <div class=" max-w-full px-4 py-10 sm:px-6 sm:py-12 lg:px-8">
            <div class="grid grid-cols-1 gap-4 lg:grid-cols-3 lg:items-stretch">
                <div class="grid place-content-center rounded bg-gray-100 p-6 sm:p-8">
                    <div class="mx-auto max-w-md text-center lg:text-left">
                        <header>
                            <h2 class="text-xl font-bold text-gray-900 sm:text-3xl">Our Range</h2>

                            <p class="mt-4 text-gray-500">
                                choose what suits your event from our range
                            </p>
                        </header>

                        <RouterLink to="/services"
                            class="mt-8 inline-block rounded border border-teal-300 bg-teal-600 px-12 py-3 text-sm font-medium text-white transition hover:shadow focus:outline-none focus:ring">
                            View All
                        </RouterLink>
                    </div>
                </div>

                <div class="lg:col-span-2 lg:py-8">
                    <ul class="grid grid-cols-2 gap-4">
                        <li>
                            <a href="#"
                                class="group block border rounded-lg shadow-lg overflow-hidden hover:shadow-xl transition-shadow">
                                <!-- Image Section -->
                                <div class="relative">
                                    <img src="https://www.urbanloos.com/assets/images/standard1.jpg" alt=""
                                        class="aspect-square w-full object-cover" />
                                </div>

                                <!-- Text Section -->
                                <div class="p-5 bg-gray-100">
                                    <h3
                                        class="text-lg font-semibold text-pink-500 group-hover:underline group-hover:underline-offset-4">
                                        UrbanLoos Standard Unit
                                    </h3>
                                    <p class="mt-2 text-sm text-gray-700">
                                        The standard UrbanLoos unit features a compact handwash station, perfect for
                                        events where cleanliness is a priority. It includes a touch-free handwash
                                        station for a hygienic experience in high-traffic areas.
                                    </p>
                                </div>
                            </a>
                        </li>

                        <li>
                            <a href="#"
                                class="group block border rounded-lg shadow-lg overflow-hidden hover:shadow-xl transition-shadow">
                                <img src="https://www.ukloos.com/combo-unit/shower-toilet-trailer-combo-unit-intro.jpg"
                                    alt="" class="aspect-square w-full rounded object-cover" />

                                <div class=" p-5 bg-gray-100">
                                    <h3
                                        class="text-lg font-semibold text-pink-500 group-hover:underline group-hover:underline-offset-4">
                                        Urbanloos VIP unit
                                    </h3>

                                    <p class="mt-1 text-sm text-gray-700">The VIP UrbanLoos unit elevates event
                                        sanitation with spacious interiors and luxury amenities designed for guest
                                        comfort. Featuring large handwash sinks, ample lighting, and secure cabinets, it
                                        provides a superior experience that’s perfect for high-profile events. </p>
                                </div>
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
</template>