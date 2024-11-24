<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>For Tulika</title>
  <style>
    /* Global Styles */
    body {
      margin: 0;
      padding: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(145deg, #1a1a1a, #000);
      color: white;
      overflow-x: hidden;
    }

    /* Main Container */
    .container {
      text-align: center;
      padding: 30px;
    }

    /* Heading */
    h1 {
      font-size: 3.5em;
      color: #ff6f91;
      text-shadow: 2px 2px 10px #ff4081;
      margin-bottom: 20px;
      animation: fadeInDown 2s ease;
    }

    /* Paragraph Text */
    p {
      font-size: 1.5em;
      line-height: 1.8;
      color: #e0e0e0;
      margin-bottom: 30px;
      animation: fadeIn 3s ease-in-out;
    }

    /* Image Section */
    .image-section {
      position: relative;
      width: 80%;
      max-width: 600px;
      margin: 30px auto;
      border-radius: 15px;
      overflow: hidden;
      box-shadow: 0 8px 30px rgba(255, 105, 180, 0.5);
      animation: zoomIn 1.5s ease;
    }

    .image-section img {
      width: 100%;
      display: block;
    }

    /* Overlaid Text */
    .image-text {
      position: absolute;
      bottom: 20px;
      left: 50%;
      transform: translateX(-50%);
      background-color: rgba(0, 0, 0, 0.6);
      color: white;
      padding: 10px 20px;
      border-radius: 20px;
      font-size: 1.3em;
      animation: fadeInUp 2s ease;
    }

    /* Button */
    .button {
      background-color: #ff4081;
      border: none;
      color: white;
      padding: 15px 30px;
      text-align: center;
      font-size: 1.2em;
      margin-top: 20px;
      cursor: pointer;
      border-radius: 30px;
      box-shadow: 0px 4px 10px rgba(255, 64, 129, 0.6);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      animation: fadeInUp 2s ease;
    }

    .button:hover {
      transform: scale(1.1);
      box-shadow: 0px 6px 15px rgba(255, 64, 129, 0.8);
    }

    /* Footer */
    .footer {
      margin-top: 40px;
      font-size: 0.9em;
      color: #bdbdbd;
    }

    /* Keyframes */
    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    @keyframes fadeInDown {
      from {
        transform: translateY(-20px);
        opacity: 0;
      }
      to {
        transform: translateY(0);
        opacity: 1;
      }
    }

    @keyframes fadeInUp {
      from {
        transform: translateY(20px);
        opacity: 0;
      }
      to {
        transform: translateY(0);
        opacity: 1;
      }
    }

    @keyframes zoomIn {
      from {
        transform: scale(0.9);
        opacity: 0;
      }
      to {
        transform: scale(1);
        opacity: 1;
      }
    }

    /* Mobile-Only Styles */
    @media only screen and (max-width: 768px) {
      body {
        display: block;
      }
    }

    /* Hide on Desktop */
    @media only screen and (min-width: 769px) {
      body {
        display: none;
      }
    }

  </style>
</head>
<body>
  <div class="container">
    <!-- Heading -->
    <h1>Tulika, Let’s Stay Close</h1>

    <!-- Message -->
    <p>
      You’re one of the most important people in my life. <br>
      I want us to be the best of friends and cherish this bond forever. <br>
      You mean the world to me.
    </p>

    <!-- Image Section -->
    <div class="image-section">
      <img src="https://media.giphy.com/media/l0HUpt2s9Pclgt9Vm/giphy.gif" alt="Friendship Gif">
      <div class="image-text">Forever Best Friends ❤️</div>
    </div>

    <!-- Button -->
    <button class="button" onclick="showMessage()">Stay With Me</button>

    <!-- Footer -->
    <div class="footer">Designed with love for Tulika</div>
  </div>

  <!-- JavaScript to handle Desktop Access -->
  <script>
    if (window.innerWidth > 768) {
      alert("Please use a mobile device to view this website.");
    }

    function showMessage() {
      alert("Thank you, Tulika! Let's always be close friends ❤️.");
    }
  </script>
</body>
</html>
