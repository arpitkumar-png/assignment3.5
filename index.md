HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alex Morgan — Portfolio & Home</title>
</head>
<body>

    <!-- Header with Name/Logo -->
    <header>
        <h1>Alex Morgan</h1>
        <p>Aspiring Front-End Web Developer & Tech Creator</p>
        
        <!-- Navigation Bar -->
        <nav aria-label="Main Navigation">
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="blog.html">Blog & Projects</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- About Me Section -->
        <section>
            <h2>About Me</h2>
            <p>Hello! I am Alex Morgan, a passionate learner currently mastering HTML foundations, semantic markup, and version control. I love turning creative design ideas into functional, accessible web experiences.</p>
        </section>

        <!-- Skills & Interests Section -->
        <section>
            <h2>Skills & Interests</h2>
            <p>Here are the core technologies and topics I am currently working with:</p>
            <ul>
                <li><strong>Technical Skills:</strong> HTML5, Semantic Markup, Git & GitHub, Basic CSS3, JavaScript Fundamentals</li>
                <li><strong>Personal Interests:</strong> UI/UX Accessibility, Open Source Collaboration, Technical Writing, Hiking</li>
            </ul>
        </section>

        <!-- Images Section -->
        <section>
            <h2>Featured Image</h2>
            <p>A glimpse of my daily setup and project workflow:</p>
            <figure>
                <img src="images/coding-workspace.jpg" alt="A well-organized wooden desk setup featuring a laptop displaying code, a mechanical keyboard, and a notebook" width="450" height="300">
                <figcaption>My primary coding and development workspace.</figcaption>
            </figure>
        </section>

        <!-- Useful Links Section -->
        <section>
            <h2>Useful Links</h2>
            <p>Check out some of my favorite learning resources and community profiles:</p>
            <ul>
                <li><a href="https://developer.mozilla.org" target="_blank" rel="noopener noreferrer">MDN Web Docs</a></li>
                <li><a href="https://github.com" target="_blank" rel="noopener noreferrer">GitHub Community</a></li>
            </ul>
        </section>
    </main>

    <!-- Footer with Contact Details -->
    <footer>
        <hr>
        <h2>Contact Details</h2>
        <p>Email: <a href="mailto:alex.morgan@example.com">alex.morgan@example.com</a></p>
        <p>GitHub: <a href="https://github.com" target="_blank" rel="noopener noreferrer">github.com/username</a></p>
        <p>&copy; 2026 Alex Morgan. All rights reserved.</p>
    </footer>

</body>
</html>
2. blog.html (Blog Posts & Projects Page)
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog & Projects — Alex Morgan</title>
</head>
<body>

    <!-- Header with Name/Logo -->
    <header>
        <h1>Alex Morgan's Tech Blog</h1>
        <p>Documenting my learning journey, coding projects, and web development discoveries.</p>
        
        <!-- Navigation Bar -->
        <nav aria-label="Main Navigation">
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="blog.html">Blog & Projects</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Blog Posts / Projects Section -->
        <section>
            <h2>Recent Blog Posts & Projects</h2>

            <article>
                <h3>Project 1: Building a Personal Portfolio from Scratch</h3>
                <p><em>Published on October 28, 2026</em></p>
                <p>In this post, I discuss how I structured my very first HTML portfolio using clean semantic elements like <code>&lt;header&gt;</code>, <code>&lt;main&gt;</code>, and <code>&lt;section&gt;</code> without relying on CSS frameworks.</p>
                
                <figure>
                    <img src="images/portfolio-preview.jpg" alt="Screenshot of a clean layout preview for a personal introduction webpage" width="400" height="250">
                    <figcaption>Initial wireframe preview of the portfolio project.</figcaption>
                </figure>
            </article>

            <article>
                <h3>Project 2: Why Accessibility Matters in Web Development</h3>
                <p><em>Published on October 29, 2026</em></p>
                <p>Accessibility ensures that websites can be used by everyone, including people relying on screen readers. Adding proper <code>alt</code> text to images and leveraging native semantic tags are critical steps toward an inclusive web.</p>
            </article>
        </section>

        <!-- Useful Links Section -->
        <section>
            <h2>Quick Resources</h2>
            <ul>
                <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank" rel="noopener noreferrer">HTML Reference Guide</a></li>
            </ul>
        </section>
    </main>

    <!-- Footer with Contact Details -->
    <footer>
        <hr>
        <h2>Contact Details</h2>
        <p>Email: <a href="mailto:alex.morgan@example.com">alex.morgan@example.com</a></p>
        <p>LinkedIn: <a href="https://linkedin.com" target="_blank" rel="noopener noreferrer">linkedin.com/in/username</a></p>
        <p>&copy; 2026 Alex Morgan. All rights reserved.</p>
    </footer>

</body>
</html>
Steps to Finalize and Submit Your Assignment:
Organize Folders: Create your main project folder. Inside it, create:

index.html (paste the first code block)

blog.html (paste the second code block)

An images/ folder containing your image files (e.g., coding-workspace.jpg and portfolio-preview.jpg) matching the code filenames.

Test Locally: Open index.html in your browser. Verify that the navigation links switch smoothly back and forth between Home and Blog pages, images load successfully with proper alt text, and lists look neat.

Commit & Push to GitHub:

Bash
git init
git add .
git commit -m "Complete Assignment 3.5: Blog and Portfolio Mini-Project"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/portfolio-mini-project.git
git push -u origin main
Final Submission: Submit your source code files (index.html, blog.html, images folder) along with your GitHub repository link!