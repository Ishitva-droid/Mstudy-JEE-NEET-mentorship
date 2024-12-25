<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surprise for Ishika Didi</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: #fbe3e8;
            text-align: center;
        }

        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        h1 {
            color: #e63946;
            font-size: 3rem;
        }

        p {
            color: #6d6875;
            font-size: 1.5rem;
        }

        .heart {
            font-size: 5rem;
            color: #e63946;
            animation: pulse 1s infinite;
        }

        @keyframes pulse {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.2);
            }
        }

        .button {
            margin-top: 20px;
            padding: 15px 30px;
            font-size: 1.2rem;
            color: white;
            background-color: #6a4c93;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .button:hover {
            background-color: #9c89b8;
        }

        #popup {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.8);
            z-index: 1000;
            text-align: center;
        }

        #popup img {
            width: 70%;
            max-width: 800px;
            margin-top: 50px;
            border-radius: 10px;
        }

        #popup h2 {
            color: white;
            font-size: 2.5rem;
            margin-top: 20px;
        }

        #popup .heart {
            font-size: 6rem;
        }

        #popup .button {
            margin-top: 20px;
            background-color: #457b9d;
        }

        .party-popper {
            position: absolute;
            top: 20px;
            right: 20px;
            width: 80px;
            animation: popper 2s ease-in-out forwards;
            display: none;
        }

        @keyframes popper {
            0% {
                opacity: 0;
                transform: scale(0.5);
            }
            50% {
                opacity: 1;
                transform: scale(1.2);
            }
            100% {
                opacity: 0;
                transform: scale(1.5);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Surprise for the Best Sister!</h1>
        <p>Thank you, Ishika Didi, for being the most amazing sister ever!</p>
        <div class="heart">❤️</div>
        <button class="button" onclick="revealSurprise()">Press Here for a Special Surprise</button>
    </div>

    <div id="popup">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/60/Himalayas_panorama.jpg" alt="Himalayas" id="himalayas">
        <h2><span class="heart">❤️</span> Thank You Didi! <span class="heart">❤️</span></h2>
        <img src="https://upload.wikimedia.org/wikipedia/commons/e/ec/Confetti.png" alt="Party Popper" class="party-popper" id="popper">
        <button class="button" onclick="closePopup()">Close</button>
    </div>

    <script>
        function revealSurprise() {
            document.querySelector('#popup').style.display = 'block';
            const popper = document.querySelector('#popper');
            popper.style.display = 'block';
            setTimeout(() => popper.style.display = 'none', 2000); // Hide party popper after animation
        }

        function closePopup() {
            document.querySelector('#popup').style.display = 'none';
        }
    </script>
</body>
</html>
