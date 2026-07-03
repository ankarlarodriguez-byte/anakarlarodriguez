<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>📚 Espacio de Aprendizaje</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        principal: '#165DFF',
                        secundario: '#36CFC9',
                        claro: '#F7F8FA',
                        oscuro: '#1D2129'
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <style>
        html { scroll-behavior: smooth; }
    </style>
</head>
<body class="bg-claro text-oscuro font-sans">

    <!-- Menú fijo -->
    <nav class="fixed w-full top-0 z-50 bg-principal/95 text-white py-4 px-6 shadow-md backdrop-blur-sm">
        <div class="max-w-6xl mx-auto flex flex-col md:flex-row justify-between items-center gap-3">
            <a href="#inicio" class="font-bold text-xl flex items-center gap-2">
                <i class="fa fa-graduation-cap"></i> Mi Aprendizaje
            </a>
            <ul class="flex flex-wrap justify-center gap-6 font-medium">
                <li><a href="#inicio" class="hover:text-secundario transition-colors">Inicio</a></li>
                <li><a href="#asignaturas" class="hover:text-secundario transition-colors">Asignaturas</a></li>
            </ul>
        </div>
    </nav>

    <!-- Cabecera -->
    <header class="pt-28 pb-16 bg-gradient-to-br from-principal to-principal/80 text-white text-center">
        <div class="max-w-4xl mx-auto px-4">
            <h1 class="text-[clamp(2.2rem,5vw,3.5rem)] font-bold mb-3">Espacio de Aprendizaje</h1>
            <p class="text-lg md:text-xl opacity-95">Tu sitio organizado para consultar y estudiar cada materia</p>
        </div>
    </header>

    <!-- Página de Inicio -->
    <section id="inicio" class="max-w-6xl mx-auto px-4 py-16">
        <div class="bg-white rounded-xl shadow-lg p-6 md:p-10">
            <h2 class="text-[clamp(1.6rem,3vw,2.4rem)] font-bold text-principal mb-4 flex items-center gap-2">
                <i class="fa fa-home"></i> Bienvenido
            </h2>
            <p class="text-lg leading-relaxed">
                Aquí tendrás toda tu información de estudio en un solo lugar. En la sección de abajo encuentras la explicación sencilla de cada asignatura.
            </p>
            <div class="mt-6 p-4 bg-principal/5 rounded-lg border-l-4 border-principal">
                💡 Usa el menú de arriba para ir directo a la materia que buscas.
            </div>
        </div>
    </section>

    <!-- Asignaturas -->
    <section id="asignaturas" class="max-w-6xl mx-auto px-4 pb-20">
        <h2 class="text-[clamp(1.8rem,3vw,2.6rem)] font-bold text-center text-principal mb-10">📘 Asignaturas</h2>

        <div class="bg-white rounded-xl shadow-lg overflow-hidden mb-8 hover:shadow-xl transition-shadow">
            <img src="https://images.unsplash.com/photo-1635070041078-e363dbe005cb?w=800&q=80" alt="Matemática" class="w-full h-48 object-cover">
            <div class="p-6">
                <h3 class="text-2xl font-semibold text-principal mb-3"><i class="fa fa-calculator"></i> Matemática</h3>
                <p>Estudia cantidades, formas, números y sus reglas. Ayuda a pensar con lógica y resolver problemas de la vida diaria.</p>
            </div>
        </div>

        <div class="bg-white rounded-xl shadow-lg overflow-hidden mb-8 hover:shadow-xl transition-shadow">
            <img src="https://images.unsplash.com/photo-1532094349851-355601093a6e?w=800&q=80" alt="Química" class="w-full h-48 object-cover">
            <div class="p-6">
                <h3 class="text-2xl font-semibold text-principal mb-3"><i class="fa fa-flask"></i> Química</h3>
                <p>Explica de qué está hecho todo lo que nos rodea, cómo cambia y qué pasa cuando se mezclan las cosas.</p>
            </div>
        </div>

        <div class="bg-white rounded-xl shadow-lg overflow-hidden mb-8 hover:shadow-xl transition-shadow">
            <img src="https://images.unsplash.com/photo-1456513080510-7bf3a84b82f8?w=800&q=80" alt="Español" class="w-full h-48 object-cover">
            <div class="p-6">
                <h3 class="text-2xl font-semibold text-principal mb-3"><i class="fa fa-book"></i> Español</h3>
                <p>Aprendes a hablar, escribir y leer bien en nuestro idioma, además de conocer cuentos, poemas y lecturas interesantes.</p>
            </div>
        </div>

        <div class="bg-white rounded-xl shadow-lg overflow-hidden mb-8 hover:shadow-xl transition-shadow">
            <img src="https://images.unsplash.com/photo-1518770660439-4636190af475?w=800&q=80" alt="Informática" class="w-full h-48 object-cover">
            <div class="p-6">
                <h3 class="text-2xl font-semibold text-principal mb-3"><i class="fa fa-laptop"></i> Informática</h3>
                <p>Enseña cómo funcionan las computadoras, el internet y usar bien las herramientas digitales para estudiar y trabajar.</p>
            </div>
        </div>

        <div class="bg-white rounded-xl shadow-lg overflow-hidden mb-8 hover:shadow-xl transition-shadow">
            <img src="https://images.unsplash.com/photo-1523050854058-8df90110c9f1?w=800&q=80" alt="Idioma" class="w-full h-48 object-cover">
            <div class="p-6">
                <h3 class="text-2xl font-semibold text-principal mb-3"><i class="fa fa-comments"></i> Idioma</h3>
                <p>Aprendes otro idioma para hablar con gente de otros países, conocer más culturas y tener mejores oportunidades.</p>
            </div>
        </div>
    </section>

    <footer class="bg-oscuro text-white py-8 text-center">
        <p>© 2026 - Espacio de Aprendizaje</p>
    </footer>

</body>
</html>
