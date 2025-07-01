<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Stopwatch</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f0f4f8;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 20px;
    }

    .timer {
      font-size: 4em;
      margin-bottom: 30px;
    }

    .buttons {
      display: flex;
      gap: 15px;
    }

    button {
      padding: 10px 20px;
      font-size: 1em;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.2s;
    }

    button.start { background-color: #28a745; color: white; }
    button.pause { background-color: #ffc107; color: black; }
    button.reset { background-color: #dc3545; color: white; }

    button:hover {
      opacity: 0.9;
    }
  </style>
</head>
<body>

  <h1>Stopwatch</h1>
  <div class="timer" id="display">00:00:00</div>
  <div class="buttons">
    <button class="start" onclick="start()">Start</button>
    <button class="pause" onclick="pause()">Pause</button>
    <button class="reset" 
</div>
</body>
</html>
    
