<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Molina Portfolio</title>
    <style>
body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
    scroll-behavior: smooth;
}

/* Header */
header {
    background: linear-gradient(to right, #aedcaf, #adc6b8);
    color: white;
    padding: 20px;
    text-align: center;
    font-size: 28px;
    font-weight: bold;
}

/* Glowing Text Effect */
@keyframes glowing {
    0% { text-shadow: 0 0 5px #4CAF50, 0 0 10px #4CAF50, 0 0 15px #4CAF50; }
    50% { text-shadow: 0 0 10px #00ff00, 0 0 20px #00ff00, 0 0 30px #00ff00; }
    100% { text-shadow: 0 0 5px #4CAF50, 0 0 10px #4CAF50, 0 0 15px #4CAF50; }
}

.glowing-text {
    font-size: 24px;
    font-weight: bold;
    color: #4CAF50;
    animation: glowing 1.5s infinite alternate;
    text-align: center;
}

/* Navigation Bar */
nav {
    display: flex;
    justify-content: center;
    background-color: #444;
    padding: 10px 0;
}

nav a {
    color: white;
    padding: 15px 20px;
    text-decoration: none;
    text-transform: uppercase;
    font-weight: bold;
    transition: 0.3s;
}

nav a:hover, nav a.active {
    background-color: #666;
    border-radius: 5px;
}

/* Sections */
section {
    padding: 50px 20px;
    margin: 20px auto;
    width: 80%;
    max-width: 900px;
    background: white;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
}

/* About Me Section */
.about-content {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 15px;
    text-align: center;
}

.about-content img {
    width: 160px;
    height: 160px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid #4CAF50;
    box-shadow: 0px 0px 15px #4CAF50;
}

/* Responsive List for Hobbies */
.list-section ul {
    list-style: none;
    padding: 0;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.list-section li {
    background: #e0f2e9;
    margin: 5px;
    padding: 10px 15px;
    border-radius: 5px;
    font-weight: bold;
    transition: 0.3s;
}

/* Glowing Effect for Hobbies */
.list-section li:hover {
    background: #4CAF50;
    color: white;
    box-shadow: 0px 0px 10px #4CAF50;
}

/* Footer */
footer {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 20px;
    font-weight: bold;
    position: fixed;
    bottom: 0;
    width: 100%;
}
    </style>
</head>
<body>
    <header>
        MOLINA PORTFOLIO
    </header>

    <nav>
        <a href="javascript:void(0);" onclick="showSection('about')" class="active">About Me</a>
        <a href="javascript:void(0);" onclick="showSection('skills')">Skills</a>
        <a href="javascript:void(0);" onclick="showSection('projects')">Projects</a>
        <a href="javascript:void(0);" onclick="showSection('contact')">Contact</a>
        <a href="javascript:void(0);" onclick="showSection('academic')">Academic & Training</a>
        <a href="javascript:void(0);" onclick="showSection('blogs')">Blogs</a>
    </nav>

    <section id="about">
        <h2>WELCOME TO MY PORTFOLIO</h2>
        <div class="about-content">
            <img src="dp.jpg" alt="Julie Ann Molina">
            <div class="info" style="font-size: large; ">
                <h3 class="glowing-text"><strong>I AM</strong>   Julie Ann Molina </h3>
                <h3><strong>21</strong> years of age.</h3>
                <h3><strong>I live in</strong> Alcala, Cagayan</h3>
                <h3>My Hobbies are</h3>
                <ul>
                    <ul>Eating, Listening to Music, Adventure, Gaming, Playing Table Tennis</ul>
                </ul>
                <h3>My quote in life is: <br>
                    "Your work is going to fill a large part of your life, and the only way to be truly satisfied is to do what you believe is <b style="font-size: 12;">GREAT WORK"</b>.</h3>
            </div>
        </div>
    </section>

    <section id="skills">
        <h1>My Skills</h1>
        <div class="skills-container">
            <div class="skill-card">
                <img src="html.PNG" alt="HTML Icon">
                <h3>HTML</h3>
                <p>I am good in HTML because I can create well-structured web pages with semantic elements.</p>
            </div>
            <div class="skill-card">
                <img src="css.PNG" alt="CSS Icon">
                <h3>CSS</h3>
                <p>I have strong CSS skills, allowing me to design visually appealing and responsive websites.</p>
            </div>
            <div class="skill-card">
                <img src="java.PNG" alt="Java Programming">
                <h3>Java Programming</h3>
                <p>I am good in Java Programming.</p>
            </div>
        </div>
    </section>

    <section id="projects">
        <h1>My Implemented and On-going Projects</h1>
        <div class="skills-container">
            <div class="skill-card">
                <img src="prj1.PNG" alt="Project1">
                <h3>Project 1: Web Development</h3>
                <p>I created Web Development Project.</p>
            </div>
            <div class="skill-card">
                <img src="prj2.PNG"alt="Project 2">
                <h3>Project 2: Website</h3>
                <p>I developed another Website.</p>
            </div>
            <div class="skill-card">
                <img src="prj3.PNG" alt="Project 3">
                <h3>Project 3: Project Management System</h3>
                <p>I implement project management system</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h1>You can reach me on the details below:</h1>
        <div class="skills-container">
            <div class="skill-card">
                <img src="email.PNG" alt="Email Address">
                <h3>Email Address: molinajulieann@sjcbi.edu.ph</h3> 
            </div>
            <div class="skill-card">
                <img src="linkedin.PNG"alt="Linkedin">
                <h3>Linked-in Account: https://www/linkedin.com/in/yourprofile</h3>
            </div>
            <div class="skill-card">
                <img src="github.PNG"alt="Github">
                <h3>Github Account: https://github.com/molinajulieann</h3>
            </div>

        </div>
    </section>

    <section id="academic">
        <h1>My Accomplishment</h1>
        <div class="skills-container">
            <div class="skill-card">
                <img src="accomplishment1.jpg" alt="Accomplishment">
                <h3>Bachelor of Science in Information Technology</h3> 
                <p>School: St. Joseph College of Baggao Incorporated</p>
            </div>
            <div class="skill-card">
                <img src="accomplishment2.jpg"alt="accomplishment1">
                <h3>Certificate of Completion in NSTP</h3>
            </div>

        </div>
    </section>

    <section id="blogs">
        <h2>Blogs</h2>
        <img src="blog.PNG" alt="Blogs Image">
        <p>Here are some of the blog posts I've written on topics like web development, design, and technology:</p>
        <ul>
            <li><a href="https://yourbloglink.com" target="_blank">The Future of Web Design</a></li>
            <li><a href="https://yourbloglink.com" target="_blank">Why JavaScript is Essential for Web Development</a></li>
            <li><a href="https://yourbloglink.com" target="_blank">Tips for Responsive Web Design</a></li>
        </ul>
    </section>

    <footer>
        &copy; 2025 Julie Ann Molina All Rights Reserved.
    </footer>

    <script>
        function showSection(sectionId) {
            const sections = document.querySelectorAll('section');
            sections.forEach(section => section.style.display = 'none');
            document.getElementById(sectionId).style.display = 'block';
            const links = document.querySelectorAll('nav a');
            links.forEach(link => link.classList.remove('active'));
            document.querySelector([onclick="showSection('${sectionId}')"]).classList.add('active');
        }
        showSection('about');
    </script>

 
</body>
</html>
