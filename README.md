<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minimal Music Player</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #121212;
            color: white;
            padding: 20px;
        }
        .player {
            max-width: 400px;
            margin: auto;
            background: #1e1e1e;
            color: white;
            padding: 10px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.1);
        }
        audio {
            width: 100%;
            margin-top: 10px;
            background: #1e1e1e;
            color: white;
            border: none;
            outline: none;
        }
    </style>
</head>
<body>
    <div class="player">
        <audio id="audioPlayer" controls>
            <source src="https://files.catbox.moe/pv9ms8.mp3" type="audio/mp3">
            Your browser does not support the audio element.
        </audio>
    </div>
</body>
</html>
