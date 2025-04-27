<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Happy Birthday Beautiful!</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #ffe0e9, #ffc8dd);
      font-family: 'Poppins', sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
      text-align: center;
      overflow-x: hidden;
    }
    h1 {
      margin-top: 30px;
      color: #ff69b4;
      font-size: 3em;
      animation: fadeIn 2s ease;
    }
    p {
      margin: 20px;
      font-size: 1.5em;
      color: #555;
      animation: fadeIn 3s ease;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin: 30px 0;
      gap: 20px;
      animation: fadeIn 4s ease;
    }
    .gallery img {
      width: 200px;
      height: 250px;
      object-fit: cover;
      border-radius: 20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      transition: transform 0.3s;
    }
    .gallery img:hover {
      transform: scale(1.1);
    }
    button {
      background: #ff69b4;
      border: none;
      padding: 12px 25px;
      font-size: 1.2em;
      color: white;
      border-radius: 30px;
      cursor: pointer;
      margin: 30px;
      transition: background 0.3s;
    }
    button:hover {
      background: #ff4f91;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px);}
      to { opacity: 1; transform: translateY(0);}
    }
  </style>
</head>
<body>

  <h1>Happy Birthday, Gorgeous! 🎉</h1>
  <p>You make the world a brighter place just by being in it. I hope today is as amazing as you are! 💖</p>

  <div class="gallery">
    <!-- Replace src with her photo links -->
    <img src="images/pic1.jpg" alt="Her Smile">
    <img src="images/pic2.jpg" alt="Her Laugh">
    <img src="images/pic3.jpg" alt="Her Eyes">
    <img src="images/pic4.jpg" alt="Her Vibe">
  </div>

  <button onclick="alert('Wishing you all the happiness you deserve 💖')">Click for a Secret!</button>

</body>
</html>
