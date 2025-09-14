<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>حساباتي</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background: #000;
      color: white;
      padding: 30px;
      position: relative;
    }
    /* أشكال هندسية ذهبية كظل */
    body::before {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: radial-gradient(circle at 20% 20%, rgba(255,215,0,0.2), transparent 40%),
                  radial-gradient(circle at 80% 30%, rgba(255,215,0,0.15), transparent 40%),
                  radial-gradient(circle at 50% 80%, rgba(255,215,0,0.1), transparent 40%);
      z-index: 0;
    }
    .content {
      position: relative;
      z-index: 1;
    }
    .top-right {
      position: absolute;
      top: 10px;
      right: 15px;
      text-align: right;
      font-size: 14px;
      line-height: 1.4;
    }
    .top-left {
      position: absolute;
      top: 10px;
      left: 15px;
      text-align: left;
      font-size: 14px;
      line-height: 1.4;
    }
    .name {
      font-size: 16px;
      font-weight: bold;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
      gap: 20px;
      margin-top: 100px;
    }
    .icon-btn {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      background: #111;
      border-radius: 20px;
      padding: 20px;
      color: white;
      text-decoration: none;
      font-size: 14px;
      transition: transform 0.2s, background 0.2s;
    }
    .icon-btn:hover {
      background: #333;
      transform: scale(1.05);
    }
    .icon-btn img {
      width: 50px;
      height: 50px;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <div class="top-right">
    <div class="name">مايكل توما بطرس</div>
    <div>مصنع ننكي لصناعة الالمنيوم</div>
    <div>العراق زاخو طريق ابراهيم الخليل</div>
  </div>
  <div class="top-left">
    <div class="name">Michael Toma Butrus</div>
    <div>Nenky Factory for Aluminum</div>
    <div>Iraq, Zakho, Ibrahim Al-Khalil Road</div>
  </div>

  <div class="content">
    <h1>Welcome 👋 أهلاً بك</h1>
    <p>هنا كل حساباتي / Here are all my accounts:</p>
    <div class="grid">
      <a class="icon-btn" href="https://wa.me/009647504595067" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp">
        واتساب / WhatsApp
      </a>
      <a class="icon-btn" href="https://weixin.qq.com/" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/1384/1384029.png" alt="WeChat">
        ويشات / WeChat
      </a>
      <a class="icon-btn" href="https://facebook.com/michael.albaze" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook">
        فيسبوك / Facebook
      </a>
      <a class="icon-btn" href="https://instagram.com/michael.potros" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" alt="Instagram">
        إنستغرام / Instagram
      </a>
      <a class="icon-btn" href="https://tiktok.com/@michaeltoma36" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/3046/3046121.png" alt="TikTok">
        تيك توك / TikTok
      </a>
      <a class="icon-btn" href="https://www.google.com/maps?q=37.1385253,42.6513713" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/684/684908.png" alt="Maps">
        العنوان / Address
      </a>
      <a class="icon-btn" href="mailto:michael.potros@gmail.com" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" alt="Email">
        ايميل / Email
      </a>
    </div>
  </div>
</body>
</html>