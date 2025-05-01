<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simple Redirect Website</title>
  <style>
    body {
      background-color: #222;
      color: #fff;
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 100px;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
      background-color: crimson;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: darkred;
    }
  </style>
</head>
<body>
  <h1>Welcome to My Simple Website</h1>
  <p>Click the button to go to DemonicChill's YouTube channel!</p>
  <button onclick="redirectToDemonicChill()">Go to DemonicChill's YouTube</button>

  <script>
    function redirectToDemonicChill() {
      window.location.href = "https://www.youtube.com/@DemonicChill2";  // Redirect to DemonicChill's YouTube channel
    }
  </script>
</body>
</html>
