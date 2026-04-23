<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mis Juegos en Godot</title>
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
    }

    h1 {
      margin: 0;
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
      transition: transform 0.2s;
    }

    .card:hover {
      transform: scale(1.05);
    }

    .card img {
      width: 100%;
      height: 160px;
      object-fit: cover;
    }

    .content {
      padding: 15px;
    }

    h2 {
      margin-top: 0;
      color: #22c55e;
    }

    .btn {
      display: inline-block;
      margin-top: 8px;
      margin-right: 5px;
      padding: 8px 12px;
      border-radius: 6px;
      text-decoration: none;
      color: white;
      font-size: 0.9em;
    }

    .download { background: #2563eb; }
    .github { background: #0ea5e9; }

    footer {
      text-align: center;
      padding: 15px;
      font-size: 0.9em;
    }
  </style>
</head>

<body>

<header>
  <h1>🎮 Mis Minijuegos en Godot</h1>
  <p>FlappyBird · SpaceInvader · Jetpack · CoinDash</p>
</header>

<div class="container">

  <!-- FlappyBird -->
  <div class="card">
    <img src="https://programamos.es/web/wp-content/uploads/2016/10/flappybird.jpg">
    <div class="content">
      <h2>FlappyBird</h2>
      <p>Evita obstáculos volando y consigue la mayor puntuación posible.</p>
      <a class="btn download" href="https://codeload.github.com/nmartin-elpuig/FlappyBird/zip/refs/heads/main?token=BYMYJUN5Z4SLDFLJJHP6UILJ5IAQU">⬇️ Descargar</a>
      <a class="btn github" href="https://github.com/nmartin-elpuig/proyecto">💻 GitHub</a>
    </div>
  </div>

  <!-- SpaceInvader -->
  <div class="card">
    <img src="imagenes/spaceinvader.jpg">
    <div class="content">
      <h2>SpaceInvader</h2>
      <p>Defiende la Tierra eliminando oleadas de enemigos espaciales.</p>
      <a class="btn download" href="descargas/spaceinvader.zip">⬇️ Descargar</a>
      <a class="btn github" href=https://github.com/nmartin-elpuig/Jetpack/new/main>💻 GitHub</a>
    </div>
  </div>

  <!-- Jetpack -->
  <div class="card">
    <img src="imagenes/jetpack.jpg">
    <div class="content">
      <h2>Jetpack</h2>
      <p>Vuela con tu jetpack evitando trampas y recogiendo puntos.</p>
      <a class="btn download" href="https://codeload.github.com/nmartin-elpuig/Jetpack/zip/refs/heads/main?token=BYMYJUJBDYB7H2ZYXYQLGZLJ5IAME">⬇️ Descargar</a>
      <a class="btn github" href="https://github.com/nmartin-elpuig/Jetpack/tree/main">💻 GitHub</a>
    </div>
  </div>

  <!-- CoinDash -->
  <div class="card">
    <img src="imagenes/coindash.jpg">
    <div class="content">
      <h2>CoinDash</h2>
      <p>Recoge monedas lo más rápido posible antes de que se acabe el tiempo.</p>
      <a class="btn download" href="descargas/coindash.zip">⬇️ Descargar</a>
      <a class="btn github" href="https://github.com/tuusuario/coindash">💻 GitHub</a>
    </div>
  </div>

</div>

<footer>
  <p>Hecho con ❤️ usando Godot</p>
</footer>

</body>
</html>
