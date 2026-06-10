<!DOCTYPE html>
<html lang="en">
<head>
    <!-- =========================================
         BASIC SEO
    ========================================== -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Sumanraj | Data Scientist & Business Analyst</title>

    <meta name="description"
          content="Portfolio of Sumanraj - Data Scientist and Business Analyst showcasing projects, skills, certifications, experience and analytics portfolio.">

    <meta name="keywords"
          content="Data Scientist, Business Analyst, Portfolio, Python, SQL, Power BI, Machine Learning, Data Analytics">

    <meta name="author" content="Sumanraj">

    <!-- Open Graph -->
    <meta property="og:title" content="Sumanraj | Data Scientist & Business Analyst">
    <meta property="og:description" content="Professional Portfolio Website">
    <meta property="og:type" content="website">

    <!-- Favicon -->
    <link rel="icon" href="assets/images/favicon.png">

    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap"
          rel="stylesheet">

    <!-- Icons -->
    <link rel="stylesheet"
          href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

    <!-- Styles -->
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/responsive.css">
</head>

<body>

<!-- =========================================
     LOADER
========================================== -->

<div id="loader">
    <div class="loader-spinner"></div>
</div>

<!-- =========================================
     BACK TO TOP
========================================== -->

<button id="backToTop" aria-label="Back To Top">
    <i class="fas fa-arrow-up"></i>
</button>

<!-- =========================================
     HEADER
========================================== -->

<header class="header">

    <nav class="navbar container">

        <a href="#" class="logo">
            Sumanraj
        </a>

        <ul class="nav-links">

            <li><a href="#about">About</a></li>

            <li><a href="#skills">Skills</a></li>

            <li><a href="#projects">Projects</a></li>

            <li><a href="#experience">Experience</a></li>

            <li><a href="#github">GitHub</a></li>

            <li><a href="#certifications">Certificates</a></li>

            <li><a href="#contact">Contact</a></li>

        </ul>

        <div class="nav-actions">

            <button id="themeToggle"
                    class="theme-toggle"
                    aria-label="Theme Toggle">

                <i class="fas fa-moon"></i>

            </button>

            <button id="menuBtn" class="menu-btn">

                <i class="fas fa-bars"></i>

            </button>

        </div>

    </nav>

</header>

<!-- =========================================
     HERO SECTION
========================================== -->

<section class="hero" id="home">

    <div class="container hero-container">

        <div class="hero-content">

            <span class="hero-tag">
                Data Science • Analytics • Business Intelligence
            </span>

            <h1 id="heroName">
                Sumanraj
            </h1>

            <h2 class="typing-container">

                <span id="typingText"></span>

            </h2>

            <p id="heroDescription">

                Aspiring Data Scientist and Business Analyst passionate
                about transforming data into actionable insights.

            </p>

            <div class="hero-buttons">

                <a href="assets/resume/resume.pdf"
                   class="btn btn-primary"
                   download>

                    Download Resume

                </a>

                <a href="#contact"
                   class="btn btn-secondary">

                    Contact Me

                </a>

            </div>

            <div class="social-icons">

                <a id="linkedinLink" href="#" target="_blank">
                    <i class="fab fa-linkedin"></i>
                </a>

                <a id="githubLink" href="#" target="_blank">
                    <i class="fab fa-github"></i>
                </a>

                <a id="emailLink" href="#">
                    <i class="fas fa-envelope"></i>
                </a>

            </div>

        </div>

        <div class="hero-image">

            <div class="profile-card">

                <img
                    id="profileImage"
                    src="assets/images/profile.jpg"
                    alt="Profile Image">

            </div>

        </div>

    </div>

</section>

<!-- =========================================
     ABOUT SECTION
========================================== -->

<section id="about" class="section">

    <div class="container">

        <div class="section-title">

            <h2>About Me</h2>

            <p>Professional Summary</p>

        </div>

        <div class="about-grid">

            <div class="about-content">

                <p id="aboutText">

                    About information will be loaded
                    from portfolio-data.js

                </p>

            </div>

            <div class="about-cards">

                <div class="info-card">

                    <h4>Education</h4>

                    <p id="educationInfo">
                        Update Later
                    </p>

                </div>

                <div class="info-card">

                    <h4>Specialization</h4>

                    <p>
                        Data Science & Analytics
                    </p>

                </div>

                <div class="info-card">

                    <h4>Career Goal</h4>

                    <p>
                        Data Scientist / Business Analyst
                    </p>

                </div>

            </div>

        </div>

    </div>

</section>

