<!-- Accessibility: Skip to main content -->
<a href="#main-content">Skip to main content</a>

<!-- Header and Navigation -->
<header>
    <h1>My Portfolio</h1>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<main id="main-content">

    <!-- Hero Section -->
    <section id="hero">
        <h2>Welcome!</h2>
        <p>Hello, I am Yash, a student learning web development and building creative projects.</p>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <img src="https://img.freepik.com/free-vector/blue-circle-with-white-user_78370-4707.jpg?semt=ais_hybrid&w=740&q=80" alt="Profile picture of Yash" width="200">
        <p>
            I am passionate about technology and enjoy creating websites. 
            This is my first personal portfolio built using HTML.
        </p>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>My Projects</h2>
        <ul>
            <li><strong>Portfolio Website:</strong> A personal one-page profile.</li>
            <li><strong>Notes App:</strong> A simple app to save and view notes.</li>
            <li><strong>Calculator:</strong> A basic calculator using JavaScript.</li>
        </ul>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Technical Skills</h2>
        <table border="1" cellpadding="5">
            <tr>
                <th>Skill</th>
                <th>Level</th>
            </tr>
            <tr>
                <td>HTML</td>
                <td>Beginner</td>
            </tr>
            <tr>
                <td>CSS</td>
                <td>Beginner</td>
            </tr>
            <tr>
                <td>JavaScript</td>
                <td>Learning</td>
            </tr>
        </table>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <form action="#" method="post">
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

            <label for="message">Message:</label><br>
            <textarea id="message" name="message" placeholder="Write your message here" required></textarea><br><br>

            <button type="submit">Send</button>
        </form>
    </section>

</main>

<!-- Footer -->
<footer>
    <p>&copy; 2025 Yash | All Rights Reserved</p>
</footer>
