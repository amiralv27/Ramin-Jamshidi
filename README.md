<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>رامین جمشیدی | مربی بدنسازی حرفه‌ای</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Roboto', sans-serif;
      background: linear-gradient(to right, #1c1c1c, #2b2b2b);
      color: #fff;
      scroll-behavior: smooth;
    }
    header {
      text-align: center;
      padding: 60px 20px;
      background: url('https://images.unsplash.com/photo-1599058917216-4f7bb10b8c07?auto=format&fit=crop&w=1350&q=80') no-repeat center/cover;
      position: relative;
    }
    header::after {
      content: '';
      position: absolute;
      top:0; left:0; width:100%; height:100%;
      background: rgba(0,0,0,0.6);
    }
    header h1 {
      position: relative;
      font-size: 3em;
      margin-bottom: 10px;
      z-index: 1;
    }
    header p {
      position: relative;
      font-size: 1.3em;
      z-index: 1;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #111;
      position: sticky;
      top: 0;
      z-index: 10;
    }
    nav a {
      color: #fff;
      padding: 15px 25px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    nav a:hover {
      color: #f0a500;
      transform: scale(1.1);
    }
    section {
      max-width: 1000px;
      margin: 40px auto;
      background: rgba(0,0,0,0.6);
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 0 20px rgba(0,0,0,0.7);
      animation: fadeIn 1s ease-in-out;
    }
    @keyframes fadeIn {
      from {opacity:0; transform: translateY(20px);}
      to {opacity:1; transform: translateY(0);}
    }
    h2 {
      color: #f0a500;
      margin-bottom: 20px;
    }
    ul {
      list-style: inside disc;
    }
    .contact a {
      color: #f0a500;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.3em;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #111;
      margin-top: 40px;
      font-size: 0.9em;
    }
    .services div {
      margin-bottom: 15px;
      transition: transform 0.3s;
    }
    .services div:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>

<header>
  <h1>رامین جمشیدی</h1>
  <p>مربی بدنسازی حرفه‌ای | ساخت مجسمه بدنساز</p>
</header>

<nav>
  <a href="#about">درباره من</a>
  <a href="#services">خدمات</a>
  <a href="#achievements">افتخارات</a>
  <a href="#contact">تماس</a>
</nav>

<section id="about">
  <h2>درباره من</h2>
  <p>بیش از ۲۰ سال تجربه در حوزه بدنسازی و پرورش اندام، با تخصص در طراحی بدن به سبک کلاسیک و ساخت مجسمه‌های بدنساز. هدف من این است که با آموزش تخصصی و برنامه‌ریزی حرفه‌ای، شما را به بهترین نسخه خودتان برسانم.</p>
</section>

<section id="services" class="services">
  <h2>خدمات</h2>
  <div>💪 طراحی برنامه تمرینی شخصی و هدفمند</div>
  <div>🥗 مشاوره تغذیه و رژیم‌های حرفه‌ای</div>
  <div>🏆 مربیگری حضوری و آنلاین</div>
  <div>🎨 ساخت مجسمه بدنساز و طراحی بدن کلاسیک</div>
</section>

<section id="achievements">
  <h2>افتخارات و مسابقات</h2>
  <ul>
    <li>قهرمانی چند دوره پرورش اندام در تهران و کشور (۱۳۸۳-۱۳۸۶)</li>
    <li>نفر سوم مسابقات سعدون کلاسیک (۱۴۰۰)</li>
  </ul>
</section>

<section id="contact">
  <h2>تماس با من</h2>
  <p class="contact">📞 <a href="tel:09383719061">09383719061</a></p>
</section>

<footer>
  © 2025 رامین جمشیدی | همه حقوق محفوظ است
</footer>

</body>
</html>
