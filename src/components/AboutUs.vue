<script setup>
</script>
<template>
    <section class="bg-gray-100 py-10">
        <div class="container mx-auto py-16 px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-2 items-center gap-8">
                <div class="max-w-lg">
                    <h2 class="text-3xl font-extrabold text-black sm:text-4xl">About Us</h2>
                    <p class="mt-4 text-gray-600 text-lg">UrbanLoos, your trusted provider of premium mobile toilet
                        rentals for events of all sizes across Nakuru, Kiambu, Narok, Nyandarua, and Laikipia counties.
                        With high hygiene standards, affordable rates, and a 100% delivery track record, we ensure
                        comfort and convenience for your guests. From standard options to VIP units with spacious
                        interiors, mirrors, and running water, each unit comes with an attendant to keep it spotless.
                        Eco-friendly and hassle-free, UrbanLoos is here to meet your needs with customizable packages
                        and reliable service</p>
                    <div class="mt-8">
                        <RouterLink to="/about" class="text-blue-500 hover:text-blue-600 font-medium">Learn more about
                            us
                            <span class="ml-2">&#8594;</span>
                        </RouterLink>
                    </div>
                </div>
                <div class="mt-12 md:mt-0">
                    <img src="https://www.urbanloos.com/assets/images/hero_area.jpg" alt="About Us Image"
                        class="object-cover rounded-lg shadow-md">
                </div>
            </div>
        </div>
    </section>
</template>