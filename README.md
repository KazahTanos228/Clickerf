<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Кликер Империя</title>
  <style>
    body { text-align: center; font-family: sans-serif; background: linear-gradient(#222, #555); color: white; }
    h1 { margin-top: 30px; }
    #click { font-size: 30px; padding: 10px 20px; margin: 20px; border-radius: 8px; }
    #upgrade { background: #00c853; color: #fff; border: none; padding: 10px; margin-top: 10px; border-radius: 6px; }
  </style>
</head>
<body>
  <h1>Кликер Империя</h1>
  <div>
    <h2>Очки: <span id="score">0</span></h2>
    <button id="click">Клик!</button><br>
    <button id="upgrade">Улучшить (+1 за клик) — 10 очков</button>
  </div>

  <script src="game.js"></script>
</body>
</html>
