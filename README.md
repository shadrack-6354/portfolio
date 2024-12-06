# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* Basic Reset */
        body, h1, h2, p, ul, li, img {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* General Body Styling */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #010005; /* Dark Gray Background */
            color: white;
            line-height: 1.6;
        }

        /* Header Styling */
        header {
            background-color: #cf7817; /* Orange Background */
            color: white;
            text-align: center;
            padding: 50px 0;
        }

        header h1 {
            font-size: 3rem;
        }

        /* Container for all sections */
        .container {
            width: 80%;
            margin: 0 auto;
        }

        /* Section Styling */
        section {
            margin: 50px 0;
        }

        section h2 {
            font-size: 2rem;
            color: #4d06f1;
            text-align: center;
            border-bottom: 2px solid #cf7817;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        /* Biography Section */
        .biography {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }

        .biography img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            margin-bottom: 20px;
        }

        .biography p {
            font-size: 1.2rem;
        }

        /* Goal, Education, Skills, Interests, References Sections */
        .content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }

        .content div {
            flex: 0 0 48%;
            margin-bottom: 30px;
            padding: 20px;
            background-color: #0c8910;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        }

        .content div h3 {
            color: #17cf23;
            margin-bottom: 15px;
        }

        /* List Styles */
        ul {
            list-style-type: none;
            padding: 0;
        }

        ul li {
            padding: 5px 0;
            font-size: 1.1rem;
        }

        footer {
            background-color: #020202; /* Orange Background */
            color: white;
            text-align: center;
            padding: 20px;
        }

        footer a {
            color: rgb(46, 2, 167);
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>

<header>
    <h1>My Portfolio</h1>
</header>

<div class="container">

    <!-- Biography Section -->
    <section class="biography">
        <h2>Biography</h2>
        <img src="biopic.jpg" alt="Your Photo">
        <p><strong>Name:</strong> SHADRACK SETH</p>
        <p><strong>Date of Birth:</strong> JULY, 5 2004</p>
        <p><strong>Gender:</strong> MALE</p>
        <p><strong>Phone Number:</strong> +254 714 552 502</p>
        <p><strong>Email:</strong> shadrackseth0@gmail.com</p>
        <p><strong>Location:</strong> KAKAMEGA, KENYA</p>
    </section>

    <!-- Goal Section -->
    <section>
        <h2>Goal</h2>
        <div class="content">
            <div>
                <h3>Career Objectives</h3>
                <p>My goal is to become a full-stack developer who creates efficient, scalable, and user-friendly web applications. I am committed to continuous learning and improving my skills to contribute to impactful projects in the tech world.</p>
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section>
        <h2>Education</h2>
        <div class="content">
            <div>
                <h3>Formal Education</h3>
                <ul>
                    <li><strong>Web Development Bootcamp</strong> -Power Learn Project(2024)</li>
                    <li><strong>Digital Literacy Program</strong> - Nairobits (2024)</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section>
        <h2>Skills</h2>
        <div class="content">
            <div>
                <h3>Technical Skills</h3>
                <ul>
                    <li>HTML5, CSS3, JavaScript</li>
                    <li>Digital Marketing</li>
                    <li>Responsive Web Design</li>
                    <li>Graphic Design</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Interests Section -->
    <section>
        <h2>Interests</h2>
        <div class="content">
            <div>
                <h3>Personal Interests</h3>
                <ul>
                    <li>Traveling and experiencing new cultures</li>
                    <li>Gaming</li>
                    <li>Reading technology and self-improvement books</li>
                    <li>Exploring new web technologies and frameworks</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- References Section -->
    <section>
        <h2>Referees</h2>
        <div class="content">
            <div>
                <h3>Professional Referees</h3>
                <ul>
                    <li><strong>Opetu Vincent</strong> -Instructional Designer/Tech Mastery Guide/Tech Visionary Director at Nairobits <br> Email: opetu@nairobits.com</li>
                    <li><strong>Likuyi Jared</strong> - Project Director at Amalemba Child Development Centre <br> Email: ictjared@gmail.com</li>
                </ul>
            </div>
        </div>
    </section>

</div>

<footer>
    <p>&copy; shadrack seth | <a href="shadrackseth0@gmail.com">Contact Me</a>+254 714 552 502</p>
</footer>

</body>
</html>
