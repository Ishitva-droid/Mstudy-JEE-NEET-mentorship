
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>High Graphics Tech Webpage</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(135deg, #1f1c2c, #928dab);
            background-size: cover;
            animation: gradientAnimation 15s infinite;
        }

        @keyframes gradientAnimation {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .container {
            position: relative;
            width: 80%;
            height: 80%;
            background: rgba(255, 255, 255, 0.1);
            border: 2px solid rgba(255, 255, 255, 0.5);
            border-radius: 20px;
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.5);
            backdrop-filter: blur(10px);
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
        }

        .glow {
            position: absolute;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle, rgba(255,255,255,0.1), transparent);
            filter: blur(150px);
            z-index: -1;
        }

        .glow::before, .glow::after {
            content: '';
            position: absolute;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255, 0, 150, 0.2), transparent);
            animation: glowAnimation 10s infinite;
        }

        .glow::before {
            top: -50%;
            left: -50%;
        }

        .glow::after {
            bottom: -50%;
            right: -50%;
        }

        @keyframes glowAnimation {
            0% { transform: scale(1); opacity: 1; }
            50% { transform: scale(1.5); opacity: 0.5; }
            100% { transform: scale(1); opacity: 1; }
        }

        .badge-container {
            position: relative;
            width: 25%;
            height: 25%;
        }

        .badge {
            width: 100%;
            height: 100%;
        }

       <div class="badge-base LI-profile-badge" data-locale="en_US" data-size="medium" data-theme="dark" data-type="VERTICAL" data-vanity="ishitva-verma-8308b5298" data-version="v1"><a class="badge-base__link LI-simple-link" href="https://in.linkedin.com/in/ishitva-verma-8308b5298?trk=profile-badge">Ishitva Verma</a></div>
              
        .linkedin-placeholder {
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            font-size: 1.5em;
            text-align: center;
            border: 2px dashed white;
            height: 100%;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="glow"></div>
        <div class="badge-container">
            <!-- Replace this div with your LinkedIn Profile Badge Code -->
            <div class="linkedin-placeholder">Your LinkedIn Profile Badge</div>
        </div>
    </div>
</body>
</html>
