# homepage
"My first personal website."
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мої проєкти </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }
        .project {
            background: white;
            margin-bottom: 20px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .project h2 {
            margin-top: 0;
        }
        .project img {
            max-width: 100%;
            border-radius: 8px;
        }
        .project p {
            line-height: 1.6;
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .btn {
            display: inline-block;
            background-color: #5cb85c;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #4cae4c;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Мої проекти в сфері e-commerce і криптовалюти </h1>
    </div>
    <div class="container">
        <div class="project">
            <h2>Проєкт 1: Тетсування ПЗ для POS - терміналів </h2>
            <img src="ecommerce_project.jpg" alt="OKKO-POS">
            <p>Цей продукт представляє собою пз для керування заправочними колонками а також для створення і обслуговуання клієнтів </p>
            <a href="https://example.com/ecommerce" class="btn">Подробнее</a>
        </div>
        <div class="project">
            <h2>Проєкт 2: Крипто біржа  з обмінником  </h2>
            <img src="crypto_project.jpg" alt="Криптобіржа з обмінником ">
            <p>Ця біржа дозволяє створювати різні типо ордерів , з штатною і позаштатною торгівлею яка отримує дані з 2 дата центрів на американському ринку валюти </p>
            
        </div>
    </div>
    <div class="footer">
        <p>Вся детальна іфнормація стосовно мого резюме за посиланням нижче .</p>
    </div>
</body>
</html>