<!DOCTYPE html>
<html lang="kk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Тойға шақыру</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(rgba(255,255,255,0.3), rgba(255,255,255,0.3)), url('https://upload.wikimedia.org/wikipedia/commons/1/1b/Kiiz_uy.jpg') no-repeat center center fixed;
      background-size: cover;
      color: white;
      text-align: center;
    }
    .overlay {
      background: rgba(0, 0, 0, 0.5);
      padding: 60px 20px;
      min-height: 100vh;
    }
    h1 {
      font-size: 4em;
      margin-bottom: 0.3em;
    }
    .subtitle {
      font-size: 1.5em;
      margin-bottom: 2em;
    }
    .buttons a {
      display: inline-block;
      margin: 10px;
      padding: 15px 30px;
      border-radius: 30px;
      background: black;
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    .buttons a:hover {
      background: white;
      color: black;
    }
    .info-section {
      background: rgba(255, 255, 255, 0.1);
      margin: 40px auto;
      max-width: 800px;
      padding: 30px;
      border-radius: 10px;
    }
    .owners, .guests {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .footer {
      margin-top: 60px;
      font-size: 1.3em;
    }
    .long-text {
      margin-top: 40px;
      font-size: 1.2em;
      line-height: 1.8em;
      text-align: justify;
      max-width: 900px;
      margin-left: auto;
      margin-right: auto;
    }
    .gallery {
      margin-top: 60px;
    }
    .gallery h2 {
      margin-bottom: 20px;
    }
    .gallery-images {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .gallery-images img {
      width: 100%;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    }
    #countdown {
      font-size: 2em;
      margin-top: 20px;
      font-weight: bold;
    }
    .map-container {
      margin-top: 30px;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    iframe {
      border: none;
      border-radius: 10px;
      width: 90%;
      max-width: 800px;
      height: 400px;
    }
    .qr-code {
      margin-top: 20px;
    }
    .instagram-section {
      margin-top: 60px;
    }
    .instagram-section a {
      color: white;
      font-size: 1.2em;
      text-decoration: none;
    }
    .instagram-section img {
      width: 40px;
      vertical-align: middle;
      margin-right: 10px;
    }
  </style>
</head>
<body>
  <div class="overlay">
    <h1>Тәтті сәттерге бірге жиналайық!</h1>
    <p class="subtitle">Құрметті біздің достарымыз, сіздерді өзіміздің кезекті жеребеміздің қадірлі қонағы болуға шақырамыз!</p>

    <div id="countdown">Таймер жүктелуде...</div>

    <div class="buttons">
      <a href="#info">Көбірек ақпарат</a>
      <a href="#owners">Той иелері</a>
      <a href="#guests">Қонақтар</a>
      <a href="#gallery">Суреттер</a>
      <a href="#instagram">Instagram</a>
    </div>

    <div id="info" class="info-section">
      <h2>Ақпарат</h2>
      <p><strong>Күні:</strong> 21 маусым 2025</p>
      <p><strong>Уақыты:</strong> 19:00 жергілікті уақыт</p>
      <p><strong>Өтетін орны:</strong> Жерұйық көшесі 8, Шалқар қаласы, Ақтөбе облысы</p>
      <div class="map-container">
        <iframe src="https://www.google.com/maps?q=47.824118,59.625917&z=17&output=embed" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        <div class="qr-code">
          <img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https://www.google.com/maps?q=47.824118,59.625917" alt="QR код картаға сілтеме үшін" />
        </div>
      </div>
    </div>

    <div id="owners" class="info-section">
      <h2>Той иелері</h2>
      <div class="owners">
        <p>Әмірбек — Нұргүл</p>
      </div>
    </div>

    <div id="guests" class="info-section">
      <h2>Қонақтар</h2>
      <div class="guests">
        <p>Дәурен — Динара</p>
        <p>Рүстем — Гүлсайран</p>
        <p>Кенжебек — Ақгүл</p>
        <p>Ильяс — Жұлдыз</p>
        <p>Нұрлыбек — Тәттігүл</p>
        <p>Айбек — Таңшолпан</p>
        <p>Алтынбек — Толқын</p>
      </div>
    </div>

    <div class="long-text">
      <p>Бұл кеш – тек қарапайым кездесу емес, бұл — достық пен сыйластықтың, жан жылуы мен шынайы қуаныштың мерекесі. Бір дастарқанда бас қосып, ескі естеліктерді еске алып, жаңа қуаныштармен бөлісетін сәт жақындап қалды. Біз үшін бұл ерекше күннің маңызы зор. Себебі, сіздердің әрқайсыларыңыз біздің өміріміздің бір бөлшегісіздер.</p>
      <p>Бірлік пен береке, қуаныш пен шаттық, шынайы күлкі мен жақсы тілектерге толы бұл кеш баршаңыздың есіңізде қалар ерекше күн боларына сенімдіміз. Қазақы дәстүрмен жайылған дастарқан, ұлттық нақыштағы безендіру, әсерлі ән-күй мен ойын-сауық бағдарламалар сіздерді күтеді.</p>
      <p>Өздеріңізбен емен-жарқын әңгімелесіп, қуанышты бөлісіп, осы тамаша сәттерді бірге өткізгіміз келеді. Қадірлі қонағымыз болып, кештің сәнін келтіріңіз!</p>
    </div>

    <div id="gallery" class="info-section gallery">
      <h2>Суреттер галереясы</h2>
      <div class="gallery-images">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4d/Kazak_wedding_traditional.jpg/800px-Kazak_wedding_traditional.jpg" alt="Той көрінісі 1">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/88/Kazakh_wedding_tradition.jpg/800px-Kazakh_wedding_tradition.jpg" alt="Той көрінісі 2">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/bd/Kazakh_culture_wedding.jpg/800px-Kazakh_culture_wedding.jpg" alt="Той көрінісі 3">
      </div>
    </div>

    <div id="instagram" class="info-section instagram-section">
      <h2>Instagram</h2>
      <a href="https://www.instagram.com/explore/tags/нұргүләмірбекжеребе" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram"> #нұргүләмірбекжеребе хэштегімен инстаграмға сурет видеолар салып бірге көруімізге болады
      </a>
    </div>

    <div class="footer">
      <p>Сізді асыға күтеміз! ❤️</p>
    </div>
  </div>

  <script>
    const countdownElement = document.getElementById("countdown");
    const eventDate = new Date("June 21, 2025 19:00:00").getTime();

    function updateCountdown() {
      const now = new Date().getTime();
      const distance = eventDate - now;

      if (distance < 0) {
        countdownElement.innerHTML = "Той басталып кетті!";
        return;
      }

      const days = Math.floor(distance / (1000 * 60 * 60 * 24));
      const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
      const seconds = Math.floor((distance % (1000 * 60)) / 1000);

      countdownElement.innerHTML = `Қалған уақыт: ${days} күн ${hours} сағат ${minutes} мин ${seconds} сек`;
    }

    updateCountdown();
    setInterval(updateCountdown, 1000);
  </script>
</body>
</html>
