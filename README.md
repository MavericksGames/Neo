<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Redirecting...</title>
  <script>
    const gameId = localStorage.getItem('unlockGame');
    const games = {
      'royal-kingdom': 'https://apkmody.com/games/royal-kingdom',
      'fortnite': 'https://www.fortnite.com/mobile/android',
      'minecraft-earth': 'https://rexdl.com/android/minecraft-earth-apk.html/'
    };
    const fallback = 'https://google.com';
    window.location.href = games[gameId] || fallback;
    localStorage.removeItem('unlockGame');
  </script>
</head>
<body>
  <p>Redirecting...</p>
</body>
</html>
