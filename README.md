# nasir-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nasir Shaik Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <nav>
        <h2>Nasir Shaik</h2>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#certificates">Certificates</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section class="home">
    <h1>Hello, I'm Nasir Shaik</h1>
    <p>B.Tech CSE Student | Aspiring Software Developer</p>
    <button onclick="toggleMode()">Dark Mode</button>
</section>

<section id="about">
    <h2>About Me</h2>
    <p>
        I am a Computer Science Engineering student currently pursuing B.Tech III Year.
        I am passionate about Software Development, Cloud Computing, and DBMS.
        I enjoy building real-time applications to solve real-world problems.
    </p>
</section>

<section id="skills">
    <h2>Skills</h2>
    <ul>
        <li>Java</li>
        <li>Python</li>
        <li>HTML, CSS, JavaScript</li>
        <li>MySQL</li>
        <li>Data Structures</li>
        <li>DBMS</li>
        <li>Cloud Computing</li>
        <li>Compiler Design</li>
    </ul>
</section>

<section id="projects">
    <h2>Projects</h2>

    <div class="card">
        <h3>Student Management System</h3>
        <p>Developed using Java & MySQL to manage student academic records.</p>
    </div>

    <div class="card">
        <h3>Library Management System</h3>
        <p>System to manage book issuing and returning efficiently.</p>
    </div>

    <div class="card">
        <h3>Cloud File Storage System</h3>
        <p>Mini project based on cloud computing for secure file storage.</p>
    </div>

</section>

<section id="certificates">
    <h2>Certificates</h2>
    <ul>
        <li>NPTEL Cloud Computing</li>
        <li>Python Programming</li>
        <li>DBMS Course</li>
        <li>Java Fundamentals</li>
        <li>Web Development</li>
    </ul>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p>Email: nasirshaik@email.com</p>
    <p>Phone: +91-XXXXXXXXXX</p>
    <p>Location: Andhra Pradesh</p>
</section>

<footer>
    <p>© 2026 Nasir Shaik | All Rights Reserved</p>
</footer>

<script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial;
    margin: 0;
    padding: 0;
    text-align: center;
    transition: 0.5s;
}

header {
    background: #333;
    color: white;
    padding: 10px;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin: 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 40px;
}

.card {
    border: 1px solid gray;
    padding: 15px;
    margin: 10px;
}

footer {
    background: black;
    color: white;
    padding: 10px;
}

.dark {
    background: black;
    color: white;
}
function toggleMode(){
    document.body.classList.toggle("dark");
}