<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="mediaqueries.css">
</head>
<body>
    <nav id="desktop-nav">
        <div class="logo">Matthew Osko</div>
        <div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <nav id="hamburger-nav">
        <div class="logo">Matthew Osko</div>
        <div class="hamburger-menu">
            <div class="hamburger-icon" onclick="togglemenu()">
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="menu-links">
                <li><a href="#about" onclick="togglemenu()">About</a></li>
                <li><a href="#experience" onclick="togglemenu()">Experience</a></li>
                <li><a href="#projects" onclick="togglemenu()">Projects</a></li>
                <li><a href="#contact" onclick="togglemenu()">Contact</a></li>
            </div>
        </div>
    </nav>

    <section id="profile">
        <div class="section_pic-container">
            <img src="./assets/profile-pic.png" alt="Matthew Osko profile picture" />
        </div>
        <div class="section_text">
            <p class="section_text_p1">Hello, I'm</p>
            <h1 class="title">Matthew Osko</h1>
            <p class="section_text_p2">Data Analyst</p>
            <div class="btn-container">
                <button 
                    class="btn btn-color-2" 
                    onclick="window.open('./assets/resume-example.pdf')">View Resume
                </button>
                <button 
                    class="btn btn-color-1" 
                    onclick="location.href='#contact'">Contact Info
                </button>
                <div id="socials-container">
                    <img src="./assets/linkedin.png" alt="My LinkedIn Profile"
                        class="icon" onclick="location.href='https://www.linkedin.com/in/matthew-osko-3a5b10288/'"/>
                    
                    <img src="./assets/github.png" alt="My Github Profile"
                        class="icon" onclick="location.href='https://github.com/matkozb'"/>
                </div>
            </div>
        </div>
    </section>
    <section id="about"> 
        <p class="section__text__p1">Get To Know More</p>
        <h1 class="title">About Me</h1>
        <div class="section-container"></div>
            <div class="section__pic-container">
                <img src="./assets/about-pic.png"
                alt ="Profile picture"
                class = "about-pic"
                />
            </div>
        <div class="about-details-container">
            <div class="about-containers">
                <div class="details-container">
                    <img src=".assets/experience.png"
                    alt ="Experience Icon"
                    class = "icon"
                />
                <h3>Experiance</h3>
                <p>2+ years <br>Data Analysis</p>
                </div>
            <div class="details-container">
                <img src=".assets/education.png"
                    alt ="Education Icon"
                    class = "icon">
                <h3>Education</h3>
                <p>B.Sc Bachelors Degree <br>M.Sc Masters Degree</p>
            </div>
            </div>
            <div class = "text-container">
                <p>Lorem Ipsum</p>
            </div>
        </div>
        <img src=".assets/arrow.png" alt="Arrow Icon" class="icon arrow"
        onclick ="location.href='./#experience'"/>
    </section> 
    <script src="script.js"></script>
</body>
</html>
