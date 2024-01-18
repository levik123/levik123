 <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
  body, html {
    height: 100%;
    margin: 0;
  }

  .animated-background {
    background-image: url('your-background-image.jpg');
    height: 100%;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    animation: moveBackground 10s linear infinite;
  }

  @keyframes moveBackground {
    0% { background-position: 0 0; }
    50% { background-position: 100% 0; }
    100% { background-position: 0 0; }
  }
</style>
</head>
<body>

<div class="animated-background"></div>

</body>
</html>
