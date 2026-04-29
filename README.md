<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>اللوائح الخاصة بالمناديب</title>

  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">

  <style>
    * { box-sizing: border-box; -webkit-tap-highlight-color: transparent; }

    body {
      font-family: "Cairo", sans-serif;
      margin: 0;
      background: #f0f2f5;
      color: #1a1a1a;
      line-height: 1.6;
    }

    /* --- حماية وحجب أجهزة الكمبيوتر --- */
    @media (min-width: 769px) {
      .container { display: none !important; }
      .no-desktop {
        display: flex !important;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        height: 100vh;
        background: #fff;
        text-align: center;
      }
    }

    .no-desktop { display: none; padding: 30px; }

    /* --- تنسيق الموبايل --- */
    .container {
      max-width: 100%;
      margin: 0 auto;
      padding: 12px;
    }

    header {
      text-align: center;
      padding: 20px 0;
      background: #2c3e50;
      border-radius: 0 0 25px 25px;
      margin-bottom: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    header h1 {
      color: #fff;
      font-size: 20px;
      margin: 10px 0 0;
    }

    .card {
      background: #fff;
      padding: 15px;
      margin-bottom: 12px;
      border-radius: 15px;
      border-right: 5px solid #bdc3c7;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    }

    /* ألوان الحالة */
    .success { border-right-color: #27ae60; }
    .warning { border-right-color: #f39c12; }
    .danger { border-right-color: #e74c3c; }

    h2 {
      font-size: 17px;
      margin: 0 0 10px 0;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    ul { padding-right: 20px; margin: 0; }
    li { margin-bottom: 5px; font-size: 14px; }

    .price-tag {
      display: inline-block;
      background: #fdf2f2;
      color: #e74c3c;
      padding: 2px 10px;
      border-radius: 20px;
      font-weight: bold;
      font-size: 13px;
      margin-top: 8px;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 12px;
      color: #7f8c8d;
    }

    .highlight { color: #e67e22; font-weight: bold; }
  </style>
</head>
<body>

  <div class="no-desktop">
    <div style="font-size: 60px;">🚫</div>
    <h2>هذه الصفحة مخصصة للهواتف فقط</h2>
    <p>يرجى فتح الرابط من داخل تطبيق "مندوب" للمتابعة.</p>
  </div>

  <div class="container">
    <header>
      <div style="font-size: 40px;">📜</div>
      <h1>اللوائح الخاصة بالمناديب</h1>
    </header>

    <div class="card" style="border-right: none; text-align: center;">
      <p>مرحباً بك في فريق <span class="highlight">مندوب</span> 👋<br> لضمان جودة العمل، يرجى قراءة اللوائح التالية بعناية.</p>
    </div>

    <div class="card success">
      <h2>✅ القواعد الذهبية</h2>
      <ul>
        <li>الالتزام التام بمواعيد التسليم.</li>
        <li>حسن المظهر والتعامل مع العملاء.</li>
        <li>الحفاظ على سلامة الطلب (الأمانة).</li>
      </ul>
    </div>

    <div class="card warning">
      <h2>⚠️ مخالفات متوسطة</h2>
      <ul>
        <li>التأخر غير المبرر عن العميل.</li>
        <li>عدم الرد على اتصالات الدعم الفني.</li>
      </ul>
      <span class="price-tag">خصم: 50 - 150 جنيه</span>
    </div>

    <div class="card danger">
      <h2>⛔ مخالفات جسيمة</h2>
      <ul>
        <li>سوء التعامل مع العملاء أو المتاجر.</li>
        <li>التلاعب في مبالغ التوصيل المقررة.</li>
      </ul>
      <span class="price-tag">خصم: حتى 300 جنيه</span>
    </div>

    <div class="card danger">
      <h2>🚫 الإيقاف النهائي</h2>
      <ul>
        <li>تكرار تجاهل الطلبات (أكثر من 5 مرات).</li>
        <li>القيام بعمليات تلاعب أو سرقة.</li>
        <li>الاتفاق مع العملاء خارج نظام "مندوب".</li>
      </ul>
    </div>

    <div class="card">
      <h2>⭐ نصيحة للنجاح</h2>
      <p style="font-size: 14px;">التقييم العالي يعني أولوية في استلام الطلبات وزيادة في الدخل اليومي. التزم تربح أكثر 💰</p>
    </div>

    <footer>
      © 2026 نظام مندوب - جميع الحقوق محفوظة
    </footer>
  </div>

  <script>
    // منع السحب للأسفل لتحديث الصفحة في بعض المتصفحات (Pull-to-refresh)
    document.body.style.overscrollBehavior = 'contain';
  </script>
</body>
</html>
