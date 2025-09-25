<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mi Web Personal</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-800">

  <!-- Header -->
  <header class="bg-blue-600 text-white shadow-md">
    <div class="max-w-4xl mx-auto p-6 flex justify-between items-center">
      <h1 class="text-2xl font-bold">Mi Web Personal</h1>
      <nav class="space-x-4">
        <a href="#sobre-mi" class="hover:underline">Sobre mí</a>
        <a href="#proyectos" class="hover:underline">Proyectos</a>
        <a href="#contacto" class="hover:underline">Contacto</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="max-w-4xl mx-auto text-center py-20">
    <img src="https://via.placeholder.com/150" alt="Foto de perfil" class="rounded-full mx-auto mb-6 shadow-lg" />
    <h2 class="text-3xl font-bold">¡Hola! Soy [Tu Nombre]</h2>
    <p class="mt-4 text-lg text-gray-600">Desarrollador web | Apasionado de la tecnología</p>
    <a href="#contacto" class="mt-6 inline-block bg-blue-600 text-white px-6 py-3 rounded-lg shadow hover:bg-blue-700">Contáctame</a>
  </section>

  <!-- Sobre mí -->
  <section id="sobre-mi" class="max-w-4xl mx-auto py-16 px-6">
    <h3 class="text-2xl font-bold mb-4">Sobre mí</h3>
    <p class="text-gray-700 leading-relaxed">
      Soy un desarrollador apasionado por crear aplicaciones modernas y fáciles de usar. 
      Me gusta aprender nuevas tecnologías y compartir mis proyectos con la comunidad.
    </p>
  </section>

  <!-- Proyectos -->
  <section id="proyectos" class="bg-gray-200 py-16 px-6">
    <div class="max-w-4xl mx-auto">
      <h3 class="text-2xl font-bold mb-6">Proyectos</h3>
      <div class="grid md:grid-cols-2 gap-6">
        <div class="bg-white p-6 rounded-xl shadow">
          <h4 class="text-xl font-semibold mb-2">Proyecto 1</h4>
          <p class="text-gray-600">Descripción breve de tu proyecto.</p>
        </div>
        <div class="bg-white p-6 rounded-xl shadow">
          <h4 class="text-xl font-semibold mb-2">Proyecto 2</h4>
          <p class="text-gray-600">Descripción breve de tu proyecto.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="max-w-4xl mx-auto py-16 px-6">
    <h3 class="text-2xl font-bold mb-6">Contacto</h3>
    <p class="text-gray-700 mb-4">Puedes escribirme a:</p>
    <a href="mailto:tuemail@ejemplo.com" class="text-blue-600 hover:underline">tuemail@ejemplo.com</a>
  </section>

  <!-- Footer -->
  <footer class="bg-blue-600 text-white py-6 mt-10">
    <div class="max-w-4xl mx-auto text-center">
      <p>&copy; 2025 Mi Web Personal. Hecho con ❤️ en GitHub Pages.</p>
    </div>
  </footer>
</body>
</html>
