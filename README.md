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
            padding: 30px;
            text-align: center;
            font-size: 42px;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 3px;
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
            border-bottom: 6px solid black;
            border-radius: 0 0 20px 20px;
        }
        .container {
            width: 85%;
            margin: auto;
            overflow: hidden;
        }
        .section {
            background: rgba(255, 255, 255, 0.1);
            padding: 50px;
            margin: 50px 0;
            border-radius: 20px;
            box-shadow: 0 8px 16px rgba(255, 193, 7, 0.4);
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .section:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 30px rgba(255, 193, 7, 0.5);
        }
        .btn {
            display: inline-block;
            background: #FFD700;
            color: black;
            padding: 18px 36px;
            text-decoration: none;
            border-radius: 12px;
            font-weight: bold;
            text-transform: uppercase;
            transition: 0.3s;
            font-size: 20px;
            border: 3px solid black;
        }
        .btn:hover {
            background: black;
            color: #FFD700;
            box-shadow: 0 6px 20px rgba(255, 193, 7, 0.6);
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 40px;
        }
        .grid div {
            background: #222;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(255, 193, 7, 0.4);
            transition: transform 0.3s;
            font-size: 22px;
            border-left: 5px solid #FFD700;
        }
        .grid div:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 30px rgba(255, 193, 7, 0.5);
        }
        footer {
            background: linear-gradient(90deg, #FFD700, #FFB300);
            color: black;
            text-align: center;
            padding: 25px;
            font-weight: bold;
            text-transform: uppercase;
            margin-top: 50px;
            font-size: 20px;
            border-top: 6px solid black;
            border-radius: 20px 20px 0 0;
        }
    </style>
</head>
<body>
    <header>Mstudy - JEE & NEET Mentorship</header>
    <div class="container">
        <section class="section">
            <h2>About Mstudy</h2>
            <p>Mstudy is dedicated to providing top-notch mentorship for JEE and NEET students. Our mentors from IITs, NITs, and AIIMS guide aspirants to excel in their exams.</p>
            <a href="https://docs.google.com/forms/d/e/1FAIpQLSd5zMfQvIMBCFZCw2KhmFvyAraBxU_dNhn4aWJP5AxmCls1uA/viewform?usp=dialog" class="btn">Apply for Mentorship</a>
        </section>
        <section class="section">
            <h2>Why Choose Us?</h2>
            <div class="grid">
                <div>
                    <h3>Expert Mentors</h3>
                    <p>Guidance from IITians, NITians & AIIMS graduates.</p>
                </div>
                <div>
                    <h3>Personalized Study Plan</h3>
                    <p>Customized strategy for JEE & NEET success.</p>
                </div>
                <div>
                    <h3>Time Management Techniques</h3>
                    <p>Effective study schedules to balance Boards & JEE/NEET.</p>
                </div>
            </div>
        </section>
        <section class="section">
            <h2>Join as a Mentor</h2>
            <p>If you're from IIT, NIT, or a medical college with strong problem-solving skills, apply now.</p>
            <a href="#" class="btn">Apply Now</a>
        </section>
        <section class="section">
            <h2>Contact Us</h2>
            <p>Email: contact@mstudy.com | Phone: +91 9876543210</p>
        </section>
    </div>
    <footer>
        &copy; 2025 Mstudy. All Rights Reserved.
    </footer>
</body>
</html>
