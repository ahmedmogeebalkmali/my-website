# my-website
Public
<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>موقع بسيط متحرك</title>
<style>
  body {
    direction: rtl;
    font-family: Arial, sans-serif;
    background-color: #000022;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
  }
  h1 {
    font-size: 64px;
    font-weight: bold;
    color: #fff;
    animation: colorChange 5s infinite alternate, moveText 4s infinite linear;
  }
  @keyframes colorChange {
    0% { color: #ff0000; }
    25% { color: #00ff00; }
    50% { color: #0000ff; }
    75% { color: #ffff00; }
    100% { color: #ff00ff; }
  }
  @keyframes moveText {
    0% { transform: translateX(0); }
    50% { transform: translateX(50px); }
    100% { transform: translateX(0); }
  }
</style>
</head>
<body>
<h1>أحببك ريم</h1>
</body>
</html>
