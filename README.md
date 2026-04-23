<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mis Minijuegos en Godot</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: #e2e8f0;
    }

    header {
      background: #020617;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #1e293b;
    }

    h1 {
      margin: 0;
      font-size: 2em;
      color: #38bdf8;
    }

    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .card {
      background: #1e293b;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 4px 15px rgba(0,0,0,0.4);
      transition: transform 0.2s;
    }

    .card:hover {
      transform: scale(1.03);
    }

    .card img {
      width: 100%;
      height: 160px;
      object-fit: cover;
    }

    .card-content {
      padding: 15px;
    }

    .card h2 {
      margin-top: 0;
      color: #22c55e;
    }

    .buttons {
      margin-top: 10px;
    }

    .btn {
      display: inline-block;
      margin: 5px 5px 0 0;
      padding: 8px 12px;
      border-radius: 6px;
      text-decoration: none;
      color: white;
      font-size: 0.9em;
    }

    .download {
      background: #2563eb;
    }

    .github {
      background: #0ea5e9;
    }

    footer {
      text-align: center;
      padding: 15px;
      border-top: 1px solid #1e293b;
      margin-top: 20px;
      font-size: 0.9em;
    }
  </style>
</head>

<body>

<header>
  <h1>🎮 Mis Minijuegos en Godot</h1>
  <p>Proyectos hechos con Godot Engine</p>
</header>

<div class="container">

  <!-- JUEGO 1 -->
  <div class="card">
    <img src="imagenes/juego1.jpg" alt="Juego 1">
    <div class="card-content">
      <h2>Space Shooter</h2>
      <p>Dispara a enemigos y sobrevive el mayor tiempo posible en el espacio.</p>
      <div class="buttons">
        <a class="btn download" href="descargas/juego1.zip">⬇️ Descargar</a>
        <a class="btn github" href="https://github.com/tuusuario/juego1">💻 GitHub</a>
      </div>
    </div>
  </div>

  <!-- JUEGO 2 -->
  <div class="card">
    <img src="imagenes/juego2.jpg" alt="Juego 2">
    <div class="card-content">
      <h2>Plataformas 2D</h2>
      <p>Salta obstáculos y llega al final del nivel en este juego clásico.</p>
      <div class="buttons">
        <a class="btn download" href="descargas/juego2.zip">⬇️ Descargar</a>
        <a class="btn github" href="https://github.com/tuusuario/juego2">💻 GitHub</a>
      </div>
    </div>
  </div>

  <!-- JUEGO 3 -->
  <div class="card">
    <img src="imagenes/juego3.jpg" alt="Juego 3">
    <div class="card-content">
      <h2>Puzzle Game</h2>
      <p>Resuelve puzzles cada vez más difíciles para avanzar.</p>
      <div class="buttons">
        <a class="btn download" href="descargas/juego3.zip">⬇️ Descargar</a>
        <a class="btn github" href="https://github.com/tuusuario/juego3">💻 GitHub</a>
      </div>
    </div>
  </div>

  <!-- JUEGO 4 -->
  <div class="card">
    <img src="imagenes/juego4.jpg" alt="Juego 4">
    <div class="card-content">
      <h2>Racing Game</h2>
      <p>Compite contra el tiempo en circuitos llenos de curvas.</p>
      <div class="buttons">
        <a class="btn download" href="descargas/juego4.zip">⬇️ Descargar</a>
        <a class="btn github" href="https://github.com/tuusuario/juego4">💻 GitHub</a>
      </div>
    </div>
  </div>

</div>

<footer>
  <p>Hecho con ❤️ usando Godot Engine</p>
</footer>

</body>
</html>
