<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF+3">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ГефестГард — Монтаж и обслуживание пожарной сигнализации</title>
    <meta name="description" content="Профессиональный монтаж и обслуживание пожарной сигнализации в Москве. Обеспечиваем безопасность вашего бизнеса и дома.">
    <link rel="stylesheet" href="styles.css"> <!-- Подключение внешнего файла стилей -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #ff0000;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .services, .advantages, .portfolio, .contact-form {
            margin-bottom: 40px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
        }
        .contact-form button {
            background-color: #ff0000;
            color: #fff;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        .image-gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .image-gallery img {
            width: 100%;
            max-width: 300px;
            height: auto;
            border-radius: 8px;
        }
    </style>
</head>
<body>

    <!-- Шапка сайта -->
    <header>
        <h1>ГефестГард</h1>
        <p>Надежная защита от пожаров в Москве</p>
    </header>

    <!-- Навигационное меню -->
    <nav>
        <a href="#services">Услуги</a>
        <a href="#about">О компании</a>
        <a href="#portfolio">Портфолио</a>
        <a href="#contact">Контакты</a>
    </nav>

    <!-- Основное содержимое -->
    <section id="services" class="services">
        <h2>Наши услуги</h2>
        <ul>
            <li>Монтаж пожарной сигнализации</li>
            <li>Обслуживание пожарной сигнализации</li>
            <li>Проектирование систем пожарной безопасности</li>
        </ul>
        <button onclick="location.href='#contact'">Заказать услугу</button>
        <div class="image-gallery">
            <img src="https://via.placeholder.com/300x200?text=Монтаж+пожарной+сигнализации" alt="Монтаж пожарной сигнализации">
            <img src="https://via.placeholder.com/300x200?text=Обслуживание+пожарной+сигнализации" alt="Обслуживание пожарной сигнализации">
            <img src="https://via.placeholder.com/300x200?text=Проектирование+систем+безопасности" alt="Проектирование систем безопасности">
        </div>
    </section>

    <section id="advantages" class="advantages">
        <h2>Почему выбирают нас?</h2>
        <ul>
            <li>Быстрый монтаж</li>
            <li>Качественное оборудование</li>
            <li>Квалифицированные специалисты</li>
            <li>Гарантия на работы</li>
        </ul>
        <div class="image-gallery">
            <img src="https://via.placeholder.com/300x200?text=Быстрый+монтаж" alt="Быстрый монтаж">
            <img src="https://via.placeholder.com/300x200?text=Качественное+оборудование" alt="Качественное оборудование">
            <img src="https://via.placeholder.com/300x200?text=Квалифицированные+специалисты" alt="Квалифицированные специалисты">
        </div>
    </section>

    <section id="portfolio" class="portfolio">
        <h2>Наши работы</h2>
        <p>Фотогалерея выполненных проектов.</p>
        <div class="image-gallery">
            <img src="https://via.placeholder.com/300x200?text=Проект+1" alt="Проект 1">
            <img src="https://via.placeholder.com/300x200?text=Проект+2" alt="Проект 2">
            <img src="https://via.placeholder.com/300x200?text=Проект+3" alt="Проект 3">
        </div>
    </section>
<!--
    <section id="contact" class="contact-form">
        <h2>Свяжитесь с нами</h2>
        <form action="#" method="post">
            <input type="text" name="name" placeholder="Ваше имя" required>
            <input type="tel" name="phone" placeholder="Ваш телефон" required>
            <input type="email" name="email" placeholder="Ваш email" required>
            <textarea name="message" placeholder="Ваше сообщение" rows="5" required></textarea>
            <button type="submit">Отправить</button>
        </form>
    </section>-->

    <!-- Подвал сайта -->
 	<section id="contact" class="contact">
    <footer>
        <p>© 2025 ООО "ГефестГард". Все права защищены.</p>
        <p>125930, г. Москва, Автомобильный пр-д., д. 9, стр.  6 | Телефон: +7 (495) 123-45-67</p>
        <p>Email: info@gefestguard.ru</p>
    </footer>

</body>
</html>
