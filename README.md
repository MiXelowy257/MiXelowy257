<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>O mnie</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f7f6;
            margin: 0;
            padding: 0;
        }

        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }

        h1, h2, h3 {
            color: #333;
        }

        h1 {
            font-size: 2.5em;
        }

        h2 {
            color: #2c3e50;
        }

        .badge {
            margin: 5px;
        }

        .section {
            margin-bottom: 40px;
        }

        .tools img, .languages img {
            margin: 5px;
        }

        .section ul {
            list-style-type: none;
            padding: 0;
        }

        .section ul li {
            margin-bottom: 10px;
        }

        .stats img {
            margin: 10px;
        }

        footer {
            text-align: center;
            font-size: 0.9em;
            color: #7f8c8d;
        }

        .badge-link {
            text-decoration: none;
            font-size: 1.2em;
            color: #3498db;
        }

        .badge-link:hover {
            color: #2c3e50;
        }
    </style>
</head>
<body>

    <div class="container">
        <section class="section">
            <h1>👋 O mnie:</h1>
            <p>Jestem programistą z zajawką na tworzenie <strong>gier, aplikacji webowych oraz mobilnych</strong> oraz <strong>cyberbezpieczeństwo</strong>. Zajmuję się też <strong>modelowaniem i animacjami 3D</strong> z użyciem <strong>Blendera</strong>.</p>
        </section>

        <section class="section">
            <h2>🔧 Najczęściej korzystam</h2>
            <h3>💻 Języki:</h3>
            <div class="languages">
                <a href="https://www.python.org/" class="badge badge-link"><img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=yellow" alt="Python"></a>
                <a href="https://learn.microsoft.com/en-us/dotnet/csharp/" class="badge badge-link"><img src="https://img.shields.io/badge/-CSharp-239120?style=flat-square&logo=c-sharp&logoColor=white" alt="C#"></a>
                <a href="https://www.javascript.com/" class="badge badge-link"><img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"></a>
                <a href="https://www.mysql.com/" class="badge badge-link"><img src="https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=orange" alt="MySQL"></a>
                <a href="https://kotlinlang.org/" class="badge badge-link"><img src="https://img.shields.io/badge/-Kotlin-0095D5?style=flat-square&logo=kotlin&logoColor=purple" alt="Kotlin"></a>
            </div>

            <h3>🔨 Narzędzia i środowiska:</h3>
            <div class="tools">
                <a href="https://unity.com/" class="badge badge-link"><img src="https://img.shields.io/badge/-Unity-000000?style=for-the-badge&logo=unity&logoColor=white" alt="Unity"></a>
                <a href="https://www.blender.org/" class="badge badge-link"><img src="https://img.shields.io/badge/-Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white" alt="Blender"></a>
                <a href="https://code.visualstudio.com/" class="badge badge-link"><img src="https://img.shields.io/badge/-Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="Visual Studio Code"></a>
                <a href="https://developer.android.com/studio" class="badge badge-link"><img src="https://img.shields.io/badge/-Android%20Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=blue" alt="Android Studio"></a>
            </div>
        </section>

        <section class="section">
            <h2>✨ Czym się zajmuję?</h2>
            <ul>
                <li>🎮 Tworzenie gier komputerowych z użyciem <strong>Unity</strong> i <strong>C#</strong></li>
                <li>👨‍🎨 Modelowanie i animacje 3D z użyciem <strong>Blendera</strong></li>
                <li>👨‍💻 <strong>Pentesty</strong></li>
                <li>🌐 Tworzenie stron internetowych</li>
                <li>📲 Tworzenie i programowanie aplikacji mobilnych</li>
                <li>🤖 Projekty z użyciem <strong>Arduino</strong></li>
            </ul>
        </section>

        <section class="section">
            <h2>🎮 Nad czym pracuję?</h2>
            <ul>
                <li>🕵️‍♂️ <strong>Code-Breakout</strong> - gra kryminalna z użyciem <strong>Unity</strong>, <strong>C#</strong> oraz <strong>Blendera</strong></li>
                <li>👨‍💻 Tworzenie <strong>Exploitów</strong> oraz ich rozszerzeń</li>
            </ul>
        </section>

        <section class="section">
            <h2>🧠 Uczę się:</h2>
            <div class="learning">
                <a href="https://www.php.net/" class="badge badge-link"><img src="https://img.shields.io/badge/-PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP"></a>
                <a href="https://www.ruby-lang.org/en/" class="badge badge-link"><img src="https://img.shields.io/badge/-Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white" alt="Ruby"></a>
                <a href="https://www.arduino.cc/" class="badge badge-link"><img src="https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white" alt="Arduino"></a>
            </div>
        </section>

        <section class="section stats">
            <h2>📊 Statystyki</h2>
            <div>
                <img src="https://github-readme-stats.vercel.app/api?username=MiXelowy257&show_icons=true&theme=tokyonight" alt="GitHub stats">
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MiXelowy257&layout=compact&theme=tokyonight" alt="Top languages">
            </div>
        </section>

        <footer>
            <p>&copy; 2025 - MiXelowy257</p>
        </footer>
    </div>
    
</body>
</html>
