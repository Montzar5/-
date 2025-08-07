<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>خدمات TikTok</title>
  <style>
    body {
      margin: 0;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f2f2f2;
      color: #1c1c1e;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }
    header {
      background: linear-gradient(90deg, #ff0050, #ff4081, #e91e63);
      padding: 20px;
      text-align: center;
      color: white;
    }
    header h1 {
      margin: 0;
      font-weight: 500;
      font-size: 1.8rem;
    }
    header p {
      margin: 5px 0 0;
      opacity: 0.7;
      font-size: 1.1rem;
    }
    main {
      flex: 1;
      display: flex;
      gap: 20px;
      padding: 20px;
      justify-content: center;
      flex-wrap: wrap;
    }
    .card {
      background: linear-gradient(135deg, #667eea, #764ba2);
      border-radius: 12px;
      padding: 20px;
      width: 260px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      color: white;
      display: flex;
      flex-direction: column;
      align-items: center;
      cursor: pointer;
      transition: transform 0.15s ease;
      user-select: none;
      text-align: center;
    }
    .card.likes {
      background: linear-gradient(135deg, #f093fb, #f5576c);
    }
    .card:hover {
      transform: scale(1.05);
    }
    .card svg {
      width: 40px;
      height: 40px;
      margin-bottom: 12px;
      stroke: white;
      stroke-width: 2;
      fill: none;
    }
    .card h2 {
      margin: 10px 0 6px;
      font-weight: 600;
      font-size: 1.3rem;
    }
    .card p {
      font-size: 0.9rem;
      opacity: 0.8;
      margin-bottom: 12px;
    }
    footer {
      height: 60px;
      background: white;
      box-shadow: 0 -2px 8px rgba(0,0,0,0.1);
      display: flex;
      justify-content: center;
      align-items: center;
      font-weight: 500;
      color: #ff0050;
      font-size: 1.1rem;
    }
    /* شعار تيك توك */
    .tiktok-logo {
      width: 80px;
      height: 80px;
      margin: 0 auto 12px;
    }
  </style>
</head>
<body>
  <header>
    <img class="tiktok-logo" src="https://upload.wikimedia.org/wikipedia/commons/0/09/TikTok_logo.svg" alt="TikTok Logo" />
    <h1>خدمات TikTok</h1>
    <p>اختر الخدمة التي تريدها</p>
  </header>
  <main>
    <a class="card" href="https://t.me/your_bot" target="_blank" rel="noopener noreferrer">
      <svg viewBox="0 0 24 24"><circle cx="9" cy="7" r="4"/><path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2"/><path d="M22 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg>
      <h2>متابعين</h2>
      <p>احصل على متابعين حقيقيين لحسابك</p>
      <div>اختر</div>
    </a>
    <a class="card likes" href="https://t.me/your_bot" target="_blank" rel="noopener noreferrer">
      <svg viewBox="0 0 24 24"><path d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z"/></svg>
      <h2>إعجابات</h2>
      <p>زيد إعجابات فيديوهاتك</p>
      <div>اختر</div>
    </a>
  </main>
  <footer>
    خدمات TikTok
  </footer>
</body>
</html>
