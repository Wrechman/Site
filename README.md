<!DOCTYPE html>
<html>
<head>
  <title>My Links</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Bangers&display=swap" rel="stylesheet">
  <style>
    /* CSS styles here */
    body {
      background-color: #000000;
      margin: 0;
      padding: 0;
      font-family: 'Bangers', cursive;
    }

    .container {
      text-align: center;
      margin-top: 150px;
      position: relative;
    }

    h1, h2, a {
      font-size: 36px;
      color: #00ff00;
      letter-spacing: 3px;
      text-shadow: 0 0 5px #00ff00;
      animation: pulse 3s infinite;
      position: relative;
      z-index: 2;
    }

    h2 {
      text-decoration: underline;
    }

    a {
      text-decoration: none;
      transition: color 0.3s;
    }

    a:hover {
      color: #00cc00;
    }

    ul {
      list-style: none;
      padding: 0;
      margin: 30px 0;
    }

    li {
      margin-bottom: 15px;
    }

    /* Digital-like background */
    .bg-square {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background-color: #333343;
  width: 70%;
  height: 150%;
  opacity: 0.2;
  z-index: -1;
}


    @keyframes pulse {
      0% {
        text-shadow: 0 0 5px #00ff00;
      }
      50% {
        text-shadow: 0 0 10px #00ff00;
      }
      100% {
        text-shadow: 0 0 5px #00ff00;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="bg-square"></div>
    <h1>WRECHMAN</h1>
    <h2>My Links</h2>
    <ul>
      <li>
        <a href="https://www.youtube.com/channel/UCoBqZ-Z-wdJifnfe7LzMyfw" target="_blank">YouTube</a>
      </li>
      <li>
        <a href="https://www.twitch.tv/wrechman_" target="_blank">Twitch</a>
      </li>
      <li>
        <a href="https://www.mariokart64.com/mk64/players/3342" target="_blank">My MK64 Rankings</a>
      </li>
    </ul>
  </div>
</body>
</html>
