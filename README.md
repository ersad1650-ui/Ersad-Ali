<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ProStore | Download Latest Apps & Games</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
        body { background-color: #f0f2f5; color: #333; }

        /* Header Style */
        header {
            background: #ffffff;
            padding: 15px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        .logo { font-size: 24px; font-weight: 600; color: #01875f; } /* Play Store Green */
        .search-bar { background: #f1f3f4; border-radius: 8px; padding: 8px 15px; width: 40%; border: none; outline: none; }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #01875f 0%, #1a73e8 100%);
            color: white;
            padding: 60px 5%;
            text-align: center;
        }

        /* Main Container */
        .container { padding: 40px 5%; }
        .section-title { margin-bottom: 25px; font-size: 22px; border-left: 5px solid #01875f; padding-left: 15px; }

        /* Grid System */
        .app-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
            gap: 25px;
        }

        /* App Card Style */
        .app-card {
            background: white;
            border-radius: 18px;
            padding: 15px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            text-align: center;
            cursor: pointer;
            text-decoration: none;
            color: inherit;
        }
        .app-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        .app-card img {
            width: 100px;
            height: 100px;
            border-radius: 22%;
            object-fit: cover;
            margin-bottom: 12px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.05);
        }
        .app-card h3 { font-size: 16px; margin-bottom: 5px; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
        .app-card p { font-size: 13px; color: #666; margin-bottom: 10px; }
        .rating { color: #fbbc04; font-size: 12px; margin-bottom: 10px; }

        /* Download Button */
        .btn-dl {
            background: #01875f;
            color: white;
            padding: 8px 20px;
            border-radius: 20px;
            text-decoration: none;
            font-size: 14px;
            display: inline-block;
        }
        
        footer { text-align: center; padding: 40px; color: #888; font-size: 14px; }
    </style>
</head>
<body>

<header>
    <div class="logo">ProStore</div>
    <input type="text" class="search-bar" placeholder="Search apps or games...">
    <div class="nav-links">Login</div>
</header>

<section class="hero">
    <h1>Discover New Apps & Games</h1>
    <p>Hand-picked premium tools and entertainment for you.</p>
</section>

<div class="container">
    <h2 class="section-title">Trending Now</h2>
    <div class="app-grid">
        
        <!-- App Card 1 -->
        <div class="app-card">
            <img src="https://cdn-icons-png.flaticon.com/512/2111/2111615.png" alt="App Icon">
            <h3>Cyber Shield VPN</h3>
            <p>Security • 45MB</p>
            <div class="rating">★★★★★ 4.9</div>
            <a href="#" class="btn-dl">Install</a>
        </div>

        <!-- App Card 2 -->
        <div class="app-card">
            <img src="https://cdn-icons-png.flaticon.com/512/681/681392.png" alt="Game Icon">
            <h3>Speed Racer 2026</h3>
            <p>Racing • 1.2GB</p>
            <div class="rating">★★★★☆ 4.5</div>
            <a href="#" class="btn-dl">Install</a>
        </div>

        <!-- App Card 3 -->
        <div class="app-card">
            <img src="https://cdn-icons-png.flaticon.com/512/5968/5968260.png" alt="Tool Icon">
            <h3>Photo Pro Editor</h3>
            <p>Tools • 32MB</p>
            <div class="rating">★★★★★ 4.8</div>
            <a href="#" class="btn-dl">Install</a>
        </div>

        <!-- App Card 4 -->
        <div class="app-card">
            <img src="https://cdn-icons-png.flaticon.com/512/174/174883.png" alt="App Icon">
            <h3>Youtube Mod</h3>
            <p>Video • 80MB</p>
            <div class="rating">★★★★☆ 4.2</div>
            <a href="#" class="btn-dl">Install</a>
        </div>

    </div>
</div>

<footer>
    &copy; 2026 ProStore Inc. All rights reserved.
</footer>

</body>
</html>
