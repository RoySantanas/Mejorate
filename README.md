
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>✨Animo✨</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background: #fff0f6;
      padding: 30px;
    }
    h1 {
      color: #ff6fb0;
      text-shadow: 2px 2px #ffe6f0;
    }
    p {
      font-size: 18px;
      color: #555;
    }
    .gatito {
      font-size: 80px;
      margin: 20px;
    }
    button {
      background: #ffb3d9;
      border: none;
      padding: 12px 20px;
      margin: 10px;
      border-radius: 8px;
      font-size: 16px;
      cursor: pointer;
      transition: 0.2s;
    }
    button:hover {
      background: #ff99cc;
    }
  </style>
</head>
<body>
  <h1>✨Animo✨</h1>
  <p>Ojalá tu día se ilumine poquito a poquito 💜</p>

  <div id="gatito" class="gatito">🐱</div>
  <p id="mensaje">¿Cómo te sientes hoy?</p>

  <button onclick="sentirseBien()">😊 Bien</button>
  <button onclick="sentirseMal()">😔 No muy bien</button>

  <script>
    function sentirseBien() {
      document.getElementById("gatito").innerHTML = "😺";
      document.getElementById("mensaje").innerHTML = "Me alegra mucho 💜 ¡Sigue sonriendo!";
    }
    function sentirseMal() {
      document.getElementById("gatito").innerHTML = "😿";
      document.getElementById("mensaje").innerHTML = "Ánimo 💜 incluso los días difíciles pasan.";
    }
  </script>
</body>
</html>
