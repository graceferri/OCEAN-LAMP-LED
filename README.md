<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>OCEAN LAMP</title>

<style>

/* ===============================
   COLOR VARIABLES
=================================*/
:root {
  --navy: #0a192f;
  --light-blue: #64b5f6;
  --white: #ffffff;
}

/* ===============================
   GLOBAL STYLING
=================================*/
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', sans-serif;
}

body {
  background: var(--navy);
  color: var(--white);
  overflow-x: hidden;
}

/* ===============================
   NAVIGATION
=================================*/
nav {
  position: fixed;
  width: 100%;
  background: rgba(10,25,47,0.9);
  backdrop-filter: blur(8px);
  padding: 15px 50px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  z-index: 1000;
}

nav h1 {
  color: var(--light-blue);
  letter-spacing: 2px;
}

nav ul {
  display: flex;
  list-style: none;
  gap: 25px;
}

nav ul li a {
  text-decoration: none;
  color: var(--white);
  transition: 0.3s;
}

nav ul li a:hover {
  color: var(--light-blue);
}

/* ===============================
   HERO SECTION
=================================*/
.hero {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  text-align: center;
  background: linear-gradient(135deg, var(--navy), #112240);
}

.hero h2 {
  font-size: 4rem;
  color: var(--light-blue);
  animation: fadeIn 2s ease-in-out;
}

.hero p {
  margin-top: 20px;
  font-size: 1.3rem;
  max-width: 600px;
  animation: slideUp 2s ease-in-out;
}

/* ===============================
   ABOUT SECTION
=================================*/
section {
  padding: 100px 50px;
}

.about {
  background: var(--white);
  color: var(--navy);
  border-radius: 30px 30px 0 0;
}

.about h2 {
  text-align: center;
  margin-bottom: 30px;
}

.about p {
  max-width: 800px;
  margin: auto;
  text-align: center;
  line-height: 1.8;
}

/* ===============================
   IMAGE SCROLLER
=================================*/
.image-slider {
  background: var(--navy);
  padding: 50px 0;
  overflow: hidden;
}

.slider-track {
  display: flex;
  width: calc(250px * 10);
  animation: scroll 20s linear infinite;
}

.slider-track img {
  width: 250px;
  height: 180px;
  object-fit: cover;
  margin: 0 15px;
  border-radius: 15px;
  transition: transform 0.3s;
}

.slider-track img:hover {
  transform: scale(1.1);
}

/* Animation for scrolling */
@keyframes scroll {
  0% { transform: translateX(-50%); }
  100% { transform: translateX(0); }
}

/* ===============================
   FOOTER
=================================*/
footer {
  background: #112240;
  text-align: center;
  padding: 30px;
  color: var(--light-blue);
}

/* ===============================
   ANIMATIONS
=================================*/
@keyframes fadeIn {
  from {opacity: 0;}
  to {opacity: 1;}
}

@keyframes slideUp {
  from {transform: translateY(40px); opacity: 0;}
  to {transform: translateY(0); opacity: 1;}
}

</style>
</head>

<body>

<!-- ===============================
     NAVIGATION
=================================-->
<nav>
  <h1>OCEAN LAMP</h1>
  <ul>
    <li><a href="#about">About</a></li>
    <li><a href="#gallery">Gallery</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<!-- ===============================
     HERO SECTION
=================================-->
<div class="hero">
  <h2>OCEAN LAMP</h2>
  <p>Creative Developer | Designer | Innovator  
  <!-- ✏️ EDIT THIS TEXT WITH YOUR PERSONAL INTRO -->
  </p>
</div>

<!-- ===============================
     ABOUT SECTION
=================================-->
<section id="about" class="about">
  <h2>About Me</h2>
  <p>
    <!-- ✏️ EDIT THIS SECTION WITH YOUR DETAILS -->
    Grace and Ekin are two  MYP/IB highschoolers girls that wanted to create a fun object to use in evryday life no matter in what situation you are in. That's why they created this Ocean Lamp with LED lights in it. Grace and Ekin thanks to this lamp, discovered also their passion for the ocean and for water animals. This lamp is made of recycled plastic which helps the world, not only it's recycled but also it gives your room a cozy vibe. 
  </p>
</section>

<!-- ===============================
     IMAGE GALLERY (AUTO SCROLL)
=================================-->
<section id="gallery" class="image-slider">
  <div class="slider-track">
    <!-- 
      📂 Replace image names with your own images.
      Put your images inside the "images" folder.
    -->
    <img src="images/image1.jpg">
    <img src="images/image2.jpg">
    <img src="images/image3.jpg">
    <img src="images/image4.jpg">
    <img src="images/image5.jpg">

    <!-- Duplicate images for seamless loop -->
    <img src="images/image1.jpg">
    <img src="images/image2.jpg">
    <img src="images/image3.jpg">
    <img src="images/image4.jpg">
    <img src="images/image5.jpg">
  </div>
</section>

<!-- ===============================
     CONTACT SECTION
=================================-->
<section id="contact" class="about">
  <h2>Contact</h2>
  <p>
    <!-- ✏️ EDIT WITH YOUR CONTACT INFO -->
    Email: graceelisabethf@gmail.com & ekinilgaz11@gmail.com
    GitHub: yourgithub
  </p>
</section>

<!-- ===============================
     FOOTER
=================================-->
<footer>
  © 2026 OCEAN LAMP | All Rights Reserved
</footer>

</body>
</html>
