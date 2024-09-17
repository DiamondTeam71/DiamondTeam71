- 👋 Hi, I’m @DiamondTeam71
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
DiamondTeam71/DiamondTeam71 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Explore and download applications, software, and more from IFL Store.">
    <title>IFL Store</title>
    <link rel="stylesheet" href="css/styles.css">
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }

        header {
            background: #333;
            color: #fff;
            padding: 20px 0;
            border-bottom: 4px solid #007bff;
        }

        .header-top {
            background: #444;
            color: #fff;
            padding: 10px 0;
            font-size: 14px;
            text-align: center;
        }

        .header-top p {
            margin: 0;
        }

        .header-top a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        .logo img {
            max-width: 150px;
        }

        h1 {
            text-align: center;
            font-size: 2.5em;
            margin: 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            text-align: center;
            background: #333;
            margin-top: 10px;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
            font-weight: bold;
            padding: 10px 15px;
            display: inline-block;
            border-radius: 5px;
        }

        nav ul li a:hover {
            background: #007bff;
        }

        .hero {
            background: url('img/hero-bg.jpg') no-repeat center center/cover;
            color: #fff;
            padding: 100px 0;
            text-align: center;
            position: relative;
            overflow: hidden;
            border-bottom: 4px solid #007bff;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            z-index: 1;
        }

        .hero .container {
            position: relative;
            z-index: 2;
        }

        .hero h2 {
            font-size: 3em;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.25em;
            margin-bottom: 30px;
        }

        .cta-btn {
            background: #007bff;
            color: #fff;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1.25em;
            display: inline-block;
            transition: background-color 0.3s, transform 0.3s;
        }

        .cta-btn:hover {
            background: #0056b3;
            transform: scale(1.05);
        }

        .intro, .telegram-app, .products {
            padding: 60px 0;
            text-align: center;
            background: #fff;
            border-bottom: 4px solid #ddd;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .intro h2, .telegram-app h2, .products h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .intro p, .telegram-app p {
            font-size: 1.125em;
            margin-bottom: 20px;
        }

        .product-card {
            border: 2px solid #ddd;
            padding: 20px;
            margin: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            transition: transform 0.3s, box-shadow 0.3s;
            background: #fff;
            display: inline-block;
            width: 30%;
            vertical-align: top;
        }

        .product-card:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(0,0,0,0.2);
        }

        .telegram-btn {
            background: #0088cc;
            color: #fff;
            padding: 15px 25px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.125em;
            transition: background-color 0.3s;
        }

        .telegram-btn:hover {
            background: #005f8d;
        }

        footer {
            background: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        footer a {
            color: #fff;
            text-decoration: none;
            transition: color 0.3s;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Animation */
        .animation {
            opacity: 0;
            animation: fadeIn 1s forwards;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        /* Card Animation */
        @keyframes cardZoom {
            0% {
                transform: scale(0.95);
            }
            100% {
                transform: scale(1);
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="header-top">
            <!-- Top bar with contact info or links -->
            <div class="container">
                <p><a href="'https://t.me/IFLCoin_bot">Contact Us</a></p>
            </div>
        </div>
        <div class="container">
            <!-- Website Logo -->
            <div class="logo">
                <img src="img/logo.png" alt="IFL Store Logo">
            </div>
        <section class="animation">
            <i><h1>Welcome to IFL Store</h1></i>
            <!-- Main Navigation -->
        </section>
            
             <nav>
           
                <ul>
        <section class="animation">
                    <li><a href="login.html">Login</a></li>
                    <li><a href="register.html">Register</a></li>
                    <li><a href="forgot-password.html">Forgot Password?</a></li>
                    <li><a href="products.html">Products</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
        </section>
        
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section class="fantastic animation">
            <!-- Hero section with a prominent image or call-to-action -->
            <div class="container">
                <h2>Discover Our Applications</h2>
                <p>Explore a wide range of applications and software tailored to your needs.</p>
                <a href="products.html" class="cta-btn">Browse Products</a>
            </div>
        </section>

        <section class="intro animation">
            <div class="container">
                <h2>About IFL Store</h2>
                <p>Welcome to IFL Store! Explore and download various applications, software, and more...</p>
            </div>
        </section>

        <section class="products animation">
            <div class="container">
                <h2>Our Create Various Application</h2>
                <div class="product-card" style="animation: cardZoom 0.5s ease;">
                    <h3>App 1</h3>
                    <p>Object Claim</p>
                </div>
                <div class="product-card" style="animation: cardZoom 0.5s ease;">
                    <h3>App 2</h3>
                    <p>Object Claim</p>
                </div>
                <div class="product-card" style="animation: cardZoom 0.5s ease;">
                    <h3>App 3</h3>
                    <p>Object Claim</p>
                </div>
            </div>
        </section>

        <section class="telegram-app animation">
            <div class="container">
                <h2>Telegram Mini App</h2>
                <button class="telegram-btn" onclick="window.open('https://t.me/IFLCoin_bot', '_blank')" aria-label="Open Telegram Mini App">
                    Open Telegram Mini App
                </button>
            </div>
        </section>
    </main>
    
    <footer>
        <div class="container">
            <p>&copy; 2024 IFL Store. All Rights Reserved.</p>
            <p><a href="privacy-policy.html">Privacy Policy</a> | <a href="terms.html">Terms of Service</a></p>
        </div>
    </footer>
</body>
</html>
