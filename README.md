<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - Maruf Bellah</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #f4f4f9;
    }

    .portfolio-container {
      display: flex;
      width: 90%;
      max-width: 1200px;
      background-color: #fff;
      box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
      border-radius: 10px;
      overflow: hidden;
    }

    .left-section {
      background-color: #2c3e50;
      color: #fff;
      flex: 1;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 20px;
    }

    .left-section img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      margin-bottom: 20px;
      border: 4px solid #ecf0f1;
    }

    .left-section h2 {
      margin-bottom: 10px;
    }

    .left-section p {
      text-align: center;
      font-size: 14px;
      line-height: 1.6;
    }

    .right-section {
      flex: 2;
      padding: 30px;
    }

    .right-section h1 {
      margin-bottom: 20px;
      color: #2c3e50;
    }

    .info-group {
      margin-bottom: 15px;
    }

    .info-group strong {
      display: inline-block;
      width: 120px;
      color: #34495e;
    }

    .info-group span {
      color: #7f8c8d;
    }

    .social-links {
      display: flex;
      gap: 10px;
      margin-top: 20px;
    }

    .social-links a {
      text-decoration: none;
      color: #fff;
      background-color: #3498db;
      padding: 10px 15px;
      border-radius: 5px;
      transition: background-color 0.3s;
    }

    .social-links a:hover {
      background-color: #2980b9;
    }
  </style>
</head>
<body>
  <div class="portfolio-container">
    <!-- Left Section -->
    <div class="left-section">
      <img src="https://via.placeholder.com/150" alt="Maruf Bellah">
      <h2>Maruf Bellah</h2>
      <p>Passionate Frontend Developer from Bangladesh. Focused on creating dynamic, beautiful, and responsive web applications.</p>
    </div>

    <!-- Right Section -->
    <div class="right-section">
      <h1>About Me</h1>
      <div class="info-group">
        <strong>📍 Address:</strong> <span>Dhaka, Bangladesh</span>
      </div>
      <div class="info-group">
        <strong>📧 Email:</strong> <span>mdmaruf5511507@gmail.com</span>
      </div>
      <div class="info-group">
        <strong>📞 Phone:</strong> <span>+880123456789</span>
      </div>
      <div class="info-group">
        <strong>🌐 Website:</strong> <span><a href="https://maruf-bellah.netlify.app/" target="_blank">maruf-bellah.netlify.app</a></span>
      </div>
      <div class="info-group">
        <strong>⚡ Fun Fact:</strong> <span>I am Funny!</span>
      </div>

      <div class="social-links">
        <a href="https://linkedin.com" target="_blank">LinkedIn</a>
        <a href="https://github.com" target="_blank">GitHub</a>
        <a href="https://twitter.com" target="_blank">Twitter</a>
      </div>
    </div>
  </div>
</body>
</html>
