<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mariya John | Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
    background: #000;
    color: #fff;
    overflow-x: hidden;
}

header {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background: linear-gradient(135deg, #000000, #111111);
    text-align: center;
}

header h1 {
    font-size: 60px;
    letter-spacing: 4px;
    font-weight: 700;
    animation: fadeDown 1s ease-in-out;
}

header p {
    font-size: 20px;
    margin-top: 15px;
    color: #ccc;
    animation: fadeUp 1.5s ease-in-out;
}

button {
    margin-top: 30px;
    padding: 12px 30px;
    background: transparent;
    border: 2px solid #fff;
    color: #fff;
    font-size: 16px;
    cursor: pointer;
    transition: 0.4s;
}

button:hover {
    background: #fff;
    color: #000;
    box-shadow: 0 0 15px #fff;
}

section {
    padding: 100px 10%;
}

h2 {
    font-size: 30px;
    margin-bottom: 40px;
    position: relative;
}

h2::after {
    content: "";
    width: 60px;
    height: 3px;
    background: #fff;
    position: absolute;
    left: 0;
    bottom: -10px;
}

.skills span {
    display: inline-block;
    padding: 10px 20px;
    margin: 8px;
    border: 1px solid #fff;
    transition: 0.3s;
}

.skills span:hover {
    background: #fff;
    color: #000;
    transform: scale(1.05);
}

.project-card {
    border: 1px solid #333;
    padding: 25px;
    margin-bottom: 30px;
    transition: 0.4s;
}

.project-card:hover {
    background: #111;
    transform: translateY(-10px);
    box-shadow: 0 0 20px rgba(255,255,255,0.2);
}

.project-card h3 {
    margin-bottom: 15px;
}

.contact-box p {
    margin-bottom: 15px;
    font-size: 18px;
}

.contact-box a {
    color: #fff;
    text-decoration: underline;
}

footer {
    text-align: center;
    padding: 30px;
    border-top: 1px solid #333;
    color: #aaa;
}

/* Animations */
@keyframes fadeDown {
    from { opacity: 0; transform: translateY(-50px); }
    to { opacity: 1; transform: translateY(0); }
}

@keyframes fadeUp {
    from { opacity: 0; transform: translateY(50px); }
    to { opacity: 1; transform: translateY(0); }
}

</style>
</head>

<body>

<header>
    <h1>MARIYA JOHN</h1>
    <p>Cyber Security Undergraduate</p>
    <button onclick="window.location.href='mailto:mariyajohn2027@gmail.com'">
        Contact Me
    </button>
</header>

<section>
    <h2>About Me</h2>
    <p>
        I am a passionate Cyber Security undergraduate focused on secure system development,
        application design, and innovative problem solving. I enjoy building efficient
        software solutions and continuously enhancing my expertise in cybersecurity
        and programming technologies.
    </p>
</section>

<section>
    <h2>Technical Skills</h2>
    <div class="skills">
        <span>Python</span>
        <span>Java</span>
        <span>C</span>
        <span>HTML</span>
        <span>CSS</span>
        <span>JavaScript</span>
        <span>MySQL</span>
        <span>Git</span>
        <span>GitHub</span>
        <span>Linux Basics</span>
        <span>Networking</span>
        <span>OOPS</span>
    </div>
</section>

<section>
    <h2>Projects</h2>

    <div class="project-card">
        <h3>Vehicle Theft Detection System</h3>
        <p>
            Developed a smart security system that detects unauthorized vehicle access
            using identification logic and alert mechanisms to enhance vehicle protection.
        </p>
    </div>

    <div class="project-card">
        <h3>User Authentication System</h3>
        <p>
            Built a secure login and registration system with database validation,
            ensuring proper credential verification and secure data handling.
        </p>
    </div>

    <div class="project-card">
        <h3>Canteen Pre-Order Website</h3>
        <p>
            Designed a web application allowing users to pre-order food,
            reducing waiting time and improving order management efficiency.
        </p>
    </div>

</section>

<section>
    <h2>Certifications</h2>
    <p>Generative AI for All – Infosys Springboard</p>
    <p>Artificial Intelligence for All – Infosys Springboard</p>
    <p>Introduction to Programming – Infosys Springboard</p>
</section>

<section>
    <h2>Languages</h2>
    <p>English | Malayalam | Hindi</p>
</section>

<section>
    <h2>Contact</h2>
    <div class="contact-box">
        <p>
            📧 Email:
            <a href="mailto:mariyajohn2027@gmail.com">
                mariyajohn2027@gmail.com
            </a>
        </p>

        <p>
            📞 Phone:
            <a href="tel:+917736898348">
                +91 7736898348
            </a>
        </p>
    </div>
</section>

<footer>
    © 2026 Mariya John | All Rights Reserved
</footer>

</body>
</html>
