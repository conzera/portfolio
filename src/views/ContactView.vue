
<template>
    <div class="contact pt-24 text-white max-w-3xl mx-auto">
        <h1 class="text-3xl font-bold mb-4">Contato:</h1>
        <form class="space-y-4">
            <input type="text" placeholder="Seu nome..." class="bg-gray-800 w-full p-1 rounded text-white" />
            <input type="email" placeholder="Seu e-mail..." class="bg-gray-800 w-full p-1 rounded text-white" />
            <textarea placeholder="Sua mensagem..." class="bg-gray-800 w-full p-1 rounded text-white"></textarea>
            <div class="flex justify-end">
                <button class="bg-blue-600 px-3 py-1 rounded hover:bg-blue-700">Enviar</button>
            </div>
        </form>

        <div class="mt-10 pb-24">
            <p><strong>Desenvolvedor:</strong> Matheus Conzi</p>
            <p><strong>E-mail:</strong> matheusconzi@hotmail.com</p>
            <p><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/matheusconzi"
                target="_blank" class="text-blue-400 underline">/matheusconzi</a></p>
        </div>
    </div>
</template>
