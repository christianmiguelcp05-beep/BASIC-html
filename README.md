# BASIC-html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ejercicio 2: HTML Basics</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      line-height: 1.6;
      color: #333;
      background-color: #f5f7fa;
    }

    header {
      background-color: #1a4d8f;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    nav a {
      color: #fff;
      margin: 0 12px;
      text-decoration: none;
    }

    nav a:hover,
    nav a:focus {
      text-decoration: underline;
    }

    main {
      max-width: 700px;
      margin: 20px auto;
      padding: 0 20px;
    }

    section {
      background-color: #fff;
      padding: 16px 20px;
      margin-bottom: 20px;
      border-radius: 8px;
    }

    h2 {
      color: #2f7d5b;
    }

    li {
      margin-bottom: 4px;
    }

    a {
      color: #1a4d8f;
    }

    footer {
      text-align: center;
      padding: 16px;
      background-color: #e8eef7;
    }
  </style>
</head>
<body>
  <header>
    <h1>HTML Basics</h1>
    <nav aria-label="Navegación principal">
      <a href="#conceptos">Conceptos</a>
      <a href="#elementos">Elementos</a>
      <a href="#recursos">Recursos</a>
    </nav>
  </header>

  <main>
    <section id="conceptos">
      <h2>Conceptos básicos</h2>
      <p>
        HTML (HyperText Markup Language) es el lenguaje que define la
        estructura de una página web. CSS se encarga de su presentación.
      </p>
    </section>

    <section id="elementos">
      <h2>Elementos que aprendí</h2>
      <ul>
        <li>Encabezados (<code>h1</code> a <code>h6</code>)</li>
        <li>Párrafos (<code>p</code>)</li>
        <li>Listas ordenadas y desordenadas (<code>ol</code>, <code>ul</code>)</li>
        <li>Enlaces (<code>a</code>)</li>
      </ul>

      <h3>Pasos para crear una página</h3>
      <ol>
        <li>Crear el archivo <code>index.html</code>.</li>
        <li>Escribir la estructura básica del documento.</li>
        <li>Agregar contenido y aplicar estilos.</li>
      </ol>
    </section>

    <section id="recursos">
      <h2>Recursos útiles</h2>
      <p>
        Para seguir practicando, visita
        <a href="https://developer.mozilla.org/es/docs/Learn/HTML" target="_blank" rel="noopener noreferrer">la guía de HTML en MDN Web Docs</a>.
      </p>
    </section>
  </main>

  <footer>
    <p>Ejercicio 2 - HTML Basics</p>
  </footer>
</body>
</html>
