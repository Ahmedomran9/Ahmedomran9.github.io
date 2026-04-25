<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>سياسات وأحكام المندوب</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: "Cairo", sans-serif;
      margin: 0;
      background: #f5f6fa;
      color: #333;
      line-height: 1.8;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 16px;
    }

    h1 {
      text-align: center;
      color: #ff6b00;
      font-size: 28px;
      margin-bottom: 10px;
    }

    h2 {
      font-size: 20px;
      margin-top: 20px;
      border-right: 4px solid #ff6b00;
      padding-right: 10px;
    }

    .card {
      background: #fff;
      padding: 16px;
      margin: 12px 0;
      border-radius: 12px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      transition: 0.2s;
    }

    .card:hover {
      transform: translateY(-2px);
    }

    .warning { border-right: 5px solid #f39c12; }
    .danger { border-right: 5px solid #e74c3c; }
    .success { border-right: 5px solid #2ecc71; }

    ul {
      padding-right: 18px;
      margin: 0;
    }

    li {
      margin-bottom: 6px;
    }

    footer {
      text-align: center;
      margin-top: 30px;
      color: #777;
      font-size: 13px;
    }

    .highlight {
      color: #ff6b00;
      font-weight: bold;
    }

    /* 📱 Mobile */
    @media (max-width: 600px) {
      h1 {
        font-size: 22px;
      }

      h2 {
        font-size: 18px;
      }

      .card {
        padding: 12px;
      }
    }

    /* 💻 Tablet */
    @media (min-width: 601px) and (max-width: 992px) {
      .container {
        padding: 20px;
      }
    }

    /* 🖥 Desktop grid layout */
    @media (min-width: 993px) {
      .grid {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 15px;
      }

      .full {
        grid-column: span 2;
      }
    }

  </style>
</head>

<body>

<div class="container">

  <h1>🚚 سياسات وأحكام المندوب</h1>

  <div class="card full">
    <p>
      مرحبًا بك في فريق <span class="highlight">مندوب</span> 👋  
      لضمان أفضل خدمة وتنظيم العمل، تم وضع هذه السياسات.
    </p>
  </div>

  <div class="grid">

    <div class="card success">
      <h2>✅ القواعد الأساسية</h2>
      <ul>
        <li>الالتزام بالمواعيد</li>
        <li>احترام العملاء</li>
        <li>الحفاظ على الطلب</li>
        <li>عدم الإلغاء بدون سبب</li>
        <li>عدم تحصيل مبالغ إضافية</li>
      </ul>
    </div>

    <div class="card warning">
      <h2>⚠️ مخالفات بسيطة</h2>
      <ul>
        <li>تأخير بسيط</li>
        <li>عدم الرد</li>
        <li>سوء تعامل بسيط</li>
      </ul>
      <p>💰 20 - 50 جنيه</p>
    </div>

    <div class="card warning">
      <h2>⚠️ مخالفات متوسطة</h2>
      <ul>
        <li>تأخير كبير</li>
        <li>إلغاء بدون إذن</li>
        <li>عدم الالتزام بالتعليمات</li>
      </ul>
      <p>💰 50 - 150 جنيه</p>
    </div>

    <div class="card danger">
      <h2>⛔ مخالفات جسيمة</h2>
      <ul>
        <li>سلوك غير لائق</li>
        <li>تلاعب في الأسعار</li>
        <li>عدم تسليم الطلب</li>
      </ul>
      <p>💰 حتى 300 جنيه أو إيقاف</p>
    </div>

    <div class="card danger">
      <h2>🚫 الإيقاف النهائي</h2>
      <ul>
        <li>سرقة أو تلاعب</li>
        <li>شكاوى متكررة</li>
        <li>سلوك سيء</li>
        <li>اتفاق خارج النظام</li>
      </ul>
    </div>

    <div class="card">
      <h2>💰 نظام الخصومات</h2>
      <ul>
        <li>الخصم من الرصيد</li>
        <li>توضيح السبب</li>
        <li>اعتراض خلال 24 ساعة</li>
      </ul>
    </div>

    <div class="card full">
      <h2>⭐ التقييم</h2>
      <p>الالتزام + السرعة + رضا العملاء = فرص وأرباح أعلى 💰</p>
    </div>

  </div>

  <footer>
    © 2026 مندوب
  </footer>

</div>

</body>
</html>
