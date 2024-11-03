<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>软件下载</title>
  <style>
    body {
      background-color: white;
      margin: 0;
      padding: 0;
    }

  .header {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 200px;
      background-color: #333;
    }

  .header img {
      max-width: 100%;
      max-height: 100%;
      position: relative;
    }

  .header img::after {
      content: "Your Software Title Here";
      color: white;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 18px;
      @media (max-width: 480px) {
        font-size: 14px;
      }
    }

    h1 {
      color: white;
      font-size: 36px;
      text-align: center;
      @media (max-width: 480px) {
        font-size: 24px;
      }
    }

  .download-section {
      text-align: center;
      margin-top: 50px;
    }

  .download-button {
      background-color: blue;
      color: white;
      padding: 15px 30px;
      text-decoration: none;
      transition: transform 0.3s ease;
      @media (max-width: 480px) {
        padding: 10px 20px;
      }
    }

  .download-button:hover {
      transform: scale(1.3);
    }

  .download-button:active {
      transform: scale(0.8);
    }
  </style>
</head>

<body>
  <div class="header">
    <img src="your_image.jpg" alt="软件图标">
  </div>
  <h1>热门软件下载</h1>
  <div class="download-section">
    <h2>软件名称：高效办公助手</h2>
    <p>描述：一款功能强大的办公软件，提升你的工作效率。</p>
    <a href="#" class="download-button">立即下载</a>
  </div>
</body>

</html>
