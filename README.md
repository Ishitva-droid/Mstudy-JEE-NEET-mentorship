<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy New Year 2025</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(135deg, #ff0000, #00ff00, #0000ff);
            background-size: 400% 400%;
            animation: gradient 10s ease infinite;
            font-family: Arial, sans-serif;
        }

        @keyframes gradient {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .container {
            text-align: center;
            color: white;
            padding: 20px;
            border: 5px solid white;
            border-radius: 15px;
            background: rgba(0, 0, 0, 0.5);
            box-shadow: 0 0 20px rgba(255, 255, 255, 0.7);
        }

        .hearts {
            font-size: 2rem;
            animation: pulse 1.5s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }

        .flower {
            font-size: 1.5rem;
        }

        input {
            padding: 10px;
            font-size: 16px;
            border: none;
            border-radius: 5px;
            margin: 10px 0;
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
            color: white;
            background-color: #ff69b4;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #ff1493;
        }

        .message {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🎉✨ Happy New Year 2025! ✨🎉</h1>
        <p class="hearts">❤️🩷❤️‍🔥🤍🩵</p>
        <p class="flower">🌸✨🌙😇🐿️🥰</p>
        <p>Enter your name to personalize your wish:</p>
        <input type="text" id="userName" placeholder="Your Name">
        <button onclick="generateMessage()">Generate Wish</button>
        <div id="wishMessage" class="message"></div>
    </div>

    <script>
        function generateMessage() {
            const name = document.getElementById('userName').value;
            if (name.trim() === "") {
                alert("Please enter your name to proceed!");
                return;
            }
            const wishContainer = document.getElementById('wishMessage');
            wishContainer.innerHTML = `
                <h2>Dear <strong>${name}</strong>,</h2>
                <p>May 2025 be your best year yet, filled with love, success, and endless happiness. 🌟 Let’s make unforgettable memories and chase dreams together. Here's to an extraordinary year ahead! ~ Ishitva (Mayuk) </p>
                <p class="hearts">❤️🌙✨🤗🩵🩷🤍❤️‍🔥❤️</p>
            `;
        }
    </script>
</body>
</html>
