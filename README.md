<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="A simple APK hosting site for easy access to APK downloads">
  <title>APK Hosting Site</title>
  <style>
    /* Basic Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      color: #333;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }

    main {
      padding: 20px;
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
    }

    .apk-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
    }

    .apk-item {
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      padding: 20px;
      width: 250px;
      text-align: center;
    }

    .apk-item h3 {
      margin-bottom: 10px;
    }

    .apk-item p {
      font-size: 0.9em;
      color: #777;
      margin-bottom: 20px;
    }

    .apk-item a {
      display: inline-block;
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }

    .apk-item a:hover {
      background-color: #45a049;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 10px;
      position: fixed;
      width: 100%;
      bottom: 0;
    }

    footer p {
      margin: 0;
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <header>
    <h1>APK Hosting Platform</h1>
    <p>Your favorite APKs, one click away!</p>
  </header>

  <!-- Main Content -->
  <main>
    <h2>Available APKs</h2>
    <div class="apk-list">
      <!-- APK 1 -->
      <div class="apk-item">
        <h3>Super Game</h3>
        <p>A fun and addictive game for your Android device.</p>
        <a href="https://yourserver.com/uploads/super-game.apk" download>Download APK</a>
      </div>

      <!-- APK 2 -->
      <div class="apk-item">
        <h3>Weather App</h3>
        <p>Stay updated with the latest weather forecasts.</p>
        <a href="https://yourserver.com/uploads/weather-app.apk" download>Download APK</a>
      </div>

      <!-- APK 3 -->
      <div class="apk-item">
        <h3>Fitness Tracker</h3>
        <p>Track your fitness goals and progress easily.</p>
        <a href="https://yourserver.com/uploads/fitness-tracker.apk" download>Download APK</a>
      </div>

      <!-- Add more APKs as needed -->
    </div>
  </main>

  <!-- Footer Section -->
  <footer>
    <p>&copy; 2025 APK Hosting Platform. All rights reserved.</p>
  </footer>

</body>
</html>
