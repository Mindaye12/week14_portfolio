<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mindaye Bogale Defaru | Portfolio</title>
    <style>
        /* --- General Styles --- */
        body {
            font-family: 'Roboto', Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        a {
            color: #0077cc;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        html {
            scroll-behavior: smooth;
        }
        /* --- Header --- */
        header {
            background-color: #fff;
            padding: 20px 40px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header h1 {
            margin: 0;
            font-size: 28px;
        }
        nav a {
            margin-left: 20px;
            font-weight: bold;
        }
        /* --- Hero Section --- */
        .hero {
            text-align: center;
            padding: 80px 20px;
            background-color: #e8f0fe;
        }
        .hero h2 {
            font-size: 24px;
            margin-bottom: 20px;
        }
        .hero img {
            width: 150px;
            height: 150px;
            max-width: 40%;
            border-radius: 50%;
            object-fit: cover;
        }
        /* --- Sections --- */
        section {
            padding: 60px 20px;
            max-width: 900px;
            margin: 0 auto;
        }
        section h2 {
            font-size: 28px;
            margin-bottom: 20px;
            border-bottom: 2px solid #0077cc;
            display: inline-block;
            padding-bottom: 5px;
        }
        section:nth-of-type(even) {
            background-color: #f0f4f8;
        }
        .portfolio-item {
            margin-bottom: 20px;
        }
        .portfolio-item a {
            display: inline-block;
            padding: 8px 16px;
            background-color: #0077cc;
            color: white;
            border-radius: 4px;
            margin-top: 5px;
        }
        .portfolio-item a:hover {
            background-color: #005fa3;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #fff;
            color: #777;
            border-top: 1px solid #ddd;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Mindaye B Defaru</h1>
        <nav>
            <a href="#bio">Bio</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#elevator">Elevator Pitch</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <div class="hero">
        <img src="https://via.placeholder.com/150" alt="Mindaye Bogale">
        <h2>Mechatronics & Robotics Enthusiast | Aspiring Automation Engineer</h2>
    </div>

    <!-- Bio Section -->
    <section id="bio">
        <h2>Bio</h2>
        <p>
            Hello! I am Mindaye B Defaru, a passionate electromechanical engineer specializing in robotics,
            automation, and embedded systems. I have hands-on experience with Raspberry Pi, Arduino, and SolidWorks,
            and I focus on creating innovative solutions for real-world problems in sectors such as tech, agriculture, and healthcare.
            My long-term vision is to establish a socially-driven robotics and AI company that empowers local communities, and to create a tech-innovation academy to inspire the next generation of African engineers.

I strive to be a versatile engineer and personal development leader, making a global impact while rooted in Africa.
        </p>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="portfolio-item">
            <strong>Phase 2 Project Video:</strong> 
            <a href="https://youtu.be/Ct_lYLIblRg?si=K20-Q9tMXWyL6WxQ" target="_blank">Watch on YouTube</a>
        </div>
        <div class="portfolio-item">
            <strong>Phase 2 Project Slide Deck:</strong> 
            <a href="https://drive.google.com/file/d/147X_9rzF2ThYNExeL4qhclnFwgGgEAz5/view?usp=sharing" target="_blank">View PDF</a>
        </div>
    </section>

    <!-- Elevator Pitch Section -->
    <section id="elevator">
        <h2>Elevator Pitch</h2>
        <p>
            Hello! I am Mindaye B Defaru, an electromechanical engineer passionate about robotics and automation.
            I specialize in designing practical solutions that bridge technology with real-world challenges, particularly
            in agriculture and healthcare. My hands-on experience with Raspberry Pi, Arduino, and SolidWorks allows me
            to prototype efficient, innovative systems quickly. I aspire to lead projects that bring sustainable,
            tech-driven impact to communities, leveraging automation and smart robotics to solve everyday problems.
        </p>
    </section>

    <!-- Footer -->
    <footer>
        &copy; 2025 Mindaye Bogale Defaru | All Rights Reserved
    </footer>

</body>
</html>
