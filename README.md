<fashion shope
<html>
<head>
    <title>Mohit Fashion Store</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        header {
            background: black;
            color: white;
            padding: 15px;
            text-align: center;
        }

        nav {
            background: #333;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: gold;
        }

        .hero {
            background: url('https://images.unsplash.com/photo-1523381210434-271e8be1f52b') no-repeat center;
            background-size: cover;
            height: 400px;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 40px;
            font-weight: bold;
        }

        .products {
            padding: 40px;
            text-align: center;
        }

        .product-box {
            display: inline-block;
            width: 250px;
            margin: 20px;
            border: 1px solid #ddd;
            padding: 15px;
        }

        .product-box img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }

        button {
            background: black;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
        }

        button:hover {
            background: gold;
            color: black;
        }

        footer {
            background: black;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
    </style>
</head>

<body>

<header>
    <h1>Mohit Fashion Store</h1>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Shop</a>
    <a href="#">New Arrivals</a>
    <a href="#">Contact</a>
</nav>

<div class="hero">
    Style That Defines You
</div>

<section class="products">
    <h2>Our Products</h2>

    <div class="product-box">
        <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab">
        <h3>Casual T-Shirt</h3>
        <p>₹799</p>
        <button>Buy Now</button>
    </div>

    <div class="product-box">
        <img src="https://images.unsplash.com/photo-1541099649105-f69ad21f3246">
        <h3>Denim Jacket</h3>
        <p>₹1999</p>
        <button>Buy Now</button>
    </div>

    <div class="product-box">
        <img src="https://images.unsplash.com/photo-1514996937319-344454492b37">
        <h3>Stylish Hoodie</h3>
        <p>₹1499</p>
        <button>Buy Now</button>
    </div>

</section>

<footer>
    © 2026 Mohit Fashion Store | All Rights Reserved
</footer>

</body>
</html>