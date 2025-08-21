
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Simple Webpage</title>
  <style>
    /* CSS Styling */
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f4f8;
      color: #333;
      margin: 20px;
      padding: 20px;
    }

    h1 {
      color: #2c3e50;
    }

    p {
      font-size: 18px;
    }

    img {
      max-width: 300px;
      border-radius: 8px;
    }

    a {
      color: #2980b9;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    button {
      padding: 10px 20px;
      background-color: #27ae60;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }

    button:hover {
      background-color: #219150;
    }
  </style>
</head>
<body>

  <!-- HTML Structure -->
  <h1>Welcome to My Webpage</h1>
  <p>This is a simple webpage to demonstrate HTML, CSS, and JavaScript.</p>

  <img src="https://via.placeholder.com/300" alt="Sample Image">

  <p>Visit my <a href="https://example.com" target="_blank">website</a> for more info.</p>

  <button onclick="showMessage()">Click Me!</button>

  <!-- JavaScript Interactivity -->
  <script>
    function showMessage() {
      alert('Hello! You clicked the button.');
    }
  </script>

</body>
</html>
