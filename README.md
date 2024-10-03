<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prom004's Professional GitHub Profile</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f5f5f5;
        }
        .container {
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 30px;
            margin-bottom: 20px;
        }
        h1, h2 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        .center {
            text-align: center;
        }
        .badge-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
            margin: 20px 0;
        }
        .stats-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin: 20px 0;
        }
        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .project-card {
            background-color: #f9f9f9;
            border-radius: 8px;
            padding: 15px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .skill-category {
            margin-bottom: 20px;
        }
        .skill-category h3 {
            color: #3498db;
        }
        .timeline {
            position: relative;
            max-width: 1200px;
            margin: 0 auto;
        }
        .timeline::after {
            content: '';
            position: absolute;
            width: 6px;
            background-color: #3498db;
            top: 0;
            bottom: 0;
            left: 50%;
            margin-left: -3px;
        }
        .timeline-item {
            padding: 10px 40px;
            position: relative;
            background-color: inherit;
            width: 50%;
        }
        .timeline-item::after {
            content: '';
            position: absolute;
            width: 25px;
            height: 25px;
            right: -17px;
            background-color: #ffffff;
            border: 4px solid #3498db;
            top: 15px;
            border-radius: 50%;
            z-index: 1;
        }
        .left {
            left: 0;
        }
        .right {
            left: 50%;
        }
        .right::after {
            left: -16px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="center">Prom004 | Software Engineer & ML Enthusiast</h1>
        <p class="center">
            <img src="/api/placeholder/200/200" alt="Professional headshot of Prom004" style="border-radius: 50%; width: 200px; height: 200px;"/>
        </p>
        <p class="center">
            <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&duration=3000&pause=1000&color=3498DB&center=true&vCenter=true&width=435&lines=Software+Engineering+Student;Machine+Learning+Enthusiast;Database+Developer;Innovative+Problem+Solver" alt="Typing SVG">
        </p>
        <div class="badge-container">
            <a href="https://www.linkedin.com/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
            <a href="mailto:youremail@example.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
            <a href="https://github.com/Prom004"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
            <a href="#"><img src="https://img.shields.io/badge/Portfolio-1abc9c?style=for-the-badge&logo=github&logoColor=white" alt="Portfolio"/></a>
        </div>
    </div>

    <div class="container">
        <h2>👩‍💻 About Me</h2>
        <p>Hello! I'm Prom004, a passionate Software Engineering student with a keen interest in machine learning and database development. I'm on a mission to create innovative software solutions that can make a real difference in the world.</p>
        <ul>
            <li>🎓 Currently pursuing a degree in Software Engineering</li>
            <li>🌱 Actively learning and expanding my skills in ML and database optimization</li>
            <li>💡 Always excited to tackle challenging projects and collaborate with fellow developers</li>
            <li>🚀 Aspiring to contribute to cutting-edge technologies and open-source projects</li>
            <li>👥 Pronouns: She/her</li>
        </ul>
    </div>

    <div class="container">
        <h2>🛠️ Technical Skills</h2>
        <div class="skill-category">
            <h3>Programming Languages</h3>
            <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
            <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java"/>
            <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
        </div>
        <div class="skill-category">
            <h3>Databases</h3>
            <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
            <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
            <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
        </div>
        <div class="skill-category">
            <h3>Machine Learning & AI</h3>
            <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
            <img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="scikit-learn"/>
            <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
        </div>
        <div class="skill-category">
            <h3>Tools & Technologies</h3>
            <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
            <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
            <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
        </div>
    </div>

    <div class="container">
        <h2>📊 GitHub Statistics</h2>
        <div class="stats-container">
            <img src="https://github-readme-stats.vercel.app/api?username=Prom004&show_icons=true&theme=react" alt="GitHub Stats" />
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=Prom004&theme=react" alt="GitHub Streak" />
        </div>
        <div class="center">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Prom004&layout=compact&theme=react" alt="Top Languages" />
        </div>
    </div>

    <div class="container">
        <h2>🚀 Featured Projects</h2>
        <div class="project-grid">
            <div class="project-card">
                <h3>ML-Powered Stock Predictor</h3>
                <p>A machine learning model that predicts stock prices using historical data and sentiment analysis.</p>
                <a href="#"><img src="https://img.shields.io/badge/View_Project-2ea44f?style=for-the-badge" alt="View Project"/></a>
            </div>
            <div class="project-card">
                <h3>Smart Database Optimizer</h3>
                <p>An AI-driven tool that optimizes database queries and structures for improved performance.</p>
                <a href="#"><img src="https://img.shields.io/badge/View_Project-2ea44f?style=for-the-badge" alt="View Project"/></a>
            </div>
            <div class="project-card">
                <h3>EcoTrack: Sustainability App</h3>
                <p>A mobile app that helps users track and reduce their carbon footprint through daily activities.</p>
                <a href="#"><img src="https://img.shields.io/badge/View_Project-2ea44f?style=for-the-badge" alt="View Project"/></a>
            </div>
        </div>
    </div>

    <div class="container">
        <h2>🌟 Professional Journey</h2>
        <div class="timeline">
            <div class="timeline-item left">
                <h3>Software Engineering Student</h3>
                <p>University Name, 2022 - Present</p>
                <p>Focusing on advanced algorithms, software architecture, and AI applications.</p>
            </div>
            <div class="timeline-item right">
                <h3>Machine Learning Intern</h3>
                <p>Tech Company Name, Summer 2023</p>
                <p>Developed and implemented ML models for predictive analytics.</p>
            </div>
            <div class="timeline-item left">
                <h3>Open Source Contributor</h3>
                <p>Various Projects, 2022 - Present</p>
                <p>Active contributor to open-source ML and database optimization projects.</p>
            </div>
        </div>
    </div>

    <div class="container">
        <h2>🎯 Future Aspirations</h2>
        <ul>
            <li>Develop cutting-edge AI solutions that address real-world challenges</li>
            <li>Contribute significantly to open-source projects in software engineering and ML</li>
            <li>Pursue advanced studies in Artificial Intelligence and Data Science</li>
            <li>Mentor aspiring developers and promote diversity in tech</li>
            <li>Launch a tech startup focused on sustainable technology solutions</li>
        </ul>
    </div>

    <div class="container center">
        <h2>📫 Get in Touch</h2>
        <p>I'm always open to interesting conversations and collaboration opportunities. Feel free to reach out!</p>
        <a href="mailto:youremail@example.com"><img src="https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Me"/></a>
        <a href="https://www.linkedin.com/"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn"/></a>
    </div>

    <hr>
    <p class="center">
        <img src="https://komarev.com/ghpvc/?username=Prom004&label=Profile%20views&color=0e75b6&style=flat" alt="Profile Views" />
    </p>
</body>
</html>
