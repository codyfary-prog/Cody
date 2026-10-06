# Cody
Surfing pictures 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surfing Gallery</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #eaf8ff;
            color: #123;
        }

        header {
            background: #0077b6;
            color: white;
            text-align: center;
            padding: 40px 20px;
        }

        header h1 {
            font-size: 45px;
            margin-bottom: 10px;
        }

        header p {
            font-size: 18px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            padding: 30px;
            max-width: 1200px;
            margin: auto;
        }

        .card {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            transition: transform 0.3s;
        }

        .card:hover {
            transform: scale(1.04);
        }

        .card img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            display: block;
        }

        .card h2 {
            padding: 15px;
            text-align: center;
            color: #0077b6;
        }

        footer {
            background: #023e8a;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>

<body>

    <header>
        <h1>🏄 Surfing Gallery</h1>
        <p>Ride the waves and enjoy the ocean.</p>
    </header>

    <main class="gallery">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1502680390469-be75c86b6367?auto=format&fit=crop&w=900&q=80"
                 alt="Surfer riding a wave">
            <h2>Riding the Wave</h2>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1455729552865-3658a5d39692?auto=format&fit=crop&w=900&q=80"
                 alt="Surfer in the ocean">
            <h2>Ocean Adventure</h2>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=900&q=80"
                 alt="Ocean waves">
            <h2>Perfect Waves</h2>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1500534623283-312aade485b7?auto=format&fit=crop&w=900&q=80"
                 alt="Beach and ocean">
            <h2>Beach Life</h2>
        </div>

    </main>

    <footer>
        <p>🌊 Surf • Ride • Repeat 🌊</p>
    </footer>

</body>
<HTML/>
