<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mavericks Games</title>
  <style>
    body {
      margin: 0;
      background-color: #0d1117;
      font-family: 'Segoe UI', sans-serif;
      color: #ffffff;
      padding: 0;
    }.header {
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #161b22;
  padding: 15px 20px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.5);
}

.header img {
  height: 35px;
}

.container {
  max-width: 420px;
  width: 100%;
  margin: 0 auto;
  padding: 20px;
}

.card {
  background-color: #161b22;
  border-radius: 15px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.5);
  overflow: hidden;
  margin-bottom: 20px;
}

.card img {
  width: 100%;
  height: auto;
}

.card-content {
  padding: 16px;
}

.title {
  font-size: 22px;
  font-weight: bold;
  margin-bottom: 6px;
}

.rating {
  color: #facc15;
  font-size: 14px;
  margin-bottom: 10px;
}

.info {
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 14px;
  margin-bottom: 16px;
  color: #c9d1d9;
}

.tag {
  background-color: #30363d;
  padding: 5px 10px;
  border-radius: 8px;
}

.download-btn {
  display: block;
  width: 100%;
  text-align: center;
  background: linear-gradient(to right, #0ea5e9, #3b82f6);
  color: #fff;
  padding: 12px;
  font-size: 16px;
  border: none;
  border-radius: 10px;
  text-decoration: none;
  transition: background 0.3s;
  margin-top: 10px;
  cursor: pointer;
}

.download-btn:hover {
  background: linear-gradient(to right, #0284c7, #2563eb);
}

  </style>
  <script>
    // Locker logic
    function showLocker(redirectUrl) {
      sessionStorage.setItem('redirectAfterLocker', redirectUrl);
      window.location.href = 'locker.html';
    }
  </script>
</head>
<body>
  <div class="header">
    <img src="https://i.postimg.cc/sXR1112v/20250513-234241.png" alt="Logo" />
  </div>  <div class="container"><!-- Minecraft Card -->
<div class="card">
  <img src="https://i.postimg.cc/xdckJWYb/images-6.jpg" alt="Minecraft Earth" />
  <div class="card-content">
    <div class="title">Minecraft Earth (Unlimited Coins)</div>
    <div class="rating">⭐ 4.7 (6.5k reviews)</div>
    <div class="info">
      <span class="tag">Adventure</span>
      <span>230 MB</span>
    </div>
    <button class="download-btn" onclick="showLocker('https://rexdl.com/android/minecraft-earth-apk.html/')">Download Game</button>
  </div>
</div>

<!-- Fortnite Card -->
<div class="card">
  <img src="https://i.postimg.cc/59ZbRPX5/fortnite-header.jpg" alt="Fortnite" />
  <div class="card-content">
    <div class="title">Fortnite (Unlimited Coins)</div>
    <div class="rating">⭐ 4.8 (9.2k reviews)</div>
    <div class="info">
      <span class="tag">Shooter</span>
      <span>300 MB</span>
    </div>
    <button class="download-btn" onclick="showLocker('https://www.fortnite.com/mobile/android')">Download Game</button>
  </div>
</div>

<!-- Royal Kingdom Card -->
<div class="card">
  <img src="https://i.postimg.cc/QxY8qXpt/royal-kingdom-art.jpg" alt="Royal Kingdom" />
  <div class="card-content">
    <div class="title">Royal Kingdom (Unlimited Coins)</div>
    <div class="rating">⭐ 4.6 (3.9k reviews)</div>
    <div class="info">
      <span class="tag">Strategy</span>
      <span>200 MB</span>
    </div>
    <button class="download-btn" onclick="showLocker('https://apkmody.com/games/royal-kingdom')">Download Game</button>
  </div>
</div>

  </div>
</body>
</html>
