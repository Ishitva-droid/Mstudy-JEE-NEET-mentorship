<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mstudy - JEE & NEET Mentorship</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Baloo+Bhai+2:wght@400;700&family=Poppins:wght@300;500;700&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: #121212;
            color: white;
        }
        header {
            background: linear-gradient(90deg, #FFD700, #FFB300);
            color: black;
            padding: 40px;
            text-align: center;
            font-size: 48px;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 3px;
            border-bottom: 8px solid black;
            border-radius: 0 0 25px 25px;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.4);
        }
        .container {
            width: 90%;
            margin: auto;
            overflow: hidden;
            padding: 20px 0;
        }
        .hero {
            text-align: center;
            padding: 80px 20px;
            background: url('https://source.unsplash.com/1600x900/?education') center/cover no-repeat;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(255, 193, 7, 0.5);
        }
        .hero h1 {
            font-size: 50px;
            background: rgba(0, 0, 0, 0.7);
            display: inline-block;
            padding: 20px;
            border-radius: 15px;
        }
        .section {
            background: rgba(255, 255, 255, 0.1);
            padding: 60px;
            margin: 50px 0;
            border-radius: 25px;
            box-shadow: 0 10px 25px rgba(255, 193, 7, 0.4);
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .section:hover {
            transform: scale(1.05);
            box-shadow: 0 12px 35px rgba(255, 193, 7, 0.6);
        }
        .btn {
            display: inline-block;
            background: #FFD700;
            color: black;
            padding: 20px 40px;
            text-decoration: none;
            border-radius: 15px;
            font-weight: bold;
            text-transform: uppercase;
            transition: 0.3s;
            font-size: 22px;
            border: 4px solid black;
        }
        .btn:hover {
            background: black;
            color: #FFD700;
            box-shadow: 0 8px 25px rgba(255, 193, 7, 0.6);
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 50px;
            text-align: left;
        }
        .grid div {
            background: #222;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 8px 20px rgba(255, 193, 7, 0.4);
            transition: transform 0.3s;
            font-size: 24px;
            border-left: 6px solid #FFD700;
        }
        .grid div:hover {
            transform: translateY(-10px);
            box-shadow: 0 12px 35px rgba(255, 193, 7, 0.5);
        }
        footer {
            background: linear-gradient(90deg, #FFD700, #FFB300);
            color: black;
            text-align: center;
            padding: 30px;
            font-weight: bold;
            text-transform: uppercase;
            font-size: 22px;
            border-top: 8px solid black;
            border-radius: 25px 25px 0 0;
        }
    </style>
</head>
<body>
    <header>Mstudy - JEE & NEET Mentorship</header>
    <div class="container">
        <div class="hero">
            <h1>Your Gateway to JEE & NEET Success</h1>
        </div>
        <section class="section">
            <h2>About Mstudy</h2>
            <p>Mstudy provides expert mentorship for JEE and NEET aspirants. Get guided by the best mentors from IITs, NITs, and AIIMS.</p>
        </section>
        <section class="section">
            <h2>Why Choose Us?</h2>
            <div class="grid">
                <div>
                    <h3>Top Mentors</h3>
                    <p>Learn from IITians, NITians & AIIMS graduates.</p>
                </div>
                <div>
                    <h3>Personalized Strategy</h3>
                    <p>Custom study plans tailored to your needs.</p>
                </div>
                <div>
                    <h3>Smart Study Techniques</h3>
                    <p>Master time management and efficient learning.</p>
                </div>
            </div>
        </section>
        <section class="section">
            <h2>Become a Mentor</h2>
            <p>Are you from IIT, NIT, or a top medical college? Join us as a mentor today.</p>
            <a href="#" class="btn">Apply Now</a>
        </section>
        <section class="section">
            <h2>Get in Touch</h2>
            <p>Email: contact@mstudy.com | Phone: +91 9876543210</p>
        </section>
    </div>
    <footer>
        &copy; 2025 Mstudy. All Rights Reserved.
    </footer>
</body>
</html>
