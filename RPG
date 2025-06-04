<!-- Salve como index.html -->
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Elementos e Ramificações</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-image: url('https://images.unsplash.com/photo-1601297183302-75e33b5e1b3c'); 
      background-size: cover;
      background-position: center;
      backdrop-filter: brightness(0.7);
      height: 100vh;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .container {
      background: rgba(0, 0, 0, 0.6);
      padding: 30px;
      border-radius: 15px;
      max-width: 500px;
      width: 100%;
      text-align: center;
      box-shadow: 0 0 15px rgba(0,0,0,0.5);
    }

    input, button {
      padding: 10px;
      font-size: 16px;
      margin-top: 10px;
      width: 100%;
      border: none;
      border-radius: 5px;
    }

    button {
      background-color: #ff6600;
      color: white;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #cc5200;
    }

    .resultado {
      margin-top: 20px;
      font-size: 18px;
      white-space: pre-wrap;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Ramificações dos Elementos</h1>
    <input type="text" id="elemento" placeholder="Digite um elemento..." />
    <button onclick="mostrarRamificacoes()">Buscar</button>
    <div class="resultado" id="resultado"></div>
  </div>

  <script>
    const elementos = {
      "Fogo": ["Lava", "Explosão", "Plasma", "Dracônico"],
      "Lava": ["Fogo"],
      "Explosão
