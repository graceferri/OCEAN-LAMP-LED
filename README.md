<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>OceanGlow Lamp</title>

<!-- Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Poppins', sans-serif;
        scroll-behavior: smooth;
    }

    body {
        background: linear-gradient(to bottom, #021B33, #033E6B, #0A6E8C);
        color: white;
    }

    header {
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        text-align: center;
        background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e') no-repeat center center/cover;
        background-blend-mode: overlay;
        background-color: rgba(0,0,0,0.6);
        animation: fadeIn 2s ease-in-out;
    }

    header h1 {
        font-size: 3.5rem;
        letter-spacing: 2px;
    }

    header p {
        margin-top: 20px;
        font-size: 1.2rem;
        max-width: 600px;
    }

    .btn {
        margin-top: 30px;
        padding: 12px 30px;
        border: none;
        background: #00C2D1;
        color: #021B33;
        font-weight: bold;
        border-radius: 30px;
        cursor: pointer;
        transition: 0.4s;
    }

    .btn:hover {
        background: white;
        transform: scale(1.1);
    }

    section {
        padding: 80px 10%;
        text-align: center;
    }

    h2 {
        margin-bottom: 40px;
        font-size: 2.5rem;
        color: #00E0FF;
    }

    .features, .materials {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 30px;
    }

    .card {
        background: rgba(255,255,255,0.1);
        padding: 30px;
        border-radius: 15px;
        backdrop-filter: blur(10px);
        transition: 0.4s;
    }

    .card:hover {
        transform: translateY(-10px);
        background: rgba(255,255,255,0.2);
    }

    .gallery img {
        width: 100%;
        border-radius: 15px;
        transition: 0.5s;
    }

    .gallery img:hover {
        transform: scale(1.05);
    }

    .contact-box {
        background: rgba(0,0,0,0.5);
        padding: 40px;
        border-radius: 15px;
        max-width: 600px;
        margin: 0 auto;
    }

    footer {
        text-align: center;
        padding: 20px;
        background: #011522;
        margin-top: 40px;
    }

    @keyframes fadeIn {
        from {opacity: 0;}
        to {opacity: 1;}
    }

</style>
</head>
<body>

<header>
    <h1>OceanGlow LED Lamp</h1>
    <p>It brings the calm beauty of the ocean into your space with a handcrafted LED ocean lamp designed to relax and inspire. You can use it in everyday life in any occasion that you are in. Wanna go to an Aquerium?? No problem buy the OceanGlow Lamp with Led lights and it will look like you are in an actaul aquerium.</p>
    <button class="btn" onclick="document.getElementById('about').scrollIntoView()">Discover More</button>
</header>

<section id="about">
    <h2>About The Lamp</h2>
    <p>The OceanGlow LED Lamp recreates the peaceful waves of the ocean using layered resin art and soft LED lighting technology. Perfect for bedrooms, offices, and relaxation spaces. It is also made with recycled plastic for helping the animals that live in the oceans, and that won't die if we use this recycled plastic.</p>
</section>

<section>
    <h2>Features</h2>
    <div class="features">
        <div class="card">
            <h3> Ocean Effect</h3>
            <p>Realistic wave design crafted with recycled plastic that gives a more realistic effect.</p>
        </div>
        <div class="card">
            <h3> LED Lighting</h3>
            <p>Energy efficient LED lights with any type of colours that you request, it has a switch where you can turn it on or off.</p>
        </div>
        <div class="card">
            <h3> Handmade Design</h3>
            <p>Each lamp is uniquely handcrafted with recycled materials.</p>
      </div>
      <div class= "card">
           <h3> Restrictions with the object</h3>
           <p>CHildren under the age of 6 can't use this product, it can give risk of hurting the children or they can break it. </p>
        </div>
    </div>
</section>

<section>
    <h2>Gallery</h2>
    <div class="gallery features">
        <!-- Replace these with your own images -->
        <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e" alt="Ocean Lamp Image 1">
        <img src="https://images.unsplash.com/photo-1493558103817-58b2924bce98" alt="Ocean Lamp Image 2">
        <img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470" alt="Ocean Lamp Image 3">
    </div>
</section>

<section>
    <h2>Materials Used</h2>
    <div class="materials">
        <div class="card">
            <p>✔ Made with love</p>
            <p>✔ Recycled Plastic used</p>
            <p>✔ High Quality LED lights</p>
            <p>✔ Acrylic Protective Layer</p>
        </div>
    </div>
</section>

<section>
    <h2>Creator Contact</h2>
    <div class="contact-box">
        <p><strong>Name:</strong> Grace Elisabeth Ferri & Ekin Ilgaz</p>
        <p><strong>Email:</strong> graceelisabethf@gmail.com & ekinilgaz11@gmail.com</p>
        <p><strong>Instagram:</strong> grace_ferri_ & ekin.ilgazz</p>
    </div>
</section>

<footer>
    <p>© 2026 OceanGlow LED Lamp | Designed with Passion 🌊</p>
</footer>

</body>
</html>
