# First-website<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* CSS: Website ko sundar banane ke liye */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            line-height: 1.6;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
            position: sticky;
            top: 0;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 20px;
            max-width: 800px;
            margin: auto;
            background: #fff;
            margin-top: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h2 {
            color: #333;
            border-bottom: 2px solid #333;
            padding-bottom: 5px;
        }
        .skills-list {
            list-style: square;
        }
        footer {
            text-align: center;
            padding: 20px;
            font-size: 0.9rem;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
        }
        button {
            background: #333;
            color: #fff;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#skills">Skills</a>
            <a href="#contact">Contact Us</a>
        </nav>
    </header>

    <section id="home">
        <h2>About Me</h2>
        <p>Hello! My name is <b>[Aapka Naam]</b>. I am a student and an aspiring web developer. I love learning new technologies and building creative projects.</p>
    </section>

    <section id="skills">
        <h2>My Skills</h2>
        <ul class="skills-list">
            <li>HTML5 & CSS3</li>
            <li>Basic JavaScript</li>
            <li>Problem Solving</li>
            <li>Microsoft Office</li>
            <li>Communication Skills</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Feel free to reach out to me:</p>
        <form>
            <label>Name:</label>
            <input type="text" placeholder="Enter your name">
            
            <label>Email:</label>
            <input type="email" placeholder="Enter your email">
            
            <label>Message:</label>
            <textarea placeholder="Your message..."></textarea>
            
            <button type="button">Submit</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2026 Created for Viva Project</p>
    </footer>

</body>
</html>
