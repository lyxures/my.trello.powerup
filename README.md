<!DOCTYPE html>
<html>
<head>
  <title>My Trello Power-Up</title>
  <script src="https://p.trellocdn.com/power-up.min.js"></script>
</head>
<body>
  <h2>Hello from My Trello Power-Up!</h2>

  <script>
    var t = TrelloPowerUp.iframe();

    // Close iframe modal example
    // You can add more Power-Up logic here
  </script>
</body>
</html>

{
  "name": "Investigation Tool",
  "description": "Custom Power-Up for investigations.",
  "author": "Your Name",
  "capabilities": {
    "board-buttons": [
      {
        "text": "Open Investigation Panel",
        "url": "https:/lyxures.github.io/my.trello.powerup/iframe.html",
        "target": "overlay"
      }
    ]
  }
}
