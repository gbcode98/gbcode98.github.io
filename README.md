<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://unpkg.com/aos@2.3.1/dist/aos.css">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/particles.js"></script>
    <style>
        body {
            background-color: #0a0a0a;
            color: #ffffff;
            scroll-behavior: smooth;
            position: relative;
        }
        #particles-js {
            position: fixed;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            z-index: -1;
        }
    </style>
</head>
<body class="font-sans" onload="AOS.init();">
    <div id="particles-js"></div>
    <header class="p-5 flex justify-between items-center bg-black text-white shadow-md">
        <h1 class="text-2xl font-bold">Meu Portfólio</h1>
        <nav>
            <ul class="flex space-x-5">
                <li><a href="#sobre" class="hover:text-purple-500">Sobre</a></li>
                <li><a href="#habilidades" class="hover:text-purple-500">Habilidades</a></li>
                <li><a href="#escolaridade" class="hover:text-purple-500">Escolaridade</a></li>
                <li><a href="#projetos" class="hover:text-purple-500">Projetos</a></li>
                <li><a href="#contato" class="hover:text-purple-500">Contato</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="sobre" class="p-10 text-center" data-aos="fade-up">
        <h2 class="text-3xl font-bold text-purple-500">Sobre Mim</h2>
        <p class="mt-3">Breve descrição sobre você...</p>
    </section>
    
    <section id="habilidades" class="p-10 text-center" data-aos="fade-up" data-aos-delay="200">
        <h2 class="text-3xl font-bold text-purple-500">Habilidades</h2>
        <p class="mt-3">Lista de habilidades...</p>
    </section>
    
    <section id="escolaridade" class="p-10 text-center" data-aos="fade-up" data-aos-delay="400">
        <h2 class="text-3xl font-bold text-purple-500">Escolaridade</h2>
        <p class="mt-3">Detalhes da sua formação...</p>
    </section>
    
    <section id="projetos" class="p-10 text-center" data-aos="fade-up" data-aos-delay="600">
        <h2 class="text-3xl font-bold text-purple-500">Projetos</h2>
        <p class="mt-3">Lista dos seus projetos...</p>
    </section>
    
    <section id="contato" class="p-10 text-center" data-aos="fade-up" data-aos-delay="800">
        <h2 class="text-3xl font-bold text-purple-500">Contato</h2>
        <p class="mt-3">Seus meios de contato...</p>
    </section>
    
    <footer class="p-5 text-center bg-black text-white mt-10">
        <p>&copy; 2025 Meu Portfólio. Todos os direitos reservados.</p>
    </footer>
    
    <script>
        AOS.init();
        particlesJS("particles-js", {
            particles: {
                number: { value: 100 },
                color: { value: "#800080" },
                shape: { type: "circle" },
                opacity: { value: 0.5, random: true },
                size: { value: 3, random: true },
                move: { speed: 2, direction: "none", random: true }
            },
            interactivity: {
                events: {
                    onhover: { enable: true, mode: "repulse" }
                }
            }
        });
    </script>
</body>
</html>
