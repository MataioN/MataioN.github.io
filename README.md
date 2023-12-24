<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      .test {
        animation: fadeIn 5s;
      }
      @keyframes fadeIn {
        0% {
          opacity: 0;
        }
        100% {
          opacity: 1;
        }
      }
    </style>
  </head>
  <body>
    <div class="test">
      <p>Bella, I love you so much!</p>
    </div>
  </body>
</html>

@-ms-keyframes fadeIn {
  0% { opacity: 0; }
  100% { opacity: 1; }
}
