<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Feliz Cumpleaños Mamá 🎂</title>
  <style>
    /* Estilo general */
    body {
      margin: 0;
      padding: 0;
      font-family: 'Poppins', sans-serif;
      color: #fff;
      text-align: center;
      height: 100vh;
      background-image: url('globos.jpg');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      display: flex;
      flex-direction: column;
      justify-content: center;
      backdrop-filter: brightness(0.6);
    }

    h1 {
      font-size: 4em;
      margin: 0;
      text-shadow: 3px 3px 10px rgba(0,0,0,0.6);
      animation: aparecer 2s ease-in-out;
    }

    p {
      font-size: 1.5em;
      margin-top: 10px;
      text-shadow: 2px 2px 6px rgba(0,0,0,0.5);
      animation: aparecer 3s ease-in-out;
    }

    .corazon {
      font-size: 2em;
      animation: latir 1s infinite;
    }

    @keyframes latir {
      0%, 100% { transform: scale(1); color: #ff7eb9; }
      50% { transform: scale(1.3); color: #ff3d9e; }
    }

    @keyframes aparecer {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* Pie de página */
    footer {
      position: absolute;
      bottom: 15px;
      width: 100%;
      font-size: 1em;
      color: #ffe5f1;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.4);
    }
  </style>
</head>
<body>
  <h1>🎉 ¡Feliz Cumpleaños, Mamá! 🎂</h1>
  <p>Eres la luz de mi vida, gracias por tanto amor ❤️</p>
  <div class="corazon">💖</div>

  <footer>Con mucho amor, tu hijo 💕</footer>
</body>
</html>
