# KOHANA
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Майстер Перманентного Макіяжу - Kohana Permanent</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fdfdfd;
            color: #333;
        }
        header {
            background-color: #f8b6c4;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #f8b6c4;
            font-weight: bold;
        }
        section {
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }
        .gallery img {
            width: 100%;
            height: auto;
            margin-bottom: 20px;
        }
        .services, .reviews, .contact {
            margin-bottom: 40px;
        }
        .service-item {
            display: flex;
            justify-content: space-between;
            border-bottom: 1px solid #ccc;
            padding: 10px 0;
        }
        .contact-info, .social-links {
            text-align: center;
        }
        .social-links a {
            margin: 0 10px;
            text-decoration: none;
            color: #f8b6c4;
            font-size: 1.5em;
        }
        footer {
            background-color: #f8b6c4;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Permanent make up</h1>
    <nav>
        <a href="#gallery">Фотографії</a>
        <a href="#services">Послуги</a>
        <a href="#reviews">Відгуки</a>
        <a href="#contact">Контакти</a>
    </nav>
</header>

<section id="gallery" class="gallery">
    <h2>Фотографії робіт</h2>
    <img src="[photo1.jpg](https://www.icloud.com/photos/#/i,pz,49F535F0-7F87-4CCE-BB87-09C434C22F73,1352/)" alt="<Брови">
    <img src="photo2.jpg" alt="Губи">
    <img src="photo3.jpg" alt="Очі">
</section>

<section id="services" class="services">
    <h2>Перелік послуг та ціни</h2>
    <div class="service-item">
        <span>Брови</span>
        <span>150 євро</span>
    </div>
    <div class="service-item">
        <span>Губи</span>
        <span>200 євро</span>
    </div>
    <div class="service-item">
        <span>Очі</span>
        <span>180 євро</span>
    </div>
</section>

<section id="reviews" class="reviews">
    <h2>Відгуки клієнтів</h2>
    <p>"Дуже задоволена результатом! Рекомендую всім." - Анна</p>
    <p>"Професійний підхід і чудовий сервіс." - Марія</p>
    <p>"Мої брови виглядають прекрасно! Дякую!" - Ольга</p>
</section>

<section id="contact" class="contact">
    <h2>Контактна інформація</h2>
    <p>Телефон: +380 123 456 789</p>
    <p>Email: kohana@example.com</p>
    <div class="social-links">
        <a href="https://www.instagram.com/kohana_permanent/" target="_blank">Instagram</a>
    </div>
</section>

<footer>
    <p>&copy; 2024 Kohana Permanent</p>
</footer>

</body>
</html>
