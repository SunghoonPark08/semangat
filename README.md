<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Animasi Semangat!</title>
  <style>
    body {
      background-color: #fdf6e3;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .semangat {
      font-size: 48px;
      font-weight: bold;
      color: #ff5722;
      animation: semangatAnim 1.5s infinite;
      margin-bottom: 20px;
    }
    .gambar {
      width: 200px;
      height: auto;
      animation: bounce 2s infinite;
    }
    @keyframes semangatAnim {
      0% { transform: scale(1); opacity: 1; }
      50% { transform: scale(1.2); opacity: 0.7; }
      100% { transform: scale(1); opacity: 1; }
    }
    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
    }
  </style>
</head>
<body>
  <div class="semangat">Semangat!</div>
  <img class="gambar" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNG9zYjltNmZ3NG4xczB6a3h3ZzR3ZnB0anU5bGduajJlY3lkNzZtMiZlcD12MV9naWZzX3NlYXJjaCZjdD1n/fxsqOYnIMEefC/giphy.gif" alt="Semangat GIF" />
</body>
</html>
