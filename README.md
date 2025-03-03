<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Music Player</title>
    <style>
        body { text-align: center; font-family: Arial, sans-serif; background: transparent; }
        button { font-size: 16px; padding: 8px 12px; margin: 5px; cursor: pointer; border-radius: 5px; border: none; }
        button:hover { background: #ddd; }
    </style>
</head>
<body>
    <audio id="bg-music" loop>
        <source src="https://media1.vocaroo.com/mp3/1f50gBo2UxPV" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <button onclick="document.getElementById('bg-music').play()">▶ Play</button>
    <button onclick="document.getElementById('bg-music').pause()">⏸ Pause</button>
</body>
</html>
