<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="stylesheet" href="https://cdn.plyr.io/3.7.8/plyr.css" />
  <title>Guided Meditation</title>
</head>
<body>
  <h2 style="text-align:center;">🎧 Guided Meditation</h2>
  <audio id="player" controls>
    <source src="https://docs.google.com/uc?export=download&id=1pccjLjQkUyhhNOWZ_kG_v29NUqD7ukCk" type="audio/mp3" />
  </audio>

  <script src="https://cdn.plyr.io/3.7.8/plyr.polyfilled.js"></script>
  <script>
    const player = new Plyr('#player');
  </script>
</body>
</html>
