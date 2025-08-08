


 <title>Sua Loja de Roupas</title>
    <!-- Inclui o CDN do Tailwind CSS para estilização rápida e responsiva -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
        }
        /* Efeito de hover personalizado para os botões */
        .btn-primary:hover {
            background-color: #3b82f6;
            transform: scale(1.05);
            transition: all 0.3s ease;
        }
        .btn-secondary:hover {
            background-color: #f3f4f6;
            color: #1f2937;
            transform: scale(1.05);
            transition: all 0.3s ease;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header da Página -->
    <header class="bg-white shadow-md p-4 sticky top-0 z-50">
        <nav class="container mx-auto flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-gray-900">Sua Marca</a>
            <div class="hidden md:flex space-x-6 font-medium">
                <a href="#" class="text-gray-600 hover:text-blue-500 transition-colors duration-300">Novidades</a>
                <a href="#" class="text-gray-600 hover:text-blue-500 transition-colors duration-300">Produtos</a>
                <a href="#" class="text-gray-600 hover:text-blue-500 transition-colors duration-300">Sobre Nós</a>
                <a href="#" class="text-gray-600 hover:text-blue-500 transition-colors duration-300">Contato</a>
            </div>
            <div class="flex items-center space-x-4">
                <!-- Ícones de carrinho e usuário (usando emojis para simplicidade) -->
                <a href="#" class="text-2xl text-gray-600 hover:text-blue-500 transition-colors duration-300">🛒</a>
                <a href="#" class="text-2xl text-gray-600 hover:text-blue-500 transition-colors duration-300">👤</a>
            </div>
        </nav>
    </header>

    <!-- Seção de Destaque (Hero) -->
    <section class="bg-blue-500 text-white py-20 px-4 md:px-0">
        <div class="container mx-auto flex flex-col md:flex-row items-center justify-between">
            <div class="md:w-1/2 text-center md:text-left mb-8 md:mb-0">
                <h1 class="text-4xl md:text-6xl font-bold leading-tight">Estilo que Combina com Você</h1>
                <p class="mt-4 text-xl md:text-2xl">Descubra as últimas tendências da moda com a nossa nova coleção.</p>
                <button class="mt-8 bg-white text-blue-500 font-bold py-3 px-8 rounded-full shadow-lg hover:bg-gray-100 transition duration-300">
                    Comprar Agora
                </button>
            </div>
            <!-- Imagem de destaque, use uma URL real aqui -->
            <div class="md:w-1/2 flex justify-center">
                <img src="https://placehold.co/500x500/E0E7FF/3b82f6?text=Nova+Coleção" alt="Imagem da nova coleção de roupas" class="rounded-lg shadow-xl">
            </div>
        </div>
    </section>

    <!-- Seção de Produtos -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-10">Nossos Produtos em Destaque</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Produto 1 -->
                <div class="bg-gray-100 rounded-lg shadow-md overflow-hidden">
                    <img src="https://placehold.co/400x500/E5E7EB/4B5563?text=Camiseta+Básica" alt="Camiseta Básica" class="w-full h-64 object-cover">
                    <div class="p-5 text-center">
                        <h3 class="text-xl font-semibold text-gray-900">Camiseta Básica</h3>
                        <p class="text-gray-600 mt-2">Um item essencial para qualquer guarda-roupa.</p>
                        <p class="text-2xl font-bold text-blue-500 mt-4">R$ 59,90</p>
                        <button class="mt-4 w-full bg-blue-500 text-white py-2 rounded-full font-semibold hover:bg-blue-600 transition duration-300">Adicionar ao Carrinho</button>
                    </div>
                </div>
                <!-- Produto 2 -->
                <div class="bg-gray-100 rounded-lg shadow-md overflow-hidden">
                    <img src="https://placehold.co/400x500/E5E7EB/4B5563?text=Calça+Jeans" alt="Calça Jeans Slim Fit" class="w-full h-64 object-cover">
                    <div class="p-5 text-center">
                        <h3 class="text-xl font-semibold text-gray-900">Calça Jeans Slim Fit</h3>
                        <p class="text-gray-600 mt-2">Conforto e estilo em uma única peça.</p>
                        <p class="text-2xl font-bold text-blue-500 mt-4">R$ 149,90</p>
                        <button class="mt-4 w-full bg-blue-500 text-white py-2 rounded-full font-semibold hover:bg-blue-600 transition duration-300">Adicionar ao Carrinho</button>
                    </div>
                </div>
                <!-- Produto 3 -->
                <div class="bg-gray-100 rounded-lg shadow-md overflow-hidden">
                    <img src="https://placehold.co/400x500/E5E7EB/4B5563?text=Jaqueta+de+Couro" alt="Jaqueta de Couro" class="w-full h-64 object-cover">
                    <div class="p-5 text-center">
                        <h3 class="text-xl font-semibold text-gray-900">Jaqueta de Couro</h3>
                        <p class="text-gray-600 mt-2">Para um visual ousado e moderno.</p>
                        <p class="text-2xl font-bold text-blue-500 mt-4">R$ 299,90</p>
                        <button class="mt-4 w-full bg-blue-500 text-white py-2 rounded-full font-semibold hover:bg-blue-600 transition duration-300">Adicionar ao Carrinho</button>
                    </div>
                </div>
                <!-- Produto 4 -->
                <div class="bg-gray-100 rounded-lg shadow-md overflow-hidden">
                    <img src="https://placehold.co/400x500/E5E7EB/4B5563?text=Vestido+Florido" alt="Vestido Florido" class="w-full h-64 object-cover">
                    <div class="p-5 text-center">
                        <h3 class="text-xl font-semibold text-gray-900">Vestido Florido</h3>
                        <p class="text-gray-600 mt-2">A leveza e a beleza da primavera.</p>
                        <p class="text-2xl font-bold text-blue-500 mt-4">R$ 119,90</p>
                        <button class="mt-4 w-full bg-blue-500 text-white py-2 rounded-full font-semibold hover:bg-blue-600 transition duration-300">Adicionar ao Carrinho</button>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Seção de Depoimentos -->
    <section class="bg-blue-500 text-white py-16">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-10">O que nossos clientes dizem</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Depoimento 1 -->
                <div class="bg-blue-600 p-6 rounded-lg shadow-lg">
                    <p class="text-lg italic">"A qualidade das roupas é incrível e o atendimento foi impecável. Recomendo a todos!"</p>
                    <p class="font-semibold text-right mt-4">- Maria S.</p>
                </div>
                <!-- Depoimento 2 -->
                <div class="bg-blue-600 p-6 rounded-lg shadow-lg">
                    <p class="text-lg italic">"Encontrei exatamente o que procurava. O site é fácil de navegar e a entrega foi super rápida."</p>
                    <p class="font-semibold text-right mt-4">- João P.</p>
                </div>
                <!-- Depoimento 3 -->
                <div class="bg-blue-600 p-6 rounded-lg shadow-lg">
                    <p class="text-lg italic">"Os designs são únicos e modernos. Minha nova loja de roupas favorita!"</p>
                    <p class="font-semibold text-right mt-4">- Ana C.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Rodapé da Página -->
    <footer class="bg-gray-900 text-gray-300 py-10">
        <div class="container mx-auto px-4 text-center">
            <div class="mb-4">
                <p>&copy; 2024 Sua Marca. Todos os direitos reservados.</p>
            </div>
            <div class="flex justify-center space-x-6 text-2xl">
                <!-- Links para redes sociais -->
                <a href="#" class="hover:text-blue-400 transition-colors duration-300">📘</a>
                <a href="#" class="hover:text-blue-400 transition-colors duration-300">📸</a>
                <a href="#" class="hover:text-blue-400 transition-colors duration-300">🐦</a>
            </div>
        </div>
    </footer>

</body>
</html>
