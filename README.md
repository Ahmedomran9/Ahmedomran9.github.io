<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>سياسات وأحكام المندوب</title>

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

    /* 🖥️ منع عرض المحتوى على الكمبيوتر */
    @media (min-width: 768px) {
      .container {
        display: none !important;
      }
      .desktop-warning {
        display: flex !important;
      }
    }

    /* رسالة التنبيه لمستخدمي الكمبيوتر */
    .desktop-warning {
      display: none;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
      padding: 20px;
      background-color: #fff;
    }

    .desktop-warning img {
      max-width: 150px;
      margin-bottom: 20px;
    }

    .container {
      max-width: 100%;
      margin: auto;
      padding: 16px;
    }

    /* باقي التنسيقات الخاصة بك مع تحسينها للموبايل */
    h1 {
      text-align: center;
      color: #ff6b00;
      font-size: 22px;
      margin-bottom: 10px;
    }

    h2 {
      font-size: 18px;
      margin-top: 15px;
      border-right: 4px solid #ff6b00;
      padding-right: 10px;
    }

    .card {
      background: #fff;
      padding: 14px;
      margin: 10px 0;
      border-radius: 12px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    }

    .warning { border-right: 5px solid #f39c12; }
    .danger { border-right: 5px solid #e74c3c; }
    .success { border-right: 5px solid #2ecc71; }

    ul { padding-right: 18px; margin: 0; }
    li { margin-bottom: 6px; font-size: 14px; }

    footer {
      text-align: center;
      margin-top: 30px;
      padding-bottom: 20px;
      color: #777;
      font-size: 12px;
    }

    .highlight { color: #ff6b00; font-weight: bold; }

  </style>
</head>

<body>

<div class="desktop-warning">
  <div style="font-size: 50px;">📱</div>
  <h2 style="border: none;">عذراً، هذه الصفحة متاحة فقط عبر تطبيق "مندوب"</h2>
  <p>يرجى فتح الرابط من خلال الهاتف المحمول لتتمكن من قراءة اللوائح.</p>
</div>

<div class="container">
  <h1>🚚 اللوائح الخاصة بالمناديب</h1>

  <div class="card">
    <p>
      مرحبًا بك في فريق <span class="highlight">مندوب</span> 👋<br>
      لضمان أفضل خدمة وتنظيم العمل، يرجى الالتزام بالسياسات التالية.
    </p>
  </div>

  <div class="card success">
    <h2>✅ القواعد الأساسية</h2>
    <ul>
      <li>الالتزام بالمواعيد</li>
      <li>احترام العملاء</li>
      <li>الحفاظ على سلامة الطلبات</li>
      <li>عدم تحصيل مبالغ إضافية</li>
    </ul>
  </div>

  <div class="card danger">
    <h2>⛔ مخالفات جسيمة</h2>
    <ul>
      <li>سلوك غير لائق مع العميل</li>
      <li>التلاعب في أسعار التوصيل</li>
      <li>عدم تسليم الطلب بعد استلامه</li>
    </ul>
    <p class="highlight">💰 الخصم يصل لـ 300 جنيه أو الإيقاف</p>
  </div>

  <div class="card danger">
    <h2>🚫 التلاعب في الطلبات</h2>
    <ul>
      <li>تعطيل أو تجاهل الطلب بعد القبول</li>
    </ul>
    <p>⚠️ الحد الأقصى للتجاهل: <span class="highlight">5 مرات فقط</span></p>
    <p style="color: red; font-weight: bold;">بعد ذلك يتم الإيقاف المباشر.</p>
  </div>

  <div class="card">
    <h2>💰 نظام الخصومات والتقييم</h2>
    <p>الالتزام + السرعة = أرباح أعلى وفرص تمييز في نظام مندوب 🏆</p>
  </div>

  <footer>
    © 2026 مندوب - جميع الحقوق محفوظة
  </footer>
</div>

<script>
  // منع عرض الصفحة إذا كان المستخدم يستخدم متصفح كمبيوتر عن طريق الـ User Agent
  function checkDevice() {
    const isMobile = /iPhone|iPad|iPod|Android/i.test(navigator.userAgent);
    if (!isMobile && window.innerWidth > 768) {
        // يمكننا ترك الـ CSS يتعامل مع الإخفاء، أو إعادة توجيهه لموقعك
        // window.location.href = "https://ahmedomran9.github.io"; 
    }
  }
  window.onload = checkDevice;
</script>

</body>
</html><!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>سياسات وأحكام المندوب</title>

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

    /* 🖥️ منع عرض المحتوى على الكمبيوتر */
    @media (min-width: 768px) {
      .container {
        display: none !important;
      }
      .desktop-warning {
        display: flex !important;
      }
    }

    /* رسالة التنبيه لمستخدمي الكمبيوتر */
    .desktop-warning {
      display: none;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
      padding: 20px;
      background-color: #fff;
    }

    .desktop-warning img {
      max-width: 150px;
      margin-bottom: 20px;
    }

    .container {
      max-width: 100%;
      margin: auto;
      padding: 16px;
    }

    /* باقي التنسيقات الخاصة بك مع تحسينها للموبايل */
    h1 {
      text-align: center;
      color: #ff6b00;
      font-size: 22px;
      margin-bottom: 10px;
    }

    h2 {
      font-size: 18px;
      margin-top: 15px;
      border-right: 4px solid #ff6b00;
      padding-right: 10px;
    }

    .card {
      background: #fff;
      padding: 14px;
      margin: 10px 0;
      border-radius: 12px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    }

    .warning { border-right: 5px solid #f39c12; }
    .danger { border-right: 5px solid #e74c3c; }
    .success { border-right: 5px solid #2ecc71; }

    ul { padding-right: 18px; margin: 0; }
    li { margin-bottom: 6px; font-size: 14px; }

    footer {
      text-align: center;
      margin-top: 30px;
      padding-bottom: 20px;
      color: #777;
      font-size: 12px;
    }

    .highlight { color: #ff6b00; font-weight: bold; }

  </style>
</head>

<body>

<div class="desktop-warning">
  <div style="font-size: 50px;">📱</div>
  <h2 style="border: none;">عذراً، هذه الصفحة متاحة فقط عبر تطبيق "مندوب"</h2>
  <p>يرجى فتح الرابط من خلال الهاتف المحمول لتتمكن من قراءة اللوائح.</p>
</div>

<div class="container">
  <h1>🚚 اللوائح الخاصة بالمناديب</h1>

  <div class="card">
    <p>
      مرحبًا بك في فريق <span class="highlight">مندوب</span> 👋<br>
      لضمان أفضل خدمة وتنظيم العمل، يرجى الالتزام بالسياسات التالية.
    </p>
  </div>

  <div class="card success">
    <h2>✅ القواعد الأساسية</h2>
    <ul>
      <li>الالتزام بالمواعيد</li>
      <li>احترام العملاء</li>
      <li>الحفاظ على سلامة الطلبات</li>
      <li>عدم تحصيل مبالغ إضافية</li>
    </ul>
  </div>

  <div class="card danger">
    <h2>⛔ مخالفات جسيمة</h2>
    <ul>
      <li>سلوك غير لائق مع العميل</li>
      <li>التلاعب في أسعار التوصيل</li>
      <li>عدم تسليم الطلب بعد استلامه</li>
    </ul>
    <p class="highlight">💰 الخصم يصل لـ 300 جنيه أو الإيقاف</p>
  </div>

  <div class="card danger">
    <h2>🚫 التلاعب في الطلبات</h2>
    <ul>
      <li>تعطيل أو تجاهل الطلب بعد القبول</li>
    </ul>
    <p>⚠️ الحد الأقصى للتجاهل: <span class="highlight">5 مرات فقط</span></p>
    <p style="color: red; font-weight: bold;">بعد ذلك يتم الإيقاف المباشر.</p>
  </div>

  <div class="card">
    <h2>💰 نظام الخصومات والتقييم</h2>
    <p>الالتزام + السرعة = أرباح أعلى وفرص تمييز في نظام مندوب 🏆</p>
  </div>

  <footer>
    © 2026 مندوب - جميع الحقوق محفوظة
  </footer>
</div>

<script>
  // منع عرض الصفحة إذا كان المستخدم يستخدم متصفح كمبيوتر عن طريق الـ User Agent
  function checkDevice() {
    const isMobile = /iPhone|iPad|iPod|Android/i.test(navigator.userAgent);
    if (!isMobile && window.innerWidth > 768) {
        // يمكننا ترك الـ CSS يتعامل مع الإخفاء، أو إعادة توجيهه لموقعك
        // window.location.href = "https://ahmedomran9.github.io"; 
    }
  }
  window.onload = checkDevice;
</script>

</body>
</html>
