<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OP WATCHES | Premium Store</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
        body { background-color: #f9f9f9; color: #333; }
        
        /* Navbar */
        nav { background: #fff; padding: 15px 5%; display: flex; justify-content: space-between; align-items: center; border-bottom: 1px solid #ddd; position: sticky; top: 0; }
        .logo { font-size: 24px; font-weight: 700; color: #000; }
        .nav-links { display: flex; gap: 20px; font-size: 14px; font-weight: 600; }
        .nav-links span { cursor: pointer; }

        /* Hero */
        .hero { padding: 60px 5%; text-align: center; background: #000; color: #fff; }
        
        /* Products */
        .product-section { padding: 40px 5%; display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
        .card { background: #fff; padding: 20px; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.05); text-align: center; }
        .card img { width: 100%; height: 250px; object-fit: cover; border-radius: 8px; margin-bottom: 15px; }
        .card h3 { font-size: 18px; margin-bottom: 5px; }
        .price { font-weight: 700; color: #e67e22; font-size: 18px; margin-bottom: 15px; }
        .btn-buy { background: #000; color: #fff; border: none; padding: 12px 20px; border-radius: 5px; width: 100%; cursor: pointer; font-weight: 600; }
        
        /* Footer */
        footer { background: #000; color: #fff; text-align: center; padding: 30px; margin-top: 50px; font-size: 14px; }
    </style>
</head>
<body>

    <nav>
        <div class="logo">OP WATCHES</div>
        <div class="nav-links">
            <span>Search</span>
            <span>Account</span>
            <span>Cart (0)</span>
        </div>
    </nav>

    <div class="hero">
        <h1>Premium Timepieces</h1>
        <p>Explore our exclusive collection</p>
    </div>

    <div class="product-section">
        <!-- Product 1 -->
        <div class="card">
            <img src="https://images.unsplash.com/photo-1524805444758-089113d48a6d?auto=format&fit=crop&w=500&q=80" alt="Watch">
            <h3>OP Royal Classic</h3>
            <p class="price">Update Price Here</p>
            <button class="btn-buy" onclick="window.open('https://wa.me/91XXXXXXXXXX?text=I want to buy OP Royal Classic')">Order on WhatsApp</button>
        </div>

        <!-- Product 2 -->
        <div class="card">
            <img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?auto=format&fit=crop&w=500&q=80" alt="Watch">
            <h3>OP Gold Chrono</h3>
            <p class="price">Update Price Here</p>
            <button class="btn-buy" onclick="window.open('https://wa.me/91XXXXXXXXXX?text=I want to buy OP Gold Chrono')">Order on WhatsApp</button>
        </div>
    </div>

    <footer>
        <p>© 2026 OP WATCHES. All Rights Reserved.</p>
        <p>⚡ Co-founded by OM NEMADE & PRAJWAL BHOI ⚡</p>
    </footer>

</body>
</html>
