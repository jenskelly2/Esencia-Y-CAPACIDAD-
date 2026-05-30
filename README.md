
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Esencia y Capacidad — Alexander Pérez</title>

<style>
  body {
    margin: 0;
    background: #0a1a2a;
    font-family: "Georgia", serif;
    color: #f5f5f5;
  }

  /* ---------------- PORTADA ANIMADA ---------------- */

  .hero {
    position: relative;
    height: 100vh;
    overflow: hidden;
  }

  .fog {
    position: absolute;
    top: 0;
    left: 0;
    width: 200%;
    height: 200%;
    background: url('https://i.imgur.com/8fK4h8W.png');
    background-size: cover;
    opacity: 0.25;
    animation: moveFog 40s linear infinite;
    filter: blur(8px);
  }

  @keyframes moveFog {
    0% { transform: translate(-10%, -10%); }
    50% { transform: translate(10%, 10%); }
    100% { transform: translate(-10%, -10%); }
  }

  .center {
    position: relative;
    z-index: 10;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
  }

  .symbol {
    font-size: 6rem;
    color: #d4af37;
    animation: glow 3s ease-in-out infinite;
  }

  @keyframes glow {
    0% { text-shadow: 0 0 10px #d4af37; opacity: 0.7; }
    50% { text-shadow: 0 0 25px #d4af37; opacity: 1; }
    100% { text-shadow: 0 0 10px #d4af37; opacity: 0.7; }
  }

  h1 {
    font-size: 3.5rem;
    color: #d4af37;
    letter-spacing: 3px;
    margin-top: 20px;
    opacity: 0;
    animation: fadeIn 3s ease forwards 1s;
  }

  @keyframes fadeIn {
    to { opacity: 1; }
  }

  p.subtitle {
    margin-top: 10px;
    font-size: 1.2rem;
    opacity: 0;
    animation: fadeIn 3s ease forwards 2s;
  }

  /* ---------------- SECCIONES ---------------- */

  section {
    max-width: 800px;
    margin: 80px auto;
    padding: 0 20px;
    line-height: 1.7;
  }

  h2 {
    color: #d4af37;
    margin-bottom: 10px;
    font-size: 2rem;
  }

  footer {
    text-align: center;
    padding: 40px;
    color: #888;
  }
</style>
</head>

<body>

<!-- PORTADA ANIMADA -->
<div class="hero">
  <div class="fog"></div>
  <div class="center">
    <div class="symbol">⟡</div>
    <h1>ESENCIA Y CAPACIDAD</h1>
    <p class="subtitle">Alexander Pérez</p>
  </div>
</div>

<!-- SINOPSIS -->
<section>
  <h2>Sinopsis</h2>
  <p>
    “Esencia y Capacidad” es una exploración profunda del autoconocimiento práctico.
    Un viaje hacia la claridad interior, la autenticidad y la capacidad real de actuar
    en el mundo sin perder la esencia personal.
  </p>
</section>

<!-- SOBRE EL AUTOR -->
<section>
  <h2>Sobre el Autor</h2>
  <p>
    Alexander Pérez es un creador enfocado en el desarrollo personal, la introspección
    y la construcción de proyectos auténticos. Su trabajo combina estética, claridad
    y profundidad emocional.
  </p>
</section>

<!-- EXTRACTO -->
<section>
  <h2>Extracto</h2>
  <p>
    “La esencia no se descubre en el ruido, sino en la pausa.  
    La capacidad no se mide por lo que haces, sino por lo que puedes sostener.”
  </p>
</section>

<!-- ENLACES -->
<section>
  <h2>Enlaces</h2>
  <ul>
    <li><a href="#" style="color:#d4af37;">Comprar el libro</a></li>
    <li><a href="#" style="color:#d4af37;">Descargar muestra</a></li>
  </ul>
</section>

<footer>
  © 2026 Alexander Pérez — Todos los derechos reservados
</footer>

</body>
</html>
