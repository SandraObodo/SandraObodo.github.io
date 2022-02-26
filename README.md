<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>RGB</title>
    <link rel="stylesheet" type="text/css" href="styles.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap"
      rel="stylesheet"
    />
  </head>
  <body>
    <h1>
      The Great
      <span id="color-display">
        <span id="r" class="rgb">R</span>
        <span id="g" class="rgb">G</span>
        <span id="b" class="rgb">B</span>
      </span>
      Guessing Game
    </h1>
    <div id="stripe">
      <button id="reset">Start</button>
      <span id="message"></span>
      <button class="mode">Easy</button>
      <button class="mode selected">Hard</button>
    </div>

    <div id="container">
      <div class="square"></div>
      <div class="square"></div>
      <div class="square"></div>
      <div class="square"></div>
      <div class="square"></div>
      <div class="square"></div>
    </div>

    <script type="text/javascript" src="app.js"></script>
  </body>
</html>
