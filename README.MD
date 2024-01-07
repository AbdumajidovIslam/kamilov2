<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your GitHub README</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" integrity="sha512-LCS+tdBDZGcda8eCf+gYr4lS9RVVT50D0FvsVRDEQ3X5B9hqaq94j2Q1xF+fQoIvMiIAko4RtM3XKlVKugxP5Q==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f7f7f7;
            margin: 20px;
        }

        h1 {
            color: #0366d6;
        }

        h2 {
            color: #6f42c1;
        }

        h3 {
            color: #22863a;
        }

        p {
            margin-bottom: 10px;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin-bottom: 5px;
        }

        a {
            color: #0366d6;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .icon {
            margin-right: 5px;
        }

        .stats {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
        }

        .stat-item {
            flex: 1;
            text-align: center;
            padding: 10px;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin-right: 5px;
        }
    </style>
</head>
<body>

    <h1>Привет, я [Ваше Имя]</h1>

    <h2>О себе</h2>
    <p>🌍 Проживаю в [Ваш город, страна]</p>
    <p>🎓 Студент/Работаю в [Ваше место учебы/работы]</p>
    <p>📚 Учусь/Работаю в области [Ваша область интересов/специализации]</p>

    <h2>Навыки и Технологии</h2>
    <h3>Языки программирования</h3>
    <ul>
        <li><i class="fab fa-python icon"></i> Python</li>
        <li><i class="fab fa-js icon"></i> JavaScript</li>
    </ul>

    <h3>Frontend</h3>
    <ul>
        <li><i class="fab fa-html5 icon"></i> HTML</li>
        <li><i class="fab fa-css3-alt icon"></i> CSS</li>
        <li><i class="fab fa-react icon"></i> React</li>
    </ul>

    <!-- Добавьте другие разделы по аналогии -->

    <h2>GitHub Статистика</h2>
    <div class="stats">
        <div class="stat-item">
            <h3>Статистика</h3>
            <img src="https://github-readme-stats.vercel.app/api?username=ваш_пользователь" alt="GitHub Stats">
        </div>
        <div class="stat-item">
            <h3>Топ языки</h3>
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ваш_пользователь" alt="Top Languages">
        </div>
    </div>

    <h2>Последние активности на GitHub</h2>
    <img src="https://activity-graph.herokuapp.com/graph?username=ваш_пользователь" alt="GitHub Activity Graph">

</body>
</html>
