<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>SH - Screenshot Tool</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Centered SH Button -->
  <div class="center-container">
    <button id="screenshotBtn">📸<br>SH</button>
  </div>

  <script src="script.js"></script>
</body>
</html>

body {
  margin: 0;
  padding: 0;
  height: 100vh;
  background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
  font-family: "Segoe UI", sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
}

/* Center container to position the button in middle */
.center-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
}

/* Responsive SH Button */
#screenshotBtn {
  background: rgba(255, 255, 255, 0.1);
  backdrop-filter: blur(10px);
  -webkit-backdrop-filter: blur(10px);
  border: 2px solid rgba(255, 255, 255, 0.2);
  color: #ffffff;
  font-weight: bold;
  font-size: 5vw;
  width: 20vw;
  height: 20vw;
  border-radius: 50%;
  cursor: pointer;
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.25);
  transition: all 0.3s ease;
  text-align: center;
  line-height: 1.2;
  max-width: 120px;
  max-height: 120px;
  min-width: 70px;
  min-height: 70px;
}

#screenshotBtn:hover {
  transform: scale(1.1);
  background: rgba(255, 255, 255, 0.2);
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.4);
}
