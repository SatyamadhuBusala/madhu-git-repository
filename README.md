<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Welcome Board</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #ffecd2, #fcb69f);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    .welcome-board {
      background: white;
      padding: 40px 60px;
      border-radius: 20px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
      text-align: center;
      border: 5px solid #ff69b4;
      animation: pop 1s ease-in-out;
    }

    .welcome-board h1 {
      font-size: 3rem;
      background: linear-gradient(90deg, #ff00cc, #3333ff);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      margin-bottom: 20px;
    }

    .welcome-board p {
      font-size: 1.2rem;
      color: #555;
    }

    @keyframes pop {
      0% {
        transform: scale(0.8);
        opacity: 0;
      }
      100% {
        transform: scale(1);
        opacity: 1;
      }
    }
  </style>
</head>
<body>

  <div class="welcome-board">
    <h1>🌟 Welcome 🌟</h1>
    <p>We’re glad to have you here!</p>
  </div>

</body>
</html>
