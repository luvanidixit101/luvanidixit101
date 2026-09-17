<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Dixit Luvani | Developer</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #0d1117;
            color: #c9d1d9;
            line-height: 1.7;
        }

        .container {
            max-width: 900px;
            margin: auto;
            padding: 40px 20px;
        }

        header {
            text-align: center;
            margin-bottom: 40px;
        }

        header h1 {
            color: #ffffff;
            font-size: 40px;
        }

        header h2 {
            color: #58a6ff;
            font-size: 21px;
            margin: 10px 0;
        }

        header p {
            max-width: 700px;
            margin: auto;
            color: #8b949e;
        }

        section {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 10px;
            padding: 25px;
            margin-bottom: 25px;
        }

        section h2 {
            color: #58a6ff;
            margin-bottom: 18px;
        }

        ul {
            padding-left: 22px;
        }

        li {
            margin-bottom: 8px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th,
        td {
            padding: 12px;
            border: 1px solid #30363d;
            text-align: left;
        }

        th {
            background: #21262d;
            color: #58a6ff;
        }

        .project {
            background: #0d1117;
            border: 1px solid #30363d;
            border-radius: 8px;
            padding: 18px;
            margin-bottom: 15px;
        }

        .project h3 {
            color: #ffffff;
            margin-bottom: 8px;
        }

        .tech {
            color: #3fb950;
            margin-top: 8px;
        }

        a {
            color: #58a6ff;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .stats {
            text-align: center;
        }

        .stats img {
            max-width: 100%;
            margin-top: 10px;
        }

        footer {
            text-align: center;
            color: #8b949e;
            padding: 20px;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 30px;
            }

            table {
                font-size: 14px;
            }
        }
    </style>
</head>

<body>

<div class="container">

    <!-- Introduction -->
    <header>

        <h1>Hi, I'm Dixit Luvani 👋</h1>

        <h2>Python & Django Developer | Full-Stack Developer</h2>

        <p>
            MCA student passionate about backend development and building
            real-world web applications. My primary focus is Python and Django,
            along with REST APIs, databases and modern full-stack technologies.
        </p>

    </header>


    <!-- About -->
    <section>

        <h2>💻 About Me</h2>

        <ul>
            <li>🎓 MCA Student</li>

            <li>
                🐍 Focused on Python, Django and Backend Development
            </li>

            <li>
                🚀 Currently learning Spring Boot, Microservices and React
            </li>

            <li>
                🧠 Interested in REST APIs, Database Design and scalable applications
            </li>
        </ul>

    </section>


    <!-- Tech Stack -->
    <section>

        <h2>🛠️ Tech Stack</h2>

        <table>

            <tr>
                <th>Category</th>
                <th>Technologies</th>
            </tr>

            <tr>
                <td>Languages</td>
                <td>Python, Java, JavaScript, TypeScript</td>
            </tr>

            <tr>
                <td>Frontend</td>
                <td>React.js, HTML, CSS, Tailwind CSS, Bootstrap</td>
            </tr>

            <tr>
                <td>Backend</td>
                <td>Django, Spring Boot, REST APIs</td>
            </tr>

            <tr>
                <td>Databases</td>
                <td>PostgreSQL, MySQL, SQLite</td>
            </tr>

            <tr>
                <td>Tools</td>
                <td>Git, GitHub, Docker, Postman, VS Code, IntelliJ IDEA</td>
            </tr>

        </table>

    </section>


    <!-- Projects -->
    <section>

        <h2>📁 Featured Projects</h2>


        <div class="project">

            <h3>🛠️ ToolShare</h3>

            <p>
                Peer-to-peer tool sharing and rental platform
                based on Microservices Architecture.
            </p>

            <p class="tech">
                Spring Boot | PostgreSQL | Docker | React | TypeScript
            </p>

        </div>


        <div class="project">

            <h3>🚚 FleetFlow</h3>

            <p>
                Web-based fleet management system for managing
                vehicles and related operations.
            </p>

            <p class="tech">
                Python | Django | PostgreSQL
            </p>

        </div>


        <div class="project">

            <h3>🤖 AI Attendance System</h3>

            <p>
                Face recognition based attendance management application.
            </p>

            <p class="tech">
                Node.js | JavaScript | SQLite | Face-API.js
            </p>

        </div>


        <div class="project">

            <h3>💰 Expense Splitter</h3>

            <p>
                Web application for managing and splitting
                shared expenses between users.
            </p>

            <p class="tech">
                Python | Django | PostgreSQL
            </p>

        </div>

    </section>


    <!-- GitHub -->
    <section class="stats">

        <h2>📊 GitHub Stats</h2>

        <img
            src="https://github-readme-stats.vercel.app/api?username=luvanidixit101&show_icons=true&theme=github_dark"
            alt="Dixit Luvani GitHub Stats"
        >

    </section>


    <!-- Contact -->
    <section>

        <h2>📬 Connect With Me</h2>

        <p>
            💻 GitHub:
            <a href="https://github.com/luvanidixit101" target="_blank">
                github.com/luvanidixit101
            </a>
        </p>

        <p>
            📍 Ahmedabad, Gujarat, India
        </p>

        <p>
            💼 Open to Python/Django, Backend and Full-Stack Developer opportunities.
        </p>

    </section>


    <footer>
        © 2026 Dixit Luvani
    </footer>

</div>

</body>

</html>
