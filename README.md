//html//
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="name-title">
                <h1>Lakshmi Chaitanya</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#about">About Me</a></li>
                    <li><a href="#what-i-do">What I Do</a></li>
                    <li><a href="#expertise">My Expertise</a></li>
                    <li><a href="#coding-profiles">Coding Profiles</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#achievements">Achievements</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <!-- About Me Section -->
        <section id="about" class="section about">
            <div class="container about-grid">
                <div class="about-image">
                    <img src="C:\Users\lakshmmi chaitanya\OneDrive\Desktop\wd\cy.jpg" alt="Profile Picture">
                </div>
                <div class="about-text">
                    <h2>About Me</h2>
                    <p>As a dedicated cybersecurity aspirant, I am passionate about safeguarding digital assets and fortifying systems against cyber threats. With strong coding abilities and a keen eye for detail, I am ready to tackle real-world challenges through trial jobs and internships. My background in programming and cybersecurity principles equips me with the tools to analyze, identify, and mitigate vulnerabilities effectively. Eager to learn and adapt in this dynamic field, I am committed to contributing to the security landscape while continuously honing my skills. Let’s collaborate to create secure and resilient digital environments!</p>
                </div>
            </div>
        </section>

        <!-- What I Do Section -->
        <section id="what-i-do" class="section what-i-do">
            <div class="container">
                <h2>What I Do</h2>
                <div class="grid cols-4">
                    <div class="expertise-item">
                        <i class="fas fa-code"></i>
                        <h3>Web Development</h3>
                        <p>Building responsive and modern web applications.</p>
                    </div>
                    <div class="expertise-item">
                        <i class="fas fa-paint-brush"></i>
                        <h3>Design</h3>
                        <p>Creating visually appealing designs.</p>
                    </div>
                    <div class="expertise-item">
                        <i class="fas fa-chart-line"></i>
                        <h3>SEO</h3>
                        <p>Optimizing websites for search engines.</p>
                    </div>
                    <div class="expertise-item">
                        <i class="fas fa-database"></i>
                        <h3>Database Management</h3>
                        <p>Managing and maintaining databases.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- My Expertise Section -->
        <section id="expertise" class="section expertise">
            <div class="container">
                <h2>My Expertise</h2>
                <div class="grid cols-3 skills-grid">
                    <div class="skill-item">
                        <i class="fas fa-html5"></i>
                        <h3>HTML</h3>
                        <p>Experienced in HTML for creating web pages.</p>
                    </div>
                    <div class="skill-item">
                        <i class="fas fa-css3-alt"></i>
                        <h3>CSS</h3>
                        <p>Skilled in CSS for styling web pages.</p>
                    </div>
                    <div class="skill-item">
                        <i class="fas fa-js-square"></i>
                        <h3>JavaScript</h3>
                        <p>Proficient in JavaScript for dynamic functionality.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Coding Profiles Section -->
        <section id="coding-profiles" class="section coding-profiles">
            <div class="container">
                <h2>Coding Profiles</h2>
                <div class="grid cols-3">
                    <div class="profile-item">
                        <i class="fab fa-github"></i>
                        <h3>GitHub</h3>
                        <p>View my code repositories.</p>
                        <a href="https://github.com/LakshmiChaitanyaB" target="_blank" class="cta-button"><i class="fas fa-link"></i> View Profile</a>
                    </div>
                    <div class="profile-item">
                        <i class="fab fa-stack-overflow"></i>
                        <h3>Stack Overflow</h3>
                        <p>Check out my contributions.</p>
                        <a href="https://stackoverflow.com/users/yourprofile" target="_blank" class="cta-button"><i class="fas fa-link"></i> View Profile</a>
                    </div>
                    <div class="profile-item">
                        <i class="fab fa-linkedin"></i>
                        <h3>LinkedIn</h3>
                        <p>Connect with me professionally.</p>
                        <a href="https://linkedin.com/in/lakshmi-chaitanya-85b56627a" target="_blank" class="cta-button"><i class="fas fa-link"></i> View Profile</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Featured Projects Section -->
        <section id="projects" class="section projects">
            <div class="container">
                <h2>Featured Projects</h2>
                <div class="grid cols-3 projects-grid">
                    <div class="project-item">
                        <i class="fas fa-laptop-code"></i>
                        <h3>Music Player and URL Shortner</h3>
                        <p>Developed a Python-based music player that allows users to play, pause, and navigate through their favorite songs with an intuitive GUI, utilizing libraries like Pygame for audio handling and Tkinter for the interface.</p>
                        <a href="#" class="cta-button"><i class="fas fa-link"></i> View Project</a>
                    </div>
                    <div class="project-item">
                        <i class="fas fa-laptop-code"></i>
                        <h3>SQL Injection Detection and Prevention in Database Using PHP </h3>
                        <p>Developed a PHP-based system for detecting and preventing SQL injection attacks in databases. The system employs prepared statements and parameterized queries to secure database interactions, ensuring robust protection against unauthorized access and data manipulation.

                        </p>
                        <a href="#" class="cta-button"><i class="fas fa-link"></i> View Project</a>
                    </div>
                    <div class="project-item">
                        <i class="fas fa-laptop-code"></i>
                        <h3>Secure Ether Transfer System Using Blockchain</h3>
                        <p>Developed a secure Ether transfer system on the Ethereum blockchain, enabling seamless transfers between different accounts within a network. Leveraged Remix IDE for smart contract development and MetaMask for secure wallet integration, ensuring robust and transparent transactions.</p>
                        <a href="#" class="cta-button"><i class="fas fa-link"></i> View Project</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Achievements Section -->
        <section id="achievements" class="section achievements">
            <div class="container">
                <h2>Achievements</h2>
                <div class="grid cols-3 achievements-grid">
                    <div class="achievement-item">
                        <i class="fas fa-award"></i>
                        <h3>CDAC</h3>
                        <p>Pragmatic Approach for Cyber Security</p>
                    </div>
                    <div class="achievement-item">
                        <i class="fas fa-award"></i>
                        <h3>CISCO</h3>
                        <p>Cyber Security for Beginners and intermediate level</p>
                    </div>
                    <div class="achievement-item">
                        <i class="fas fa-award"></i>
                        <h3>Ethical Hacking</h3>
                        <p>Edufabrica</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="section contact">
            <div class="container">
                <h2>Contact</h2>
                <div class="contact-form">
                    <form action="#">
                        <label for="name">Name</label>
                        <input type="text" id="name" name="name" required>

                        <label for="email">Email</label>
                        <input type="email" id="email" name="email" required>

                        <label for="message">Message</label>
                        <textarea id="message" name="message" required></textarea>

                        <button type="submit" class="cta-button"><i class="fas fa-paper-plane"></i> Send Message</button>
                    </form>
                </div>
            </div>
        </section>

        <!-- Footer Section -->
        <footer>
            <div class="container">
                <div class="social-icons">
                    <a href="https://instagram.com/yourprofile" target="_blank"><i class="fab fa-instagram"></i></a>
                    <a href="https://twitter.com/yourprofile" target="_blank"><i class="fab fa-twitter"></i></a>
                    <a href="https://github.com/yourprofile" target="_blank"><i class="fab fa-github"></i></a>
                    <a href="https://linkedin.com/in/yourprofile" target="_blank"><i class="fab fa-linkedin"></i></a>
                </div>
                <a href="C:\Users\lakshmmi chaitanya\OneDrive\Desktop\wd\resume.pdf.docx" download class="cta-button"><i class="fas fa-download"></i> Download Resume</a>
                <p>&copy; 2024 LakshmiChaitanya. All rights reserved.</p>
            </div>
        </footer>
    </main>
</body>
</html>

