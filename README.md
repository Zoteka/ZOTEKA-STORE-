<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>ZOTEKA STORE</title>
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      background-color: #f4f6f9;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      color: white;
      padding: 30px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      margin-top: 10px;
      font-size: 1.1rem;
    }

    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
    }

    .card {
      background-color: white;
      border-radius: 15px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.07);
      padding: 25px;
      transition: 0.3s ease;
      text-align: center;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 12px 25px rgba(0, 0, 0, 0.15);
    }

    .card h3 {
      color: #203a43;
      font-size: 1.3rem;
      margin-bottom: 10px;
    }

    .card p {
      font-size: 1rem;
      line-height: 1.5;
      color: #555;
    }

    .contact {
      text-align: center;
      margin: 40px 0 20px;
    }

    .contact a {
      background-color: #0088cc;
      color: white;
      padding: 14px 28px;
      border-radius: 8px;
      text-decoration: none;
      font-size: 1.1rem;
      transition: background 0.3s ease;
    }

    .contact a:hover {
      background-color: #0072b1;
    }

    footer {
      background-color: #2c5364;
      color: white;
      text-align: center;
      padding: 15px 10px;
      font-size: 0.9rem;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>🌐 ZOTEKA STORE</h1>
    <p>متجرك الذكي لكل خدمات الشحن والتكنولوجيا والتوثيقات</p>
  </header>

  <section class="container">
    <div class="card">
      <h3>💻 خدمات التكنولوجيا</h3>
      <p>برمجة، تصميم مواقع، حلول رقمية، دعم فني متكامل</p>
    </div>
    <div class="card">
      <h3>📶 شحن إنترنت</h3>
      <p>اتصالات، فودافون، أورنج، WE – شحن فوري وسريع</p>
    </div>
    <div class="card">
      <h3>🎮 شحن ألعاب</h3>
      <p>ببجي، فري فاير، كول أوف ديوتي، ريلز، وأكثر</p>
    </div>
    <div class="card">
      <h3>🏛️ خدمات حكومية</h3>
      <p>تجديد رخص، مخالفات، شهادات، دعم إلكتروني سريع</p>
    </div>
    <div class="card">
      <h3>📄 توثيقات</h3>
      <p>توثيق حسابات، إثبات ملكية، أوراق رسمية وموثوقة</p>
    </div>
    <div class="card">
      <h3>📱 رصيد وباقات</h3>
      <p>شحن رصيد وباقات لجميع الشبكات بأفضل الأسعار</p>
    </div>
    <div class="card">
      <h3>🎓 منصات مدرسين</h3>
      <p>شحن منصات تعليمية مثل: نجوى، نفهم، إدراك وغيرهم</p>
    </div>
  </section>

  <div class="contact">
    <a href="https://t.me/ZOTEKA" target="_blank">💬 تواصل مع مدير الموقع على تيليجرام</a>
  </div>

  <footer>
    &copy; 2025 ZOTEKA STORE | جميع الحقوق محفوظة
  </footer>

</body>
</html>
