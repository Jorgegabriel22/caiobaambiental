<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Caioba Ambiental | Desentupidora no Litoral do Paraná</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-yellow-400">
    <script src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js" defer></script>

    <header class="bg-blue-500 text-white shadow-lg" x-data="{ open: false }">
        <div class="container mx-auto px-4 py-6 flex items-center justify-between">
            <div class="flex items-center space-x-4">
                <img src="IMGCAIOBA.png" alt="Logo" class="w-16">
                <div>
                    <h1 class="text-xl font-bold">CAIOBA AMBIENTAL</h1>
                    <p class="text-sm text-white/70">18 anos de experiência</p>
                </div>
            </div>

            <button class="md:hidden focus:outline-none" @click="open = !open">
                <i class="fas fa-bars text-2xl"></i>
            </button>

            <nav class="hidden md:flex space-x-4">
                <a href="#services" class="hover:text-yellow-300 transition">Nossos Serviços</a>
                <a href="#contact" class="hover:text-yellow-300 transition">Contato</a>
                <a href="https://wa.me/554199159904" class="hover:text-yellow-300 transition">WhatsApp</a>
            </nav>
        </div>

        <div x-show="open" class="md:hidden px-4 pb-4 space-y-2">
            <a href="#services" class="block py-2 border-b border-white/20">Nossos Serviços</a>
            <a href="#contact" class="block py-2 border-b border-white/20">Contato</a>
            <a href="https://wa.me/554199159904" class="block py-2">WhatsApp</a>
        </div>
    </header>


    <section class="relative bg-gradient-to-r from-white-600 to-white-500 text-white py-16 md:py-24 overflow-hidden">
        <div class="container mx-auto px-4 relative z-10">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h2 class="text-3xl md:text-4xl font-bold mb-4 text-black">Soluções Ambientais no Litoral do Paraná</h2>
                    <p class="text-lg mb-7 text-black">Há 18 anos oferecendo serviços de qualidade em Matinhos e região com profissionalismo e comprometimento.</p>
                    <div class="flex flex-col sm:flex-row space-y-3 sm:space-y-0 sm:space-x-4">
                        <a href="#services" class="bg-blue-300 hover:bg-white-100 text-black font-semibold px-6 py-3 rounded-full transition text-center shadow-lg hover:text-yellow-300 transition">
                            <i class="fas fa-concierge-bell mr-2"></i> Nossos Serviços
                        </a>
                        <a href="tel:+554199159904" class="bg-blue-300 hover:bg-white-100 text-black font-semibold px-6 py-3 rounded-full transition text-center shadow-lg hover:text-yellow-300 transition">
                            <i class="fas fa-phone-alt mr-2 "></i> Ligar Agora
                        </a>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center">
                </div>
            </div>
        </div>

        <div class="wave-bg">
            <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">

            </svg>
        </div>
    </section>

    <section id="services" class="py-16 bg-white-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-black-700 mb-2">Nossos Serviços</h2>
                <div class="w-20 h-1 bg-blue-300 mx-auto mb-4"></div>
                <p class="text-white-600 max-w-2xl mx-auto mb-5">Oferecemos soluções completas em serviços ambientais com equipamentos modernos e equipe especializada.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="service-card bg-white rounded-lg overflow-hidden shadow-md transition duration-300 transform hover:scale-105">
                    <div class="h-48 bg-center bg-cover bg-no-repeat" style="background-image: url('banheiro2.jpeg');"> </div>
                    <div class="p-6 bg-white">
                        <h3 class="text-xl font-bold text-blue-700 mb-2">Locação de Banheiros Químicos</h3>
                        <p class="text-gray-600 mb-4"> Banheiros químicos para eventos, obras e situações temporárias. Higiene e comodidade garantida. </p>
                        <a href="tel:+554199159904" class="text-blue-500 font-semibold hover:text-yellow-600 transition flex items-center"> Solicitar orçamento
                            <i class="fas fa-arrow-right ml-2"></i>
                        </a>
                    </div>
                </div>

                <div class="service-card bg-white rounded-lg overflow-hidden shadow-md transition duration-300 transform hover:scale-105">
                    <div class="h-48 bg-center bg-cover bg-no-repeat" style="background-image: url('fossa.jpeg');"> </div>
                        
                    
                    <div class="p-6 bg-white">
                        <h3 class="text-xl font-bold text-blue-700 mb-2">Limpeza de Fossa</h3>
                        <p class="text-gray-600 mb-4">Serviço especializado em limpeza e desentupimento de fossas sépticas e sumidouros.</p>
                        <a href="tel:+554199159904" class="text-blue-500 font-semibold hover:text-yellow-600 transition flex items-center">
                            Solicitar orçamento
                            <i class="fas fa-arrow-right ml-2"></i>
                        </a>
                    </div>
                </div>

                <div class="service-card bg-white rounded-lg overflow-hidden shadow-md transition duration-300 transform hover:scale-105">
                    <div class="service-card bg-white rounded-lg overflow-hidden shadow-md transition duration-300 transform hover:scale-105">
                    <div class="h-48 bg-center bg-cover bg-no-repeat" style="background-image: url('gordura.jpeg');"> </div>
                    </div>
                    <div class="p-6 bg-white">
                        <h3 class="text-xl font-bold text-blue-700 mb-2">Limpeza de Caixa de Gordura</h3>
                        <p class="text-gray-600 mb-4">Remoção e limpeza profissional de caixas de gordura para restaurantes e residências.</p>
                        <a href="tel:+554199159904" class="text-blue-500 font-semibold hover:text-yellow-600 transition flex items-center">
                            Solicitar orçamento
                            <i class="fas fa-arrow-right ml-2"></i>
                        </a>
                    </div>
                </div>

                <div class="service-card bg-white rounded-lg overflow-hidden shadow-md transition duration-300 transform hover:scale-105">
                    <div class="service-card bg-white rounded-lg overflow-hidden shadow-md transition duration-300 transform hover:scale-105">
                    <div class="h-48 bg-center bg-cover bg-no-repeat" style="background-image: url('image1.jpeg');"> </div>
                    </div>
                    <div class="p-6 bg-white">
                        <h3 class="text-xl font-bold text-blue-700 mb-2">Hidrojateamento</h3>
                        <p class="text-gray-600 mb-4">Limpeza de tubulações e redes de esgoto com tecnologia de alta pressão.</p>
                        <a href="tel:+554199159904" class="text-blue-500 font-semibold hover:text-yellow-600 transition flex items-center">
                            Solicitar orçamento
                            <i class="fas fa-arrow-right ml-2"></i>
                        </a>
                    </div>
                </div>

                <div class="service-card bg-white rounded-lg overflow-hidden shadow-md transition duration-300 transform hover:scale-105">
                    <div class="service-card bg-white rounded-lg overflow-hidden shadow-md transition duration-300 transform hover:scale-105">
                    <div class="h-48 bg-center bg-cover bg-no-repeat" style="background-image: url('desentupimento.webp');"> </div>
                    </div>
                    <div class="p-6 bg-white">
                        <h3 class="text-xl font-bold text-blue-700 mb-2">Desentupimentos</h3>
                        <p class="text-gray-600 mb-4">Resolução de entupimentos em pias, vasos sanitários, ralos e toda rede de esgoto.</p>
                        <a href="tel:+554199159904" class="text-blue-500 font-semibold hover:text-yellow-600 transition flex items-center">
                            Solicitar orçamento
                            <i class="fas fa-arrow-right ml-2"></i>
                        </a>
                    </div>
                </div>

                <div class="service-card bg-white rounded-lg overflow-hidden shadow-md transition duration-300 transform hover:scale-105">
                    <div class="h-48 bg-center bg-cover bg-no-repeat" style="background-image: url('container..jpg.jpeg');">
                    </div>
                    <div class="p-6 bg-white">
                        <h3 class="text-xl font-bold text-blue-700 mb-2">Locação de Containers</h3>
                        <p class="text-gray-600 mb-4">
                            Containers práticos, seguros e ideais para sua obra, estoque ou escritório.
                            Entrega rápida e aluguel sob medida para sua necessidade.
                        </p>
                        <a href="tel:+554199159904" class="text-blue-500 font-semibold hover:text-yellow-600 transition flex items-center">
                            Solicitar orçamento
                            <i class="fas fa-arrow-right ml-2"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <div class="flex flex-col lg:flex-row items-center">
                <div class="lg:w-1/2 mb-10 lg:mb-0 lg:pr-10">
                    <div class="relative">
                        <img src="fotosite.jpg" alt="Equipe Caioba Ambiental" class="rounded-lg shadow-xl w-full">
                        <div class="absolute -bottom-5 -right-5 bg-blue-400 text-white p-4 rounded-lg shadow-lg">
                            <p class="text-2xl font-bold">18+</p>
                            <p class="text-sm">Anos de experiência</p>
                        </div>
                    </div>
                </div>
                <div class="lg:w-1/2">
                    <h2 class="text-3xl font-bold text-gray-700 mb-4">Sobre a Caioba Ambiental</h2>
                    <div class="w-20 h-1 bg-blue-700 mb-6"></div>
                    <p class="text-gray-700 mb-5">Há 18 anos atuando no mercado de serviços ambientais em Matinhos e região metropolitana do litoral do Paraná, a Caioba Ambiental se destaca pela qualidade e eficiência em seus serviços.</p>
                    <p class="text-gray-700 mb-6">Nossa equipe é composta por profissionais qualificados e equipamentos modernos para garantir a melhor solução para nossos clientes, sejam residenciais, comerciais ou industriais.</p>

                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-6 mb-8">
                        <div class="flex items-start">
                             </div>
                        <div class="flex items-start">
                            <div class="bg-blue-600 text-white p-2 rounded-full mr-3">
                                <i class="fas fa-check text-sm"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-blue-700 mb-1">Equipe Qualificada</h4>
                                <p class="text-gray-600 text-sm">Profissionais treinados e certificados.</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="bg-blue-600 text-white p-2 rounded-full mr-3">
                                <i class="fas fa-check text-sm"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-blue-700 mb-1">Equipamentos Modernos</h4>
                                <p class="text-gray-600 text-sm">Tecnologia de ponta para melhor eficiência.</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="bg-blue-600 text-white p-2 rounded-full mr-3">
                                <i class="fas fa-check text-sm"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-blue-700 mb-1">Licenciamento Ambiental</h4>
                                <p class="text-gray-700 text-sm">Todos os serviços com a documentação em dia.</p>
                            </div>
                        </div>
                    </div>

                    <div class="flex flex-col sm:flex-row space-y-3 sm:space-y-0 sm:space-x-4">
                        <a href="tel:+554199159904" class="bg-blue-600 hover:bg-blue-700 text-white font-semibold px-6 py-3 rounded-full transition text-center shadow hover:text-yellow-300 transition">
                            <i class="fas fa-phone-alt mr-2"></i> Ligar Agora
                        </a>
                        <a href="#contact" class="bg-blue-600 hover:bg-blue-700 border-blue-700 text-white font-semibold px-6 py-3 rounded-full transition text-center shadow hover:text-yellow-300 transition">
                            <i class="fas fa-envelope mr-2"></i> Fale Conosco
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                
            </div>
            </div>
    </section>

    <section id="mapa" class="py-16 bg-blue-600">
        <div class="container mx-auto px-4">
            <h2 class="text-2xl font-bold text-center mb-6 text-white">Nossa Localização</h2>
            <div class="w-full h-64 sm:h-80 md:h-96 rounded-lg overflow-hidden shadow-lg">
                <iframe
                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3592.9096921364567!2d-48.51867142378264!3d-25.773546277344458!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94dbec2b8248dc1d%3A0x74479b7cb02eb171!2sR.%204%2C%20203%2C%20Matinhos%20-%20PR%2C%2083260-000!5e0!3m2!1spt-BR!2sbr!4v1753476368682!5m2!1spt-BR!2sbr" 
                    width="100%"
                    height="100%"
                    style="border:0;"
                    allowfullscreen=""
                    loading="lazy"
                    referrerpolicy="no-referrer-when-downgrade"
                    class="w-full h-full">
                </iframe>
            </div>
        </div>
    </section>

    <section id="contact" class="py-16 bg-blue-600 text-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold mb-2">Entre em Contato</h2>
                <div class="w-20 h-1 bg-yellow-400 mx-auto mb-4"></div>
                <p class="max-w-2xl mx-auto">
                    Estamos prontos para atender sua necessidade com a qualidade que apenas 18 anos de experiência podem oferecer.
                </p>
            </div>

            <div class="flex flex-col lg:flex-row">
                <div class="lg:w-1/2 mb-10 lg:mb-0 lg:pr-10">
                    <form
                        id="form-contato"
                        action="https://formsubmit.co/jorgegabrielmmagalhaes@gmail.com"
                        method="POST"
                        onsubmit="enviarFormulario(event)"
                        class="bg-blue-300 rounded-lg shadow-xl p-6 text-gray-800"
                    >
                        <div class="mb-4">
                            <label for="name" class="block text-gray-700 font-semibold mb-2">Nome</label>
                            <input name="nome" type="text" id="name" required class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500" />
                        </div>
                        <div class="mb-4">
                            <label for="phone" class="block text-gray-700 font-semibold mb-2">Telefone</label>
                            <input name="telefone" type="tel" id="phone" required class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500" />
                        </div>
                        <div class="mb-4">
                            <label for="service" class="block text-gray-700 font-semibold mb-2">Serviço Desejado</label>
                            <select name="serviço" id="service" required class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                                <option value="">Selecione um serviço</option>
                                <option value="banheiros">Banheiros Químicos</option>
                                <option value="fossa">Limpeza de Fossa</option>
                                <option value="gordura">Limpeza de Caixa de Gordura</option>
                                <option value="hidrojateamento">Hidrojateamento</option>
                                <option value="desentupimento">Desentupimento</option>
                                <option value="containers">Containers</option>
                            </select>
                        </div>
                        <div class="mb-6">
                            <label for="message" class="block text-gray-700 font-semibold mb-2">Mensagem</label>
                            <textarea name="mensagem" id="message" rows="4" required class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500"></textarea>
                        </div>

                        <input type="hidden" name="_captcha" value="false" />
                        <input type="hidden" name="_subject" value="Nova mensagem do site Caioba Ambiental" />
                        <input type="hidden" name="_next" value="http://127.0.0.1:5500/caioba.html">
                        <button type="submit" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-semibold py-3 px-4 rounded-lg transition shadow">
                            Enviar Mensagem
                        </button>

                    </form>
                </div>

                <div class="lg:w-1/2">
                    <div class="bg-blue-300 rounded-lg shadow-xl p-6 h-full">
                        <h3 class="text-2xl font-bold mb-6 text-blue-800">Informações de Contato</h3>

                        <div class="space-y-6">
                            <div class="flex items-start">
                                <div class="bg-blue-600 text-white p-3 rounded-full mr-4">
                                    <i class="fas fa-phone-alt"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold mb-1">Telefone</h4>
                                    <p class="text-gray-100">
                                        <a href="tel:+554199159904" class="hover:text-white transition">(41) 9915-9904</a>
                                    </p>
                                </div>
                            </div>

                            <div class="flex items-start">
                                <div class="bg-blue-600 text-white p-3 rounded-full mr-4">
                                    <i class="fas fa-envelope"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold mb-1">E-mail</h4>
                                    <p class="text-gray-100">
                                        <a href="mailto:jorgegabrielmmagalhaes@gmail.com" class="hover:text-white transition">jorgegabrielmmagalhaes@gmail.com</a>
                                    </p>
                                </div>
                            </div>

                            <div class="flex items-start">
                                <div class="bg-blue-600 text-white p-3 rounded-full mr-4">
                                    <i class="fas fa-clock"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold mb-1">Horário de Atendimento</h4>
                                    <p class="text-gray-100">Segunda a Sexta: 8h às 18h</p>

                                </div>
                            </div>
                        </div>

                        <div class="mt-10">
                            <h4 class="font-bold mb-2 text-white">Siga-nos</h4>
                            <div class="flex space-x-4">
                                <a href="https://www.facebook.com/share/16M3EfDNd6/" class="bg-blue-600 hover:bg-blue-800 text-white p-3 rounded-full transition hover:text-yellow-300 transition">
                                    <i class="fab fa-facebook-f"></i>
                                </a>
                                <a href="https://www.instagram.com/caiobaambiental?igsh=OXhuYm9sdWNkZDZ2" class="bg-blue-600 hover:bg-blue-800 text-white p-3 rounded-full transition hover:text-yellow-300 transition">
                                    <i class="fab fa-instagram"></i>
                                </a>
                                <a href="https://wa.me/message/2BCTETMDSEXDD1" class="bg-blue-600 hover:bg-blue-800 text-white p-3 rounded-full transition hover:text-yellow-300 transition">
                                    <i class="fab fa-whatsapp"></i>
                                </a>

                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-blue-900 text-white py-8">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-6 md:mb-0 flex items-center">
                    <img src="IMGCAIOBA.png" width="100" alt="Logo Caioba Ambiental">
                    <h2 class="text-xl font-bold ml-4">CAIOBA AMBIENTAL</h2>
                </div>
                <div class="text-center md:text-right">
                    <p class="text-white mb-2">© 2025 Caioba Ambiental. Todos os direitos reservados.</p>
                    <p class="text-white text-sm">Desenvolvido com <i class="fas fa-heart text-blue-400"></i> para a cidade de Matinhos</p>
                </div>
            </div>
        </div>
    </footer>

    <a href="https://wa.me/554199159904" class="fixed bottom-6 right-6 bg-green-500 hover:bg-green-600 text-white p-4 rounded-full shadow-xl transition transform hover:scale-110 z-50">
        <i class="fab fa-whatsapp text-2xl"></i>
    </a>

</body>
</html>
