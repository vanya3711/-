<!DOCTYPE html>
<html lang="ua">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>3D Услуги и Печать</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f4f4f4; }
    header { background: #222; color: #fff; padding: 40px 20px; text-align: center; }
    header h1 { margin: 0 0 10px; }
    header p { margin: 0 0 20px; font-size: 1.2em; }
    .btn { padding: 10px 20px; background: #00b894; color: #fff; border: none; border-radius: 5px; text-decoration: none; margin: 5px; display: inline-block; }
    section { padding: 40px 20px; max-width: 1000px; margin: auto; }
    h2 { text-align: center; margin-bottom: 30px; }
    .services, .products, .portfolio { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .card { background: white; padding: 20px; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
    .photo-upload { text-align: center; margin-top: 30px; }
    .photo-upload input[type="file"] { margin-top: 10px; }
    footer { background: #222; color: #fff; padding: 30px 20px; text-align: center; }
  </style>
</head>
<body>
  <header>
    <h1>Профессиональные 3D-услуги</h1>
    <p>Моделирование, визуализация и 3D-печать под заказ</p>
    <a href="#catalog" class="btn">Каталог моделей</a>
    <a href="#contact" class="btn">Связаться с нами</a>
  </header>

  <section id="services">
    <h2>Наши услуги</h2>
    <div class="services">
      <div class="card">
        <h3>3D-моделирование</h3>
        <p>Создание точных цифровых моделей по фото, чертежам или идеям клиента.</p>
      </div>
      <div class="card">
        <h3>3D-визуализация</h3>
        <p>Фотореалистичные изображения и анимации для ваших проектов и презентаций.</p>
      </div>
      <div class="card">
        <h3>3D-печать</h3>
        <p>FDM и SLA-печать. Материалы на выбор, доставка по Украине.</p>
      </div>
    </div>
  </section>

  <section id="catalog">
    <h2>Каталог товаров</h2>
    <div class="products">
      <div class="card">
        <h3>Фигурка "Робот"</h3>
        <p>Цена: 1 200 ₴</p>
      </div>
      <div class="card">
        <h3>Корпус для Arduino</h3>
        <p>Цена: 500 ₴</p>
      </div>
      <div class="card">
        <h3>Заказать свою модель</h3>
        <p>Индивидуальное производство по вашему макету.</p>
      </div>
    </div>
  </section>

  <section id="portfolio">
    <h2>Портфолио</h2>
    <div class="portfolio">
      <div class="card">
        <h3>Проект: Архитектурный макет</h3>
        <p>Печать + рендер для презентации жилого комплекса.</p>
      </div>
      <div class="card">
        <h3>Проект: Кастом-фигурка</h3>
        <p>Модель на заказ по фотографии клиента.</p>
      </div>
    </div>
  </section>

  <section id="upload">
    <h2>Загрузите своё фото</h2>
    <div class="photo-upload">
      <form method="post" enctype="multipart/form-data">
        <input type="file" name="photo" accept="image/*">
        <br>
        <input type="submit" value="Загрузить" class="btn">
      </form>
      <p>Примечание: для активации загрузки необходимо настроить серверную часть.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Контакты</h2>
    <p style="text-align:center;">Тел: +380 (50) 000-00-00 | +380 (67) 111-11-11</p>
    <p style="text-align:center;">Email: info@3dprint.ua</p>
    <p style="text-align:center;">Telegram: @your3dservice | WhatsApp: +380 (50) 000-00-00</p>
  </section>

  <footer>
    <p>&copy; 2025 3D Услуги. Сделано с помощью <a href="https://gptonline.ai" style="color:#00b894;">gptonline.ai</a></p>
  </footer>
</body>
</html>

