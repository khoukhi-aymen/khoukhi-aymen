<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aymen Khoukhi</title>
  <style>
    body {
      background-color: black;
      overflow: hidden;
    }

    h1 {
      color: white;
      text-align: center;
    }

    .container {
      position: relative;
      width: 100%;
      height: 100vh;
    }

    .ball {
      position: absolute;
      border-radius: 50%;
      background-color: #FFC107;
      animation: moveBall linear infinite;
    }

    @keyframes moveBall {
      0% {
        top: 0;
        left: 0;
      }
      50% {
        top: 50%;
        left: 50%;
      }
      100% {
        top: 100%;
        left: 100%;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Hi, I'm Aymen Khoukhi! <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30"></h1>
    <div class="ball"></div>
  </div>
</body>
</html>

