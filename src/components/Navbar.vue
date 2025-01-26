<script setup>
import { ref } from 'vue';
import { RouterLink } from 'vue-router'; // Import RouterLink

// Reactive state to control menu visibility
const isMenuOpen = ref(false);

// Toggle function to open/close the menu
function toggleMenu() {
    isMenuOpen.value = !isMenuOpen.value;
}

// Function to close the menu after clicking an item
function closeMenu() {
    isMenuOpen.value = false;
}
</script>

<template>
    <nav class="bg-white border-gray-200 dark:bg-gray-900">
        <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto py-2">
            <RouterLink to="/" class="flex items-center space-x-3 rtl:space-x-reverse">
                <img src="https://www.urbanloos.com/assets/images/urban-loos-favicon-color.png" class="h-12" alt="Logo" />
                <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white">urbanloos</span>
            </RouterLink>

            <!-- Menu Toggle Button for Small Devices -->
            <button type="button"
                class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
                aria-controls="navbar-default" aria-expanded="false" @click="toggleMenu">
                <span class="sr-only">Open main menu</span>
                <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none"
                    viewBox="0 0 17 14">
                    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M1 1h15M1 7h15M1 13h15" />
                </svg>
            </button>

            <!-- Navigation Links -->
            <div :class="{ 'hidden': !isMenuOpen, 'w-full md:block md:w-auto': true }" id="navbar-default">
                <ul
                    class="font-medium font-sans flex flex-col p-4 md:p-0 mt-4 border border-gray-100 rounded-lg bg-teal-400 md:flex-row md:space-x-2 rtl:space-x-reverse md:mt-0 md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700">
                    <li>
                        <RouterLink to="/" @click="closeMenu" class="block px-4 py-2 rounded " :class="{
                            'text-white bg-pink-400': $route.path === '/',
                            'text-gray-900 hover:bg-teal-400': $route.path !== '/'
                        }" aria-current="page">
                            Home
                        </RouterLink>
                    </li>
                    <li>
                        <RouterLink to="/about" @click="closeMenu" class="block px-4 py-2 rounded" :class="{
                            'text-white bg-pink-400': $route.path === '/about',
                            'text-gray-900 hover:bg-teal-400': $route.path !== '/about'
                        }">
                            About
                        </RouterLink>
                    </li>
                    <li>
                        <RouterLink to="/services" @click="closeMenu" class="block px-4 py-2 rounded" :class="{
                            'text-white bg-pink-400': $route.path === '/services',
                            'text-gray-900 hover:bg-teal-400': $route.path !== '/services'
                        }">
                            Services
                        </RouterLink>
                    </li>
                    <li>
                        <RouterLink to="/contact" @click="closeMenu" class="block px-4 py-2 rounded " :class="{
                            'text-white bg-pink-400': $route.path === '/contact',
                            'text-gray-900 hover:bg-teal-400': $route.path !== '/contact'
                        }">
                            Contact
                        </RouterLink>
                    </li>
                    <li>
                        <RouterLink to="/blog" @click="closeMenu" class="block px-4 py-2 rounded " :class="{
                            'text-white bg-pink-400': $route.path === '/blog',
                            'text-gray-900 hover:bg-teal-400': $route.path !== '/blog'
                        }">
                            Blog
                        </RouterLink>
                    </li>
                    <li>
                        <RouterLink to="/faq" @click="closeMenu" class="block px-4 py-2 rounded " :class="{
                            'text-white bg-pink-400': $route.path === '/faq',
                            'text-gray-900 hover:bg-teal-400': $route.path !== '/faq'
                        }">
                            FAQS
                        </RouterLink>
                    </li>
                    <li>
                        <RouterLink to="/serviceAreas" @click="closeMenu" class="block px-4 py-2 rounded " :class="{
                            'text-white bg-pink-400': $route.path === '/serviceAreas',
                            'text-gray-900 hover:bg-teal-400': $route.path !== '/serviceAreas'
                        }">
                            Service Areas
                        </RouterLink>
                    </li>
                </ul>
            </div>



        </div>
    </nav>
</template>
