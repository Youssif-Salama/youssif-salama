<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Youssif Salama - Full Stack MERN Developer</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #0d1b2a;
            color: #f0f0f0;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
        }

        .container {
            background-color: #0077bc;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.8);
            animation: fadeIn 2s ease-in-out;
            max-width: 800px;
        }

        h1, h3 {
            text-align: center;
            color: #ffffff;
        }

        h1 {
            font-size: 2.5rem;
            text-shadow: 0px 0px 10px #00ffff;
        }

        h3 {
            font-size: 1.75rem;
            text-shadow: 0px 0px 5px #ffcc00;
        }

        .section {
            margin: 20px 0;
        }

        .section-title {
            font-size: 1.5rem;
            color: #ffffff;
            margin-bottom: 10px;
        }

        .tech-icon {
            display: inline-block;
            margin: 10px;
            padding: 10px;
            transition: transform 0.3s ease, background-color 0.3s ease;
        }

        .tech-icon img {
            width: 50px;
            height: 50px;
        }

        .tech-icon:hover {
            transform: translateY(-10px);
            background-color: rgba(255, 255, 255, 0.1);
        }

        a {
            text-decoration: none;
            color: #ffcc00;
            transition: color 0.3s ease;
        }

        a:hover {
            color: #00ffff;
        }

        /* Keyframe animations */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes pulse {
            0% {
                box-shadow: 0 0 10px #0077bc, 0 0 20px #0077bc, 0 0 30px #0077bc;
            }
            50% {
                box-shadow: 0 0 20px #00ffff, 0 0 40px #00ffff, 0 0 60px #00ffff;
            }
            100% {
                box-shadow: 0 0 10px #0077bc, 0 0 20px #0077bc, 0 0 30px #0077bc;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hi there, I'm Youssif Salama 👋</h1>
        <h3>Full Stack MERN Developer</h3>
        <div class="section">
            <h4 class="section-title">Technologies & Tools</h4>
            <div class="tech-icon"><img src="https://img.shields.io/badge/HTML5-orange?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"></div>
            <div class="tech-icon"><img src="https://img.shields.io/badge/CSS3-blue?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"></div>
            <div class="tech-icon"><img src="https://img.shields.io/badge/JavaScript-yellow?style=for-the-badge&logo=javascript&logoColor=white" alt="JavaScript"></div>
            <!-- Add more technologies as needed -->
        </div>
        <div class="section">
            <h4 class="section-title">💼 Professional Experience</h4>
            <p>Freelance Developer: Worked on several freelance projects using the MERN stack and more.</p>
            <p>Contract with KLXDYI Company: Developed full stack applications.</p>
        </div>
        <div class="section">
            <h4 class="section-title">📖 Currently Learning</h4>
            <p>Nest.js & Jest for building scalable backend applications and writing tests.</p>
        </div>
        <div class="section">
            <h4 class="section-title">📫 How to Reach Me</h4>
            <p>Email: <a href="mailto:youssifsalama01@gmail.com">youssifsalama01@gmail.com</a></p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/youssif-salama-039506244/">Youssif Salama</a></p>
        </div>
    </div>
</body>
</html>
