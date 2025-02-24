<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Abre tu Carta</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <style>
    /* Fondo decorado: degradado y patrón sutil */
    body {
      background: linear-gradient(135deg, #fce4ec, #ffe4e1);
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      overflow: hidden;
      position: relative;
    }
    /* Pseudo-elemento para el patrón de fondo */
    body::before {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background-image: 
        radial-gradient(circle at 20% 20%, rgba(233, 30, 99, 0.15) 10%, transparent 10%),
        radial-gradient(circle at 80% 80%, rgba(233, 30, 99, 0.15) 10%, transparent 10%);
      background-size: 150px 150px;
      opacity: 0.5;
      z-index: -1;
    }
    /* Estilos para la carta */
    .card {
      background: #fff;
      border: 2px dashed #ffb6c1;
      padding: 2rem;
      border-radius: 15px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      width: 90%;
      max-width: 600px;
      text-align: center;
      position: relative;
      overflow: hidden;
    }
    .card h1 {
      color: #e91e63;
      margin-bottom: 1rem;
      font-size: 2.5rem;
    }
    .card p {
      color: #333;
      margin-bottom: 1.5rem;
      line-height: 1.5;
      font-size: 1.2rem;
    }
    .card a {
      display: inline-block;
      background: #e91e63;
      color: #fff;
      text-decoration: none;
      padding: 0.75rem 1.5rem;
      border-radius: 5px;
      font-size: 1rem;
      transition: background 0.3s ease;
    }
    .card a:hover {
      background: #c2185b;
    }
    /* Decoraciones: corazones animados en las esquinas */
    .decorative-heart {
      position: absolute;
      font-size: 2.5rem;
      animation: floatHeart 4s infinite ease-in-out;
    }
    .decorative-heart.top-left {
      top: -20px;
      left: -20px;
    }
    .decorative-heart.bottom-right {
      bottom: -20px;
      right: -20px;
      animation-direction: reverse;
    }
    @keyframes floatHeart {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }
  </style>
</head>
<body>
  <div class="card">
    <!-- Corazones decorativos -->
    <div class="decorative-heart top-left">💖</div>
    <div class="decorative-heart bottom-right">💖</div>
    <h1>HOLAAAA!!</h1>
    <p>👉🏼 HAZ CLICK EN EL BOTÓN, ESPERO TE GUSTE.. 👈🏼</p>
    <!-- Redirige a la página de San Valentín -->
    <a href="San Valentin.html">Abrir Carta</a>
  </div>
</body>
</html>
