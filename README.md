<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Yadira Álvarez Beauty Studio</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fffafc;
      color: #333;
    }
    header {
      background-color: #ffc0cb;
      padding: 20px;
      text-align: center;
      color: white;
    }
    nav {
      background-color: #f8e1e7;
      padding: 10px;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #c2185b;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      color: #c2185b;
    }
    .servicios, .galeria {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .servicio, .foto {
      flex: 1 1 calc(33% - 20px);
      background-color: #fff;
      border: 1px solid #eee;
      padding: 10px;
      text-align: center;
    }
    footer {
      background-color: #f8e1e7;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }
    @media(max-width: 768px){
      .servicio, .foto {
        flex: 1 1 100%;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Yadira Álvarez Beauty Studio</h1>
  <p>Realza tu belleza con estilo y elegancia</p>
</header>

<nav>
  <a href="#inicio">Inicio</a>
  <a href="#servicios">Servicios</a>
  <a href="#galeria">Galería</a>
  <a href="#nosotros">Nosotros</a>
  <a href="#contacto">Contacto</a>
</nav>

<section id="inicio">
  <h2>Bienvenidos</h2>
  <p>En Yadira Álvarez Beauty Studio te ofrecemos un espacio dedicado a resaltar tu belleza natural. Confía en nuestras manos expertas para transformarte.</p>
</section>

<section id="servicios">
  <h2>Servicios</h2>
  <div class="servicios">
    <div class="servicio"><strong>Corte y peinado</strong></div>
    <div class="servicio"><strong>Maquillaje profesional</strong></div>
    <div class="servicio"><strong>Manicure y Pedicure</strong></div>
    <div class="servicio"><strong>Cejas y Pestañas</strong></div>
    <div class="servicio"><strong>Coloración</strong></div>
    <div class="servicio"><strong>Paquetes para novias</strong></div>
  </div>
</section>

<section id="galeria">
  <h2>Galería</h2>
  <div class="galeria">
    <div class="foto">[Foto 1]</div>
    <div class="foto">[Foto 2]</div>
    <div class="foto">[Foto 3]</div>
  </div>
</section>

<section id="nosotros">
  <h2>Sobre Nosotros</h2>
  <p>Soy Yadira Álvarez, una apasionada estilista con más de 10 años de experiencia. Mi misión es brindar servicios personalizados que reflejen tu estilo y te hagan sentir hermosa.</p>
</section>

<section id="contacto">
  <h2>Contacto</h2>
  <p>📞 Teléfono / WhatsApp: <strong>099 123 4567</strong></p>
  <p>📍 Dirección: Calle Belleza, El Coca, Ecuador</p>
  <p>📸 Instagram: <a href="#">@yadira_beauty</a></p>
</section>

<footer>
  © 2025 Yadira Álvarez Beauty Studio. Todos los derechos reservados.
</footer>

</body>
</html>
