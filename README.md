<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Anya Isupova — Амбассадор красоты</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap');

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Inter', sans-serif;
      background-color: #fff;
      color: #222;
      line-height: 1.7;
    }

    header {
      background: #fff;
      text-align: center;
      padding: 60px 20px 30px;
      border-bottom: 1px solid #eee;
    }

    header h1 {
      font-size: 46px;
      color: #000;
      margin-bottom: 10px;
      letter-spacing: 1px;
    }

    header p {
      font-size: 16px;
      color: #888;
      letter-spacing: 1px;
    }

    .hero-image {
      max-width: 280px;
      margin: 30px auto;
      border-radius: 50%;
      overflow: hidden;
    }

    .hero-image img {
      width: 100%;
      height: auto;
      display: block;
      object-fit: cover;
      border-radius: 50%;
      box-shadow: 0 6px 14px rgba(0, 0, 0, 0.12);
    }

    main {
      max-width: 820px;
      margin: 40px auto;
      padding: 0 20px;
    }

    section {
      margin-bottom: 50px;
    }

    h2 {
      font-size: 24px;
      color: #000;
      margin-bottom: 12px;
    }

    p {
      font-size: 16px;
      color: #444;
      margin-bottom: 15px;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 16px;
      margin-top: 20px;
    }

    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 12px;
      object-fit: cover;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .gallery img:hover {
      transform: scale(1.02);
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
    }

    .button {
      display: inline-block;
      padding: 12px 24px;
      margin-top: 20px;
      background-color: #000;
      color: #fff;
      text-decoration: none;
      border-radius: 30px;
      font-weight: 400;
      transition: background-color 0.3s ease;
    }

    .button:hover {
      background-color: #444;
    }

    footer {
      text-align: center;
      padding: 30px 20px;
      font-size: 14px;
      color: #aaa;
      border-top: 1px solid #eee;
      background-color: #fafafa;
    }
  </style>
</head>
<body>
  <header>
    <h1>Anya Isupova</h1>
    <p>Амбассадор красоты</p>
    <div class="hero-image">
      <img src="img/anya.jpg" alt="Anya Isupova">
    </div>
  </header>

  <main>
    <section>
      <h2>Обо мне</h2>
      <p>
        Я — Anya Isupova, амбассадор красоты, создатель и вдохновитель проектов в сфере эстетики, культурных событий и здорового образа жизни. Моя миссия — создавать стильное, глубокое и полезное пространство для женщин, которые выбирают качество, уверенность и гармонию.
      </p>
      <p>
        Мои проекты — это отражение ценностей минимализма, внутренней силы и современной женственности.
      </p>
    </section>

    <section>
      <h2>Проект: Monodrama Event</h2>
      <p>
        <strong>Monodrama Event</strong> — это уникальный формат камерных мероприятий, сочетающих элементы перформанса, театра, моды и живой коммуникации. Этот проект направлен на переосмысление женской роли в современном мире через искусство. Каждое событие — это эмоциональное и визуальное погружение, где женщины становятся главными героинями собственных историй.
      </p>
      <p>
        События Monodrama проходят в избранных локациях и объединяют сильных, чувствительных, креативных личностей. Мы работаем с талантливыми режиссёрами, стилистами и психологами, чтобы каждое выступление стало откровением.
      </p>
    </section>

    <section>
      <h2>Проект: Звёздный Пульс</h2>
      <p>
        <strong>Звёздный Пульс</strong> — это проект о красоте и здоровье, вдохновлённый космической гармонией и внутренним сиянием человека. Мы исследуем, как внешняя эстетика связана с энергетическим состоянием, образом жизни и ментальным балансом.
      </p>
      <p>
        В рамках проекта проходят тематические ретриты, коллаборации с косметологами, нутрициологами и wellness-экспертами. Цель — не просто внешняя трансформация, а создание устойчивого ресурса внутри каждой женщины.
      </p>
    </section>

    <section>
      <h2>Галерея проектов</h2>
      <div class="gallery">
        <img src="img/anya.jpg" alt="Anya Isupova Portrait">
      </div>
    </section>

    <section>
      <a href="#contact" class="button">Связаться</a>
    </section>
  </main>

  <footer>
    © 2025 Anya Isupova. Все права защищены.
  </footer>
</body>
</html>
