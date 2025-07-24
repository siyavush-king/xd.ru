# xd.ru
site owner XD
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>XD.ru - HTML devohelper</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body, html {
      height: 100%;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: white;
      text-align: center;
      background: url('background.jpg') no-repeat center center fixed;
      background-size: cover;
      backdrop-filter: brightness(0.9);
    }

    .overlay {
      background-color: rgba(0, 0, 0, 0.5);
      height: 100%;
      width: 100%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    h1 {
      font-size: 4rem;
      margin-bottom: 1rem;
    }

    p {
      font-size: 1.5rem;
      opacity: 0.9;
    }

    .tagline {
      margin-top: 20px;
      font-style: italic;
      color: #aaa;
    }

    .telegram-button {
      margin-top: 30px;
      padding: 12px 24px;
      font-size: 1rem;
      background-color: #229ED9;
      border: none;
      border-radius: 8px;
      color: white;
      cursor: pointer;
      transition: background-color 0.3s ease;
      text-decoration: none;
    }

    .telegram-button:hover {
      background-color: #1a8cb8;
    }
  </style>
</head>
<body>
  <div class="overlay">
    <h1>XD.ru</h1>
    <p>HTML devohelper</p>
    <p class="tagline">Your magic begins here...</p>

    <a class="telegram-button" href="https://t.me/helper4403" target="_blank">Telegram</a>
  </div>
</body>
</html>
