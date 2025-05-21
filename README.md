
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <title>Natalka</title>
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&display=swap" rel="stylesheet">
  <style>
    body {
      background: linear-gradient(to bottom, #ffe6ec, #ffffff);
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 0;
      padding: 0;
    }

   h2.title {
      font-family: 'Dancing Script', cursive;
      font-size: 48px;
      color: darkred;
      margin-top: 60px;
      margin-bottom: 10px;
    }

   p.subtitle {
      font-size: 18px;
      color: #555;
      margin: 0 auto 40px auto;
      max-width: 600px;
    }
  </style>
</head>
<body>

  <h2 class="title">Najpiękniejsza na świecie</h2>
  <p class="subtitle">Bo piękno nie tylko się widzi – piękno się czuje.</p>

</body>
</html>

  <section>
    <h2>Magia spojrzenia</h2>
    <p>Zachwyca nie tylko urodą, ale i duszą 🌸</p>
    <div class="gallery">
<img src="https://github.com/user-attachments/assets/0e1a787f-75dc-4751-bcdf-913c413f18f7" alt="zdjecie1" />

<img src="https://github.com/user-attachments/assets/1c48acda-a26e-46c3-afc1-305d58756a1a" alt="zdjecie1" />

   = </div>
    <p class="quote">„Kiedy patrzę na Ciebie, świat staje się piękniejszy.”</p>
  </section>
<div class="poem">
      Czasem wystarczy jedno spojrzenie,<br>
      by serce zadrżało w zachwycie.<br>
      Gdy jesteś obok – świat jaśnieje,<br>
      a każda chwila nabiera życia.
    </div>



   Za każdym razem kiedy Cię widzę,<br>
      przypominam sobie kiedy pierwszy raz złapałem Cię za rękę,<br>
      kiedy pierwszy raz Cię pocałowałem,<br>
      nawet naszą pierwszą rozmowę.<br><br>
      Jesteś dla mnie najważniejsza – nawet nie wiesz jak bardzo.<br>
      Chciałbym Cię znowu zobaczyć...<br>
      Jesteś najcudowniejsza i nie chcę Cię stracić, mimo wszystko.
    </div>
  </section>

  <footer>
    
  </footer>
  <div class="timeline">

  <div class="timeline-item left">
    <div class="timeline-content">
      <h3>Pierwsza rozmowa</h3>
      <p>Pamiętam każdy szczegół – Twoje słowa, Twój uśmiech, Twoje spojrzenie...</p>
    </div>
  </div>

  <div class="timeline-item right">
    <div class="timeline-content">
      <h3>Pierwszy spacer</h3>
      <p>To wtedy poczułem, że jesteś kimś wyjątkowym, niepowtarzalnym.</p>
    </div>
  </div>

  <div class="timeline-item left">
    <div class="timeline-content">
      <h3>Pierwszy pocałunek</h3>
      <p>Moment, który zatrzymał czas... byłeś tylko Ty i ja.</p>
    </div>
  </div>

  <div class="timeline-item right">
    <div class="timeline-content">
      <h3>Nasze wspólne chwile</h3>
      <p>Plany, rozmowy, śmiech i wszystko to, co tworzymy razem ❤️</p>
    </div>
  </div>

</div>
&copy; 2025 — Stworzona z sercem 💖

<script>
  setInterval(() => {
    const heart = document.createElement("div");
    heart.innerText = "❤️";
    heart.style.position = "fixed";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.top = "-2vh";
    heart.style.fontSize = "24px";
    heart.style.animation = "fall 3s linear forwards";
    document.body.appendChild(heart);
    setTimeout(() => heart.remove(), 3000);
  }, 300);

</script>
<style>
  @keyframes fall {
    to {
      transform: translateY(100vh);
      opacity: 0;
    }
  }
</style>
