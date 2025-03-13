<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Playway Kids School</title>
    <link href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2&family=Pacifico&family=Poppins:wght@300;400;700&family=Chewy&family=Fredoka+One&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: radial-gradient(circle, #FFF5E1, #FFD3A5);
            text-align: center;
            color: #444;
            overflow-x: hidden;
        }
        header {
            background: url('header-bg.png') no-repeat center/cover;
            color: white;
            padding: 30px;
            font-size: 40px;
            font-family: 'Chewy', cursive;
            text-shadow: 4px 4px 10px rgba(0,0,0,0.3);
            border-radius: 0 0 50% 50%;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin: 40px auto;
            padding: 30px;
            background: #FFD166;
            border-radius: 50px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
            font-family: 'Baloo Bhai 2', cursive;
            width: 80%;
            position: relative;
            transform: rotate(-2deg);
        }
        .section:nth-child(even) {
            transform: rotate(2deg);
            background: #06D6A0;
            color: white;
        }
        h2 {
            font-family: 'Fredoka One', cursive;
            font-size: 32px;
            color: #D7263D;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .gallery img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 50%;
            box-shadow: 5px 5px 15px rgba(0,0,0,0.2);
        }
        .students {
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        .student-card {
            background: #ff477e;
            padding: 20px;
            border-radius: 50%;
            color: white;
            font-size: 18px;
            font-weight: bold;
            width: 120px;
            height: 120px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 3px 3px 10px rgba(0,0,0,0.2);
        }
        button {
            background: #06D6A0;
            border: none;
            padding: 12px 25px;
            color: white;
            font-size: 20px;
            cursor: pointer;
            border-radius: 30px;
            transition: 0.3s;
            font-family: 'Baloo Bhai 2', cursive;
        }
        button:hover {
            background: #118AB2;
        }
        footer {
            background: linear-gradient(135deg, #118AB2, #06D6A0);
            color: white;
            padding: 20px;
            margin-top: 40px;
            font-family: 'Pacifico', cursive;
            border-radius: 50% 50% 0 0;
        }
    </style>
</head>
<body>
    <header>
        🌸 Welcome to Playway Kids School 🌸
    </header>
    <div class="container">
        <div class="section">
            <h2>About Us</h2>
            <p>Playway Kids School is a place where learning is fun! We provide a nurturing environment for children to grow and explore.</p>
        </div>
        <div class="section">
            <h2>Our Programs</h2>
            <p>We offer a variety of play-based learning programs designed for early childhood development.</p>
            <button>Learn More</button>
        </div>
        <div class="section">
            <h2>Upcoming Events</h2>
            <p>🎉 Annual Sports Day - March 20th</p>
            <p>🎭 Drama & Theatre Fest - April 5th</p>
            <p>🎨 Art & Craft Exhibition - April 15th</p>
        </div>
        <div class="section">
            <h2>Student of the Month</h2>
            <div class="students">
                <div class="student-card">👦 Aryan Sharma</div>
                <div class="student-card">👧 Anaya Verma</div>
                <div class="student-card">👦 Rohan Gupta</div>
            </div>
        </div>
        <div class="section">
            <h2>Photo Gallery</h2>
            <div class="gallery">
                <img src="kids_playing.jpg" alt="Kids Playing">
                <img src="art_class.jpg" alt="Art Class">
                <img src="sports_day.jpg" alt="Sports Day">
                <img src="music_fun.jpg" alt="Music Fun">
            </div>
        </div>
        <div class="section">
            <h2>Fun Learning Activities</h2>
            <p>🎵 Music & Dance</p>
            <p>🎨 Creative Art</p>
            <p>📚 Storytelling Sessions</p>
            <p>⚽ Sports & Outdoor Games</p>
        </div>
        <div class="section">
            <h2>Contact Us</h2>
            <p>Email: info@playwayschool.com</p>
            <p>Phone: +91 9876543210</p>
        </div>
    </div>
    <footer>
        &copy; 2025 Playway Kids School | All Rights Reserved | Designed with ❤️
    </footer>
</body>
</html>
