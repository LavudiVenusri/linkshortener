<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Link Shortener</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background-color: lavenderblush; /* light purple background */
    }

    .container {
      text-align: center;
      margin-top: 100px;
    }

    h1 {
      color: #6a5acd; /* dark purple */
    }

    input[type="text"] {
      padding: 8px;
      margin-bottom: 10px;
    }

    button {
      padding: 8px 16px;
      background-color: #6a5acd; /* dark purple */
      color: white;
      border: none;
      cursor: pointer;
    }

    button:hover {
      background-color: #9370db; /* lighter purple on hover */
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Link Shortener</h1>
    <input type="text" id="originalUrl" placeholder="Enter URL">
    <button onclick="shortenLink()">Shorten</button>
    <p id="shortenedUrl"></p>
  </div>
  
  <script>
    function shortenLink() {
      var originalUrl = document.getElementById('originalUrl').value;
      // Logic to shorten the URL (replace this with your implementation)
      // For demonstration purposes, just echoing the input URL as the shortened URL
      document.getElementById('shortenedUrl').innerText = "Shortened URL: " + originalUrl;
    }
  </script>
</body>
</html>
