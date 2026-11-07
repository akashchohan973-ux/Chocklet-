<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chocklet with Akash | Sweet Treats & Ice Creams</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Pacifico&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #fff8f0;
            color: #333;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(135deg, #4a2e18, #2c1810);
            color: #fff;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
        }
        header h1 {
            font-family: 'Pacifico', cursive;
            font-size: 3rem;
            color: #ffb703;
            margin-bottom: 5px;
        }
        header p {
            font-size: 1.1rem;
            letter-spacing: 1px;
            color: #ffd166;
        }
        .banner {
            background: #ffb703;
            color: #000;
            text-align: center;
            padding: 12px;
            font-weight: 700;
            font-size: 1.2rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            animation: pulse 1.5s infinite;
        }
        @keyframes pulse {
            0% { opacity: 1; }
            50% { opacity: 0.8; }
            100% { opacity: 1; }
        }
        .container {
            max-width: 1100px;
            margin: 40px auto;
            padding: 0 20px;
        }
        .section-title {
            text-align: center;
            font-size: 2.2rem;
            color: #4a2e18;
            margin-bottom: 30px;
            position: relative;
        }
        .section-title::after {
            content: '';
            width: 80px;
            height: 4px;
            background-color: #ffb703;
            display: block;
            margin: 8px auto 0;
            border-radius: 2px;
        }
        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            margin-bottom: 50px;
        }
        .card {
            background: #fff;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 6px 15px rgba(0,0,0,0.08);
            transition: transform 0.3s ease;
            text-align: center;
            padding: 30px 20px;
            border-bottom: 5px solid #ffb703;
        }
        .card:hover {
            transform: translateY(-8px);
        }
        .card h3 {
            font-size: 1.5rem;
            color: #4a2e18;
            margin-bottom: 10px;
        }
        .card p {
            color: #666;
            font-size: 0.95rem;
        }
        .flavors-list {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
            margin-top: 15px;
        }
        .flavor-badge {
            background-color: #ffe8d6;
            color: #b7410e;
            padding: 6px 15px;
            border-radius: 20px;
            font-weight: 600;
            font-size: 0.9rem;
        }
        .info-box {
            background: #4a2e18;
            color: #fff;
            border-radius: 15px;
            padding: 40px;
            text-align: center;
            margin-bottom: 50px;
        }
        .info-box h2 {
            font-size: 2rem;
            color: #ffb703;
            margin-bottom: 15px;
        }
        .info-box p {
            font-size: 1.2rem;
            margin-bottom: 10px;
        }
        footer {
            background: #2c1810;
            color: #aaa;
            text-align: center;
            padding: 20px 0;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Chocklet with Akash</h1>
        <p>Pure Indulgence & Fully Yummy Taste!</p>
    </header>

    <!-- New Customer Offer Banner -->
    <div class="banner">
        🎉 Special Offer for New Customers! Visit today and get a special discount on your first order! 🎉
    </div>

    <div class="container">
        
        <!-- Menu / Specialties -->
        <h2 class="section-title">Our Delicious Specialties</h2>
        <div class="menu-grid">
            <div class="card">
                <h3>🍫 Chocolate Brownie Cake</h3>
                <p>Rich, moist, and loaded with heavenly chocolate flavor. Baked fresh to satisfy your ultimate sweet cravings!</p>
            </div>
            <div class="card">
                <h3>🍦 Premium Ice Creams</h3>
                <p>Creamy, smooth, and delicious ice creams crafted to perfection for a refreshing treat.</p>
                <div class="flavors-list">
                    <span class="flavor-badge">Pista</span>
                    <span class="flavor-badge">Strawberry</span>
                    <span class="flavor-badge">Pineapple</span>
                </div>
            </div>
        </div>

        <!-- Visit Us / Address Section -->
        <div class="info-box">
            <h2>Come Visit Us!</h2>
            <p>Experience the fully yummy taste in person.</p>
            <p><strong>📍 Address:</strong> Waliv, Vasai, Maharashtra</p>
        </div>

    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Chocklet with Akash. All Rights Reserved.</p>
    </footer>

</body>
</html>
