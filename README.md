
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Password Check</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 40px; }
    #result { margin-top: 20px; color: green; font-weight: bold; }
  </style>
</head>
<body>
  <h2>Enter the password:</h2>
  <input type="password" id="passwordInput" placeholder="Password">
  <button onclick="checkPassword()">Submit</button>
  <div id="result"></div>
  <script>
    function checkPassword() {
      const input = document.getElementById('passwordInput').value.trim();
      if (input.toLowerCase() === "i choose chaos".toLowerCase()) {
        document.getElementById('result').textContent = "A Fissure In Tranquility. Embrace The Chaos. Partake In The Madness. Strife Awaits.<a href='https://example.com/chaos' target='_blank'> Riot</a>";
      } else {
        document.getElementById('result').textContent = "";
      }
    }
  </script>
</body>
</html>