<!-- =========================================
     STATISTICS
========================================== -->

<section class="stats-section">

    <div class="container">

        <div class="stats-grid">

            <div class="stat-card">

                <h3 class="counter" data-target="15">0</h3>

                <p>Projects</p>

            </div>

            <div class="stat-card">

                <h3 class="counter" data-target="10">0</h3>

                <p>Certificates</p>

            </div>

            <div class="stat-card">

                <h3 class="counter" data-target="2">0</h3>

                <p>Internships</p>

            </div>

            <div class="stat-card">

                <h3 class="counter" data-target="25">0</h3>

                <p>Repositories</p>

            </div>

        </div>

    </div>

</section>

<!-- =========================================
     SKILLS
========================================== -->

<section id="skills" class="section">

    <div class="container">

        <div class="section-title">

            <h2>Skills</h2>

            <p>Technical Expertise</p>

        </div>

        <div id="skillsContainer"
             class="skills-container">

        </div>

    </div>

</section>

<!-- =========================================
     PROJECTS
========================================== -->

<section id="projects" class="section">

    <div class="container">

        <div class="section-title">

            <h2>Projects</h2>

            <p>Featured Work</p>

        </div>

        <div id="projectFilters"
             class="project-filters">

        </div>

        <div id="projectsContainer"
             class="projects-grid">

        </div>

    </div>

</section>

<!-- =========================================
     EXPERIENCE
========================================== -->

<section id="experience"
         class="section">

    <div class="container">

        <div class="section-title">

            <h2>Experience</h2>

            <p>Journey Timeline</p>

        </div>

        <div id="timelineContainer"
             class="timeline">

        </div>

    </div>

</section>

<!-- =========================================
     GITHUB SHOWCASE
========================================== -->

<section id="github"
         class="section">

    <div class="container">

        <div class="section-title">

            <h2>GitHub Showcase</h2>

            <p>Latest Repositories</p>

        </div>

        <div id="githubRepos"
             class="github-grid">

        </div>

    </div>

</section>

<!-- =========================================
     CERTIFICATIONS
========================================== -->

<section id="certifications"
         class="section">

    <div class="container">

        <div class="section-title">

            <h2>Certifications</h2>

            <p>Professional Learning</p>

        </div>

        <div id="certificationContainer"
             class="certificate-grid">

        </div>

    </div>

</section>

<!-- =========================================
     CONTACT
========================================== -->

<section id="contact"
         class="section">

    <div class="container">

        <div class="section-title">

            <h2>Contact Me</h2>

            <p>Let's Connect</p>

        </div>

        <div class="contact-grid">

            <div class="contact-info">

                <div class="contact-card">

                    <i class="fas fa-envelope"></i>

                    <h4>Email</h4>

                    <p id="contactEmail">
                        your@email.com
                    </p>

                </div>

                <div class="contact-card">

                    <i class="fab fa-linkedin"></i>

                    <h4>LinkedIn</h4>

                    <p>
                        Professional Network
                    </p>

                </div>

                <div class="contact-card">

                    <i class="fab fa-github"></i>

                    <h4>GitHub</h4>

                    <p>
                        Project Repository
                    </p>

                </div>

            </div>

            <form id="contactForm"
                  class="contact-form">

                <input type="text"
                       placeholder="Your Name"
                       required>

                <input type="email"
                       placeholder="Your Email"
                       required>

                <input type="text"
                       placeholder="Subject"
                       required>

                <textarea rows="6"
                          placeholder="Message"
                          required>
                </textarea>

                <button type="submit"
                        class="btn btn-primary">

                    Send Message

                </button>

            </form>

        </div>

    </div>

</section>

<!-- =========================================
     FOOTER
========================================== -->

<footer>

    <div class="container">

        <div class="footer-content">

            <h3>Sumanraj</h3>

            <p>
                Data Scientist • Business Analyst
            </p>

            <div class="footer-social">

                <a href="#">
                    <i class="fab fa-linkedin"></i>
                </a>

                <a href="#">
                    <i class="fab fa-github"></i>
                </a>

                <a href="#">
                    <i class="fas fa-envelope"></i>
                </a>

            </div>

            <p class="copyright">

                © 2026 Sumanraj.
                All Rights Reserved.

            </p>

        </div>

    </div>

</footer>

<!-- =========================================
     SCRIPTS
========================================== -->

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

<script src="data/portfolio-data.js"></script>

<script src="js/main.js"></script>

<script src="js/github.js"></script>

<script src="js/darkmode.js"></script>

</body>
</html>
