<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>YUG</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(270deg, #ff6ec4, #7873f5, #4ade80, #facc15);
      background-size: 800% 800%;
      animation: gradientBG 10s ease infinite;
      font-family: 'Segoe UI', sans-serif;
    }
    h1 {
      font-size: 5rem;
      color: white;
      text-shadow: 0 0 20px rgba(0,0,0,0.5);
      animation: flicker 1.5s infinite;
    }
    @keyframes gradientBG {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    @keyframes flicker {
      0%, 19%, 21%, 23%, 25%, 54%, 56%, 100% {
        opacity: 1;
      }
      20%, 24%, 55% {
        opacity: 0.4;
      }
    }
  </style>
</head>
<body>
  <h1>YUG</h1>
</body>
</html>
