<!DOCTYPE html>
<script>
  // STEP 1: Get the game ID from the URL (e.g., ?game=fortnite)
  const gameId = new URLSearchParams(window.location.search).get('game');

  // STEP 2: List all your games and their unlock links
  const games = {
    "fortnite": "https://www.fortnite.com/mobile/android",
    "minecraft-earth": "https://rexdl.com/android/minecraft-earth-apk.html/",
    "royal-kingdom": "https://apkmody.com/games/royal-kingdom"
    // Add new games here later (e.g., "new-game": "https://new-link.com")
  };

  // STEP 3: Redirect to the game or fallback to games directory
  window.location.href = games[gameId] || "https://YOUR-GITHUB-USERNAME.github.io/REPO-NAME/games.html";
</script><!DOCTYPE html>
<html>
<head>
    <title>All Games</title>
    <style>
        body { 
            font-family: Arial; 
            text-align: center; 
            padding: 30px;
            background: #f5f5f5;
        }
        .game-link {
            display: block;
            margin: 20px;
            font-size: 20px;
            color: #3498db;
            text-decoration: none;
        }
        .game-link:hover {
            color: #2980b9;
        }
    </style>
</head>
<body>
    <h1>All Working Games</h1>
    <a href="https://www.fortnite.com/mobile/android" class="game-link">🎮 Fortnite Android</a>
    <a href="https://rexdl.com/android/minecraft-earth-apk.html/" class="game-link">🧱 Minecraft Earth APK</a>
    <a href="https://apkmody.com/games/royal-kingdom" class="game-link">👑 Royal Kingdom</a>
    <!-- Add new games here later -->
</body>
</html>
