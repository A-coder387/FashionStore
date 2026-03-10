<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trendy Fashion Store</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f5f5f5; }
        header { background: black; color: white; padding: 20px; text-align: center; }
        nav { background: #333; padding: 10px; text-align: center; }
        nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
        .products { display: flex; flex-wrap: wrap; justify-content: center; padding: 20px; }
        .product { background: white; width: 250px; margin: 15px; padding: 15px; border-radius: 8px; text-align: center; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
        button { background: black; color: white; border: none; padding: 10px 20px; cursor: pointer; border-radius: 5px; }
        button:hover { background: #444; }
        footer { background: black; color: white; text-align: center; padding: 15px; margin-top: 20px; }
    </style>
</head>
<body>

<header>
    <h1>Trendy Fashion Store</h1>
    <p>Modern Clothing for Everyone</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Men</a>
    <a href="#">Women</a>
    <a href="#">Kids</a>
</nav>

<section class="products">
    <div class="product">
        <h3>Classic Men's Shirt</h3>
        <p>$25.00</p>
        <button>Order Now</button>
    </div>
    <div class="product">
        <h3>Elegant Women's Dress</h3>
        <p>$45.00</p>
        <button>Order Now</button>
    </div>
    <div class="product">
        <h3>Cool Kids' Sneakers</h3>
        <p>$30.00</p>
        <button>Order Now</button>
    </div>
</section>

<footer>
    <p>&copy; 2026 FashionStore - Cash on Delivery Available</p>
</footer>

</body>
</html>
