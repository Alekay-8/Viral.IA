<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LUMINA AI | Inteligencia Artificial para Negocios</title>

  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">

  <style>
    body { font-family: 'Inter', system-ui, sans-serif; }
    .hero-font { font-family: 'Space Grotesk', sans-serif; }
    .navy-bg { background-color: #0A1428; }
    .cream { color: #F5EDE1; }
    .cream-accent { color: #E8D5B7; }
    .card { transition: all 0.4s ease; }
    .card:hover { transform: translateY(-15px); box-shadow: 0 30px 60px -15px rgba(59, 130, 246, 0.3); }
  </style>
</head>

<body class="navy-bg text-slate-200">

  <!-- NAVBAR -->
  <nav class="fixed top-0 w-full bg-[#0A1428]/90 backdrop-blur-lg border-b border-white/10 z-50">
    <div class="max-w-7xl mx-auto px-6 py-5 flex justify-between items-center">
      <h1 class="text-3xl font-bold hero-font text-white">LUMINA<span class="cream-accent">AI</span></h1>

      <a href="https://wa.me/19155045344" target="_blank"
        class="bg-[#E8D5B7] text-[#0A1428] px-6 py-3 rounded-full font-semibold hover:bg-white transition flex items-center gap-2">
        <i class="fab fa-whatsapp"></i> WhatsApp
      </a>
    </div>
  </nav>

  <!-- HERO -->
  <section class="min-h-screen flex items-center pt-20">
    <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">

      <div class="space-y-8">
        <h2 class="text-6xl font-bold hero-font cream">
          Consigue más clientes en automático con IA
        </h2>

        <p class="text-xl text-slate-400">
          Automatizamos tu negocio para generar ventas sin contratar más personal.
        </p>

        <div class="flex gap-4">
          <a href="https://wa.me/19155045344" target="_blank"
            class="bg-blue-600 px-10 py-4 rounded-xl font-semibold">
            Hablar por WhatsApp
          </a>

          <a href="#form" class="border px-10 py-4 rounded-xl">
            Solicitar demo
          </a>
        </div>

        <p class="text-sm text-green-400">
          ✓ Sin código ✓ Resultados rápidos ✓ Soporte directo
        </p>
      </div>

      <img src="https://picsum.photos/600/500" class="rounded-2xl">

    </div>
  </section>

  <!-- FORM -->
  <section id="form" class="py-20 text-center">
    <div class="max-w-xl mx-auto">

      <h2 class="text-4xl font-bold mb-6">
        Solicita tu demo gratuita
      </h2>

      <form action="https://formspree.io/f/FORM_ID" method="POST" class="space-y-4">

        <input type="text" name="name" placeholder="Tu nombre" required
          class="w-full bg-[#1E2937] px-6 py-3 rounded-xl">

        <input type="email" name="email" placeholder="Tu email" required
          class="w-full bg-[#1E2937] px-6 py-3 rounded-xl">

        <textarea name="message" placeholder="¿Qué necesitas?" required
          class="w-full bg-[#1E2937] px-6 py-3 rounded-xl"></textarea>

        <button type="submit"
          class="w-full bg-blue-600 py-3 rounded-xl font-semibold">
          Solicitar demo
        </button>

      </form>

      <p class="text-red-400 mt-4 text-sm">
        Solo estamos tomando 5 negocios este mes
      </p>

    </div>
  </section>

  <!-- FOOTER -->
  <footer class="text-center py-10 text-slate-500">
    © 2026 Lumina AI
  </footer>

</body>
</html>