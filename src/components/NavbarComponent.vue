
<template>
    <nav class="bg-gray-900 text-white py-4 px-8 flex justify-between items-center fixed top-0 w-full">
        <h1 class="text-lg font-bold">Portfólio</h1>
        <ul class="flex gap-6">
            <li>
                <router-link to="/" class="hover:underline">Início</router-link>
            </li>
            <li>
                <router-link to="/about" class="hover:underline">Sobre</router-link>
            </li>
            <li>
                <router-link to="/career" class="hover:underline">Carreira</router-link>
            </li>
            <li>
                <router-link to="/project" class="hover:underline">Projetos</router-link>
            </li>
            <li>
                <router-link to="/contact" class="hover:underline">Contato</router-link>
            </li>

        </ul>
    </nav>
</template>
