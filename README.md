# el-arrayan-taller
sitio web de El arrayan taller
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>El Arrayán Taller</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f4f1ec;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #3e3e3e;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    img.logo {
      width: 120px;
      margin-bottom: 1rem;
    }
    nav {
      background-color: #2e2e2e;
      text-align: center;
      padding: 1rem 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: bold;
    }
    section {
      padding: 2rem;
      text-align: center;
    }
    .galeria {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1rem;
    }
    .galeria img {
      width: 300px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.2);
    }
    footer {
      background-color: #3e3e3e;
      color: white;
      text-align: center;
      padding: 1rem;
    }
    .boton {
      background-color: #6f4e37;
      color: white;
      padding: 0.75rem 1.5rem;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
    }
    .boton:hover {
      background-color: #5c3e2b;
    }
  </style>
</head>
<body>
<header>
  <img src="logo.png" alt="El Arrayán Taller Logo" class="logo" />
  <h1>El Arrayán Taller</h1>
  <p>Carpintería artesanal - Muebles a medida</p>
</header>
<nav>
  <a href="#inicio">Inicio</a>
  <a href="#galeria">Galería</a>
  <a href="#contacto">Contacto</a>
</nav>
<section id="inicio">
  <h2>Bienvenidos</h2>
  <p>Transformamos madera en ideas. Realizamos muebles personalizados, rótulos y más.</p>
  <a class="boton" href="https://www.instagram.com/elarrayan.taller" target="_blank">Síguenos en Instagram</a>
</section>
<section id="galeria">
  <h2>Galería de Trabajos</h2>
  <div class="galeria">
    <img src="cocina.jpeg" alt="Mueble de Cocina" />
    <img src="rotulo.jpeg" alt="Rótulo Casa Cafetería" />
  </div>
</section>
<section id="contacto">
  <h2>Contacto</h2>
  <p>Escríbenos por Instagram para cotizar tu proyecto.</p>
</section>
<footer>
  <p>© 2025 El Arrayán Taller. Todos los derechos reservados.</p>
</footer>
</body>
</html>
