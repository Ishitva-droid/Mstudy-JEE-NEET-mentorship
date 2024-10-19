# ishitva-droid.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sharda Prasad Jewellers - Luxury Jewelry</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Poppins', sans-serif;
            background-color: #f7f7f7;
            color: #333;
        }
        /* Navbar */
        nav {
            background-color: #fff;
            padding: 10px 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
            position: fixed;
            width: 100%;
            z-index: 1000;
        }
        nav a {
            text-decoration: none;
            color: #333;
            margin: 0 20px;
            font-weight: 500;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #bfa64b;
        }
        .logo {
            font-family: 'Playfair Display', serif;
            font-size: 30px;
            color: #bfa64b;
        }
        /* Hero Section */
        .hero {
            background-image: url('hero-banner.jpg'); /* Add a hero banner */
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            position: relative;
        }
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.6); /* Dark overlay */
        }
        .hero h1 {
            font-family: 'Playfair Display', serif;
            font-size: 60px;
            position: relative;
            z-index: 2;
        }
        .hero p {
            font-size: 20px;
            position: relative;
            z-index: 2;
        }
        .cta-btn {
            display: inline-block;
            padding: 12px 30px;
            background-color: #bfa64b;
            color: white;
            border-radius: 30px;
            text-decoration: none;
            transition: background-color 0.3s ease;
            margin-top: 20px;
            font-weight: bold;
        }
        .cta-btn:hover {
            background-color: #a5873b;
        }
        /* Jewelry Collection Section */
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 50px 20px;
        }
        .collection-title {
            text-align: center;
            font-size: 35px;
            font-family: 'Playfair Display', serif;
            margin-bottom: 50px;
            color: #333;
        }
        .jewelry-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        .jewelry-item {
            background-color: #fff;
            padding: 20px;
            text-align: center;
            border-radius: 10px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        }
        .jewelry-item:hover {
            transform: translateY(-10px);
            box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.2);
        }
        .jewelry-item img {
            max-width: 100%;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .jewelry-item h3 {
            font-family: 'Playfair Display', serif;
            font-size: 24px;
            color: #bfa64b;
            margin-bottom: 10px;
        }
        .jewelry-item p {
            font-size: 16px;
            color: #666;
        }
        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 30px 0;
        }
        footer a {
            color: white;
            margin: 0 10px;
            text-decoration: none;
        }
        footer a:hover {
            color: #bfa64b;
        }
        footer p {
            font-size: 14px;
            margin: 0;
        }
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 40px;
            }
            .hero p {
                font-size: 18px;
            }
        }
    </style>
</head>
<body>

<!-- Navbar -->
<nav>
    <div class="logo">Sharda Prasad Jewellers</div>
    <div>
        <a href="#">Home</a>
        <a href="#">Collection</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </div>
</nav>

<!-- Hero Section -->
<div class="hero">
    <div>
        <h1>Luxury Jewelry for Every Occasion</h1>
        <p>Explore our exclusive collection of gold, diamond, and silver jewelry.</p>
        <a href="#" class="cta-btn">Discover Now</a>
    </div>
</div>

<!-- Jewelry Collection Section -->
<div class="container">
    <h2 class="collection-title">Our Exclusive Collection</h2>
    <div class="jewelry-grid">
        <!-- Jewelry Item 1 -->
        <div class="jewelry-item">
            <img src="gold-pendant.jpg" alt="Gold Pendant">
            <h3>Gold Pendant</h3>
            <p>Elegant and timeless gold pendants, crafted for perfection.</p>
        </div>
        <!-- Jewelry Item 2 -->
        <div class="jewelry-item">
            <img src="silver-anklet.jpg" alt="Silver Anklet">
            <h3>Silver Anklet</h3>
            <p>Intricately designed silver anklets that add grace to every step.</p>
        </div>
        <!-- Jewelry Item 3 -->
        <div class="jewelry-item">
            <img src="diamond-necklace.jpg" alt="Diamond Necklace">
            <h3>Diamond Necklace</h3>
            <p>A dazzling diamond necklace that defines elegance and luxury.</p>
        </div>
    </div>
</div>

<!-- Footer -->
<footer>
    <p>&copy; 2024 Sharda Prasad Jewellers, Shohratgarh, Siddharthnagar. All Rights Reserved.</p>
    <p>
        <a href="#">Facebook</a> | 
        <a href="#">Instagram</a> | 
        <a href="#">Twitter</a>
    </p>
</footer>

</body>
</html>
