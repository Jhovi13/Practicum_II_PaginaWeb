<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>coo-ki'</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #3E5841; 
            color: #FFFDDC; 
        }
        .bg-yucatan-green { background-color: #3E5841; }
        .text-yucatan-green { color: #3E5841; }
        .bg-terracotta { background-color: #A24936; }
        .text-terracotta { color: #A24936; }
        .bg-orange-burnt { background-color: #D56135; }
        .text-orange-burnt { color: #D56135; }
        .bg-cream { background-color: #FFFDDC; }
        .text-cream { color: #FFFDDC; }
    </style>
</head>
<body class="bg-[#3E5841] text-[#FFFDDC] antialiased">

    <header class="w-[900px] mx-auto pt-16 pb-12 text-center">
        <span class="inline-block px-4 py-1 mb-4 text-xs font-semibold uppercase tracking-widest bg-[#A24936] text-[#FFFDDC] rounded-full">Wireframe / Prácticum II Equipo 5D</span>
        <h1 class="text-6xl font-bold tracking-tight text-[#FFFDDC] mb-4">coo-ki'(Cambiar por logo)</h1>
        <p class="text-2xl font-medium text-[#FFFDDC]/90 max-w-2xl mx-auto">
            Galletas artesanales elaboradas con harina de <em>Tenebrio molitor</em> y tubérculos tradicionales mayas.
        </p>
    </header>

    <main class="w-[900px] mx-auto space-y-12 pb-20">

        <section class="bg-[#2e4331] border-2 border-[#A24936] rounded-xl p-6 shadow-md">
            <h2 class="text-lg font-bold text-[#FFFDDC] mb-3 uppercase tracking-wider text-center">Video de Elaboración / Proceso</h2>
            <div class="w-full h-80 bg-[#3E5841] border-2 border-dashed border-[#D56135] rounded-lg flex flex-col items-center justify-center text-center p-6">
                <svg class="w-16 h-16 text-[#D56135] mb-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M14.752 11.168l-3.197-2.132A1 1 0 0010 9.87v4.263a1 1 0 001.555.832l3.197-2.132a1 1 0 000-1.664z"></path>
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                </svg>
                <span class="text-sm font-semibold text-[#FFFDDC]">ESPACIO RESERVADO PARA VIDEO DE ELABORACIÓN O EXPLICACIÓN</span>
              
            </div>
        </section>

        <section class="bg-[#2e4331] border border-[#A24936]/40 rounded-xl p-8 shadow-md">
            <h2 class="text-2xl font-bold text-[#FFFDDC] mb-4 border-b-2 border-[#D56135] pb-2">Problemática y Oportunidad</h2>
            <p class="text-base leading-relaxed text-[#FFFDDC]/90 mb-4">
                Entre el <strong>15% y el 25%</strong> de los tubérculos locales (camote, yuca y makal) se pierden como merma (cáscaras, corteza y pulpa) durante la cosecha en la península de Yucatán, terminando habitualmente en vertederos.
            </p>
            <p class="text-base leading-relaxed text-[#FFFDDC]/90">
                La oportunidad radica en utilizar estas mermas como sustrato orgánico para la crianza eficiente de <em>Tenebrio molitor</em>, transformando un residuo regional en una fuente de proteína sustentable de alta calidad sin competir con la ganadería convencional.
            </p>
        </section>

        <section class="bg-[#2e4331] border border-[#A24936]/40 rounded-xl p-8 shadow-md">
            <h2 class="text-2xl font-bold text-[#FFFDDC] mb-4 border-b-2 border-[#D56135] pb-2">Ciclo y Proceso de Producción Circular</h2>
            <div class="grid grid-cols-3 gap-4 text-sm mt-4">
                <div class="bg-[#3E5841] p-4 rounded-lg border border-[#A24936]">
                    <span class="block font-bold text-[#D56135] mb-1">1. Bioconversión</span>
                    <span class="text-[#FFFDDC]/80">Las larvas consumen los residuos de camote, yuca y makal, transformándolos en biomasa proteica y generando frass.</span>
                </div>
                <div class="bg-[#3E5841] p-4 rounded-lg border border-[#A24936]">
                    <span class="block font-bold text-[#D56135] mb-1">2. Procesamiento</span>
                    <span class="text-[#FFFDDC]/80">Ayuno, lavado, inactivación térmica, deshidratación y molienda fina para obtener harina de insecto sin neofobia.</span>
                </div>
                <div class="bg-[#3E5841] p-4 rounded-lg border border-[#A24936]">
                    <span class="block font-bold text-[#D56135] mb-1">3. Horneado</span>
                    <span class="text-[#FFFDDC]/80">Mezcla homogénea con harinas de tubérculos mayas y horneado a 180°C para lograr una galleta crocante.</span>
                </div>
            </div>
        </section>

        <section class="bg-[#2e4331] border border-[#A24936]/40 rounded-xl p-8 shadow-md">
            <h2 class="text-2xl font-bold text-[#FFFDDC] mb-4 border-b-2 border-[#D56135] pb-2">Perfil Nutricional Destacado</h2>
            <ul class="space-y-3 text-base text-[#FFFDDC]/90">
                <li class="flex items-start">
                    <span class="inline-block w-2 h-2 mt-2 mr-3 bg-[#D56135] rounded-full"></span>
                    <span><strong>52.4% de proteína cruda</strong> promedio en materia seca aportada por el <em>Tenebrio molitor</em>, con aminoácidos esenciales (leucina, valina, lisina).</span>
                </li>
                <li class="flex items-start">
                    <span class="inline-block w-2 h-2 mt-2 mr-3 bg-[#D56135] rounded-full"></span>
                    <span><strong>Camote, yuca y makal:</strong> Aporte de carbohidratos complejos, fibra dietética y almidones resistentes que mejoran la microbiota y regulan el índice glucémico.</span>
                </li>
                <li class="flex items-start">
                    <span class="inline-block w-2 h-2 mt-2 mr-3 bg-[#D56135] rounded-full"></span>
                    <span><strong>Sin aditivos sintéticos:</strong> Libre de colorantes artificiales, con sabor y color natural derivados de la raíz del camote.</span>
                </li>
            </ul>
        </section>

        <section class="bg-[#2e4331] border border-[#A24936]/40 rounded-xl p-8 shadow-md">
            <h2 class="text-2xl font-bold text-[#FFFDDC] mb-6 border-b-2 border-[#D56135] pb-2">Exploración Visual (Wireframe de Empaque y Producto)</h2>
            <div class="grid grid-cols-2 gap-6">
                <!-- Placeholder 1 -->
                <div class="flex flex-col items-center">
                    <div class="w-full h-48 bg-[#3E5841] border-2 border-dashed border-[#A24936] rounded-lg flex flex-col items-center justify-center p-4 text-center">
                        <svg class="w-10 h-10 text-[#D56135] mb-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M4 16l4.586-4.586a2 2 0 012.828 0L16 16m-2-2l1.586-1.586a2 2 0 012.828 0L20 14m-6-6h.01M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"></path>
                        </svg>
                        <span class="text-xs font-semibold text-[#FFFDDC]">ESPACIO RESERVADO: GALLETA HORNEADA</span>
                    </div>
                    <span class="text-xs text-[#FFFDDC]/70 mt-2">Detalle de textura rugosa y color dorado natural</span>
                </div>
                <!-- Placeholder 2 -->
                <div class="flex flex-col items-center">
                    <div class="w-full h-48 bg-[#3E5841] border-2 border-dashed border-[#A24936] rounded-lg flex flex-col items-center justify-center p-4 text-center">
                        <svg class="w-10 h-10 text-[#D56135] mb-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M4 16l4.586-4.586a2 2 0 012.828 0L16 16m-2-2l1.586-1.586a2 2 0 012.828 0L20 14m-6-6h.01M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"></path>
                        </svg>
                        <span class="text-xs font-semibold text-[#FFFDDC]">ESPACIO RESERVADO FOTOGRAFÍA DEL EMPAQUE FINAL</span>
                    </div>
                    <span class="text-xs text-[#FFFDDC]/70 mt-2">BEMPAQUE FINA</span>
                </div>
            </div>
        </section>

    </main>

    <footer class="w-full bg-[#293c2c] text-[#FFFDDC] py-8 text-center text-sm border-t border-[#A24936]/30">
        <p class="font-medium">Prácticum II </p>
        <p class="text-xs mt-1 text-[#FFFDDC]/70">Equipo 5D: Santiago Sánchez, José Pablo Visoso, Said Wabi, Rodrigo Cruz.</p>
    </footer>

</body>
</html>
