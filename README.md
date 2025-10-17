# brochhure
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>METALLIFT | Consultoría Estratégica en Transporte Vertical</title>
    <!-- Carga de Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Carga de íconos Lucide (formal y vectorial) -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <!-- Configuración de la fuente y colores de Tailwind basados en el logo -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'metallift-primary': '#002147', // Azul marino del logo
                        'metallift-accent': '#FFC72C', // Amarillo/Oro del logo
                        'metallift-action': '#E53E3E', // Rojo para CTAs y alertas
                        'metallift-bg': '#F7FAFC', // Gris claro para fondo
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        .hide-scrollbar::-webkit-scrollbar { display: none; }
        .hide-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
        /* Clases de utilidad para iconos */
        .icon-lg { width: 1.5rem; height: 1.5rem; }

        /* Estilos específicos para el carrusel de testimonios */
        .testimonial-carousel {
            scroll-snap-type: x mandatory;
            -webkit-overflow-scrolling: touch;
        }
        .testimonial-item {
            scroll-snap-align: start;
            flex: 0 0 100%;
        }

        /* Estilo para simular el calendario de citas */
        .calendar-mock {
            background-color: #ffffff;
            border: 2px solid #ddd;
            padding: 1rem;
        }
    </style>
</head>
<body class="bg-gray-100 font-sans text-gray-800">
    
    <div class="max-w-xl mx-auto bg-white rounded-xl shadow-2xl overflow-hidden">

        <!-- HEADER: LOGO, Slogan y Contacto -->
        <header class="bg-metallift-primary text-white py-8 px-4 text-center">
            <div class="flex items-center justify-center mb-2">
                <!-- *** REEMPLAZO DE LOGO FUNCIONAL (NOMBRE ESTILIZADO) *** -->
                <div class="h-12 sm:h-16 max-h-16 flex items-end">
                    <span class="text-3xl sm:text-4xl font-extrabold tracking-widest text-white">METALLIFT</span>
                </div>
            </div>
            
            <h1 class="text-2xl sm:text-3xl font-extrabold tracking-tight mb-1">
                Consultoría Estratégica
            </h1>
            <p class="text-md font-light text-gray-300 mt-1">
                Su Aliado Imparcial para la Seguridad y el Cumplimiento.
            </p>
            <!-- LOCALIZACIÓN ELIMINADA PARA FACILITAR LA EXPANSIÓN -->
        </header>

        <!-- Sección 1: Introducción y Propuesta de Valor -->
        <section class="py-8 px-4">
            <h2 class="text-xl font-bold text-metallift-primary mb-3 text-center">
                ¿Está su Propiedad Horizontal realmente protegida?
            </h2>
            <p class="text-sm text-gray-600 mb-6">
                Los equipos de transporte vertical (ascensores, escaleras, montacoches) exponen a la copropiedad a **riesgos legales y financieros significativos** por incumplimiento de NTC, sobrecostos o mantenimiento deficiente. METALLIFT es el **escudo imparcial** que usted necesita.
            </p>

            <div class="grid grid-cols-2 gap-4">
                <div class="p-3 bg-metallift-bg rounded-lg text-center shadow-inner">
                    <p class="text-md font-bold text-metallift-action flex items-center justify-center space-x-1">
                        <i data-lucide="shield-check" class="icon-lg"></i><span>Mitigue el Riesgo Legal</span>
                    </p>
                    <p class="text-xs text-gray-600">Evite la co-responsabilidad ante incidentes.</p>
                </div>
                <div class="p-3 bg-metallift-bg rounded-lg text-center shadow-inner">
                    <p class="text-md font-bold text-metallift-action flex items-center justify-center space-x-1">
                        <i data-lucide="dollar-sign" class="icon-lg"></i><span>Garantice la Inversión</span>
                    </p>
                    <p class="text-xs text-gray-600">Asegure precios justos y calidad en repuestos/proyectos.</p>
                </div>
            </div>
        </section>

        <!-- Sección de Cifras de Autoridad -->
        <section class="py-6 px-4 bg-metallift-primary text-white text-center">
            <h3 class="text-xl font-bold text-metallift-accent mb-3">
                Nuestra Promesa se Mide en Resultados
            </h3>
            <div class="grid grid-cols-3 gap-2">
                <div>
                    <p class="text-2xl font-extrabold text-white">+25%</p>
                    <p class="text-xs font-light text-gray-300">Ahorro Promedio en Modernizaciones</p>
                </div>
                <div>
                    <p class="text-2xl font-extrabold text-white">99%</p>
                    <p class="text-xs font-light text-gray-300">Equipos que aprueban ITE*</p>
                </div>
                <div>
                    <p class="text-2xl font-extrabold text-white">4 PUNTOS</p>
                    <p class="text-xs font-light text-gray-300">Garantía en Cumplimiento NTC</p>
                </div>
            </div>
        </section>


        <!-- Sección 2: Pilares de Servicio (Diseño de Tarjetas) -->
        <section class="py-8 px-4 bg-metallift-bg">
            <h3 class="text-xl font-bold text-metallift-primary mb-4 text-center">
                Nuestros 4 Pilares de Servicio
            </h3>
            
            <div class="space-y-4">
                
                <!-- Pilar 1: Proyectos -->
                <div class="p-4 bg-white rounded-xl shadow border-l-4 border-metallift-accent">
                    <h4 class="text-lg font-bold text-metallift-primary flex items-center mb-1 space-x-2">
                        <i data-lucide="building-2" class="icon-lg text-metallift-action"></i><span>1. Blindaje en Proyectos (Inversión)</span>
                    </h4>
                    <p class="text-sm text-gray-600">Auditoría de Recepción de Obra Nueva, pliegos NTC y eliminación de cláusulas contractuales lesivas. **Protegemos su inversión desde el papel.**</p>
                </div>

                <!-- Pilar 2: Auditoría Continua de Mantenimiento -->
                <div class="p-4 bg-white rounded-xl shadow border-l-4 border-metallift-accent">
                    <h4 class="text-lg font-bold text-metallift-primary flex items-center mb-1 space-x-2">
                        <i data-lucide="clipboard-check" class="icon-lg text-metallift-action"></i><span>2. Auditoría Continua de Mantenimiento</span>
                    </h4>
                    <p class="text-sm text-gray-600">Verificamos las buenas prácticas, la idoneidad del personal y el cumplimiento de la mantenedora. **Somos su Gerente de Calidad Externa.**</p>
                </div>
                
                <!-- Pilar 3: Auditoría de Cumplimiento al Propietario -->
                <div class="p-4 bg-white rounded-xl shadow border-l-4 border-metallift-accent">
                    <h4 class="text-lg font-bold text-metallift-primary flex items-center mb-1 space-x-2">
                        <i data-lucide="user-check" class="icon-lg text-metallift-action"></i><span>3. Auditoría de Cumplimiento al Propietario</span>
                    </h4>
                    <p class="text-sm text-gray-600">Revisamos que la administración cumpla con su **compromiso legal** (presupuesto y Certificación de Inspección) y evite la co-responsabilidad por omisión.</p>
                </div>

                 <!-- Pilar 4: Soporte a la Industria -->
                <div class="p-4 bg-white rounded-xl shadow border-l-4 border-metallift-accent">
                    <h4 class="text-lg font-bold text-metallift-primary flex items-center mb-1 space-x-2">
                        <i data-lucide="handshake" class="icon-lg text-metallift-action"></i><span>4. Soporte a la Industria (Validación Externa)</span>
                    </h4>
                    <p class="text-sm text-gray-600">Ofrecemos validación técnica pericial a mantenedoras y auditoría externa para incluirlas en nuestra **Base de Proveedores Referenciados**.</p>
                </div>
            </div>
        </section>
        
        <!-- ======================================================= -->
        <!-- NUEVAS FUNCIONES INTERACTIVAS -->
        <!-- ======================================================= -->

        <!-- FUNCIÓN 1: Calculadora de Riesgo Rápido -->
        <section class="py-8 px-4 bg-metallift-bg">
            <h3 class="text-xl font-bold text-metallift-primary mb-4 text-center">
                Calculadora de Riesgo Rápido
            </h3>
            <div id="risk-calculator" class="p-4 bg-white rounded-xl shadow">
                <div class="space-y-4">
                    <div class="flex flex-col">
                        <label for="antiguedad" class="text-sm font-medium text-gray-700">Antigüedad del Equipo (Años):</label>
                        <input type="number" id="antiguedad" min="1" max="50" value="10" class="mt-1 p-2 border border-gray-300 rounded-md focus:ring-metallift-accent focus:border-metallift-accent">
                    </div>
                    <div class="flex flex-col">
                        <label for="trafico" class="text-sm font-medium text-gray-700">Tráfico (Diario):</label>
                        <select id="trafico" class="mt-1 p-2 border border-gray-300 rounded-md focus:ring-metallift-accent focus:border-metallift-accent">
                            <option value="1">Bajo (Residencial pequeño)</option>
                            <option value="2">Medio (Residencial grande/Mixto)</option>
                            <option value="3">Alto (Comercial/Hospitalario)</option>
                        </select>
                    </div>
                    <div class="flex flex-col">
                        <label for="ultimafalla" class="text-sm font-medium text-gray-700">Fallas Graves en el Último Año:</label>
                        <select id="ultimafalla" class="mt-1 p-2 border border-gray-300 rounded-md focus:ring-metallift-accent focus:border-metallift-accent">
                            <option value="1">Ninguna</option>
                            <option value="2">1 - 3 Fallas</option>
                            <option value="3">Más de 3 Fallas</option>
                        </select>
                    </div>
                    <button onclick="calcularRiesgo()" class="w-full bg-metallift-action hover:bg-red-700 text-white font-bold py-2 rounded-md transition duration-300">
                        Calcular mi Riesgo
                    </button>
                    <div id="resultado-riesgo" class="mt-4 p-3 rounded-lg text-center font-bold text-lg bg-metallift-bg border border-gray-300">
                        Nivel de Riesgo: 
                    </div>
                </div>
            </div>
        </section>

        <!-- FUNCIÓN 2: Testimonios Dinámicos (Carrusel) -->
        <section class="py-8 px-4 bg-white">
            <h3 class="text-xl font-bold text-metallift-primary mb-4 text-center flex items-center justify-center space-x-2">
                <i data-lucide="quote" class="icon-lg text-metallift-accent"></i><span>La Voz de Nuestros Clientes</span>
            </h3>
            <div id="testimonios" class="relative">
                <div class="flex overflow-x-scroll testimonial-carousel hide-scrollbar snap-x snap-mandatory">
                    
                    <!-- Testimonio 1 (Ficticio - Foco: Ahorro) -->
                    <div class="testimonial-item p-4 border rounded-xl shadow-md bg-metallift-bg mr-4">
                        <p class="text-sm italic text-gray-700">"Gracias a la auditoría de METALLIFT, logramos reducir el costo de nuestra modernización en un 28% al identificar componentes innecesarios. Su acompañamiento fue invaluable."</p>
                        <p class="mt-3 text-right font-semibold text-metallift-primary text-sm">- Ing. Javier López, Administrador PH 'Torres del Este'</p>
                    </div>

                    <!-- Testimonio 2 (Ficticio - Foco: Tranquilidad Legal) -->
                    <div class="testimonial-item p-4 border rounded-xl shadow-md bg-metallift-bg mr-4">
                        <p class="text-sm italic text-gray-700">"Teníamos miedo de la próxima inspección por la antigüedad del equipo. METALLIFT nos preparó al detalle, y la auditoría pasó sin un solo problema grave. Total tranquilidad legal."</p>
                        <p class="mt-3 text-right font-semibold text-metallift-primary text-sm">- Dra. Ana María Soto, Consejo de Administración</p>
                    </div>

                    <!-- Testimonio 3 (Ficticio - Foco: Mantenedora) -->
                    <div class="testimonial-item p-4 border rounded-xl shadow-md bg-metallift-bg">
                        <p class="text-sm italic text-gray-700">"El informe pericial de METALLIFT nos ayudó a desvirtuar un reclamo injusto de un cliente por negligencia. Su imparcialidad nos dio el respaldo técnico que necesitábamos."</p>
                        <p class="mt-3 text-right font-semibold text-metallift-primary text-sm">- Gerencia, Ascensores Globales [Espacio para tu Proveedor Referenciado]</p>
                    </div>

                </div>
                <div id="carousel-dots" class="flex justify-center mt-3 space-x-2">
                    <!-- Dots generados por JS -->
                </div>
            </div>
            <p class="text-center text-xs text-gray-500 mt-4">*Estos testimonios son ejemplos de casos de éxito y deben ser reemplazados por sus clientes reales.</p>
        </section>

        <!-- CTA Principal y Botón de WhatsApp (Foco para compartir) -->
        <section class="py-8 px-4 bg-metallift-accent text-center">
            <h2 class="text-2xl font-bold text-metallift-primary mb-2">
                ¡Contáctenos Hoy!
            </h2>
            <p class="text-md font-bold text-metallift-action mb-4">
                ¡OFERTA EXCLUSIVA! 🎁 Comuníquese ahora mismo y obtenga un 30% de descuento.
            </p>
            <p class="text-md font-medium text-gray-800 mb-6">
                Reciba una evaluación inicial de sus equipos y mitigue sus riesgos antes de que sea demasiado tarde.
                <br>
                <span class="font-bold text-metallift-primary mt-2 block">Email: administracion@metallift.net</span>
            </p>
            <!-- CTA DIRECTO A WHATSAPP -->
            <a href="https://wa.me/573019763859?text=Hola%2C%20quisiera%20solicitar%20una%20evaluaci%C3%B3n%20inicial%20de%20mis%20equipos%20de%20transporte%20vertical.%20%C2%BFMe%20pueden%20dar%20m%C3%A1s%20informaci%C3%B3n%3F" target="_blank" class="inline-block bg-metallift-action hover:bg-red-700 text-white text-lg font-bold py-3 px-6 rounded-full transition duration-300 shadow-xl flex items-center justify-center space-x-2 mx-auto max-w-xs">
                <span>WhatsApp Ahora</span>
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-message-square-text"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/><path d="M13 8H7"/><path d="M17 12H7"/></svg>
            </a>
        </section>

        <!-- FOOTER: Normativa y Contacto -->
        <footer class="bg-gray-800 text-gray-400 py-4 px-4 text-center text-xs">
             <div class="flex justify-center space-x-4 mb-2">
                <span class="text-white font-semibold">Regulaciones Clave:</span>
                <span class="text-metallift-accent">NTC-5926-1</span>
                <span class="text-metallift-accent">RETIE</span>
            </div>
            <p>Email: <a href="mailto:administracion@metallift.net" class="text-metallift-accent hover:underline">administracion@metallift.net</a></p>
            &copy; 2025 METALLIFT. Soluciones a todo nivel.
        </footer>
    </div>
    
    <!-- Scripts de Funcionalidad -->
    <script>
        // Inicialización de Íconos de Lucide
        document.addEventListener('DOMContentLoaded', () => {
            if (typeof lucide !== 'undefined' && lucide.createIcons) {
                lucide.createIcons();
            }
            inicializarCarrusel();
        });

        // ----------------------------------------------------
        // FUNCIÓN 1: CALCULADORA DE RIESGO RÁPIDO
        // ----------------------------------------------------
        function calcularRiesgo() {
            const antiguedad = parseInt(document.getElementById('antiguedad').value);
            const trafico = parseInt(document.getElementById('trafico').value);
            const fallas = parseInt(document.getElementById('ultimafalla').value);
            const resultadoDiv = document.getElementById('resultado-riesgo');
            
            // Lógica de puntuación de riesgo (Máx 10 puntos = Máximo Riesgo)
            let riesgo = 0;
            
            // 1. Antigüedad (1-5 pts)
            if (antiguedad > 20) riesgo += 5;
            else if (antiguedad > 10) riesgo += 3;
            else if (antiguedad > 5) riesgo += 1;

            // 2. Tráfico (1-3 pts)
            riesgo += trafico; // Bajo(1), Medio(2), Alto(3)

            // 3. Fallas (1-3 pts)
            riesgo += fallas; // Ninguna(1), 1-3(2), +3(3)

            // Escala de Riesgo (Total posible: 11 pts)
            let colorClass = 'bg-green-100 text-green-700';
            let nivelTexto = 'BAJO';

            if (riesgo >= 8) {
                colorClass = 'bg-red-100 text-red-700';
                nivelTexto = 'CRÍTICO';
            } else if (riesgo >= 5) {
                colorClass = 'bg-yellow-100 text-yellow-700';
                nivelTexto = 'MEDIO';
            }

            resultadoDiv.className = `mt-4 p-3 rounded-lg text-center font-bold text-lg border ${colorClass}`;
            resultadoDiv.innerHTML = `Nivel de Riesgo: **${nivelTexto}** (${riesgo} / 11)`;
        }

        // ----------------------------------------------------
        // FUNCIÓN 2: TESTIMONIOS DINÁMICOS (CARRUSEL)
        // ----------------------------------------------------
        function inicializarCarrusel() {
            const carrusel = document.querySelector('.testimonial-carousel');
            const items = document.querySelectorAll('.testimonial-item');
            const dotsContainer = document.getElementById('carousel-dots');
            const totalItems = items.length;

            if (totalItems === 0) return;

            // Crear los dots
            for (let i = 0; i < totalItems; i++) {
                const dot = document.createElement('span');
                dot.className = 'w-2 h-2 rounded-full bg-gray-400 cursor-pointer transition duration-300';
                dot.setAttribute('data-index', i);
                dotsContainer.appendChild(dot);
            }

            const dots = dotsContainer.querySelectorAll('span');

            // Función para actualizar los dots
            const actualizarDots = () => {
                const scrollLeft = carrusel.scrollLeft;
                const itemWidth = items[0].offsetWidth + (carrusel.scrollWidth - carrusel.clientWidth) / (totalItems - 1);
                const currentIndex = Math.round(scrollLeft / itemWidth);

                dots.forEach((dot, index) => {
                    dot.classList.remove('bg-metallift-action');
                    dot.classList.add('bg-gray-400');
                    if (index === currentIndex) {
                        dot.classList.add('bg-metallift-action');
                        dot.classList.remove('bg-gray-400');
                    }
                });
            };

            carrusel.addEventListener('scroll', actualizarDots);
            
            // Inicializar el primer dot
            actualizarDots(); 
        }

        // ----------------------------------------------------
        // FUNCIÓN 3: CHATBOT DE PREGUNTAS FRECUENTES (FAQ) - ELIMINADA
        // ----------------------------------------------------
    </script>
    <!-- Script para inicializar los íconos de Lucide -->
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            if (typeof lucide !== 'undefined' && lucide.createIcons) {
                lucide.createIcons();
            }
        });
    </script>
</body>
</html>
