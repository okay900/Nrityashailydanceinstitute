# Nrityashaily Dance Institute
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Nrityashaily Dance Institute</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="fade-in">
        <img src="logo.png" alt="Nrityashaily Dance Institute Logo" class="logo">
        <h1>Nrityashaily Dance Institute</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="gallery.html">Gallery</a>
            <a href="about.html">About Us</a>
            <a href="contact.html">Join Us</a>
        </nav>
    </header>
    <main class="fade-in">
        <section class="intro">
            <h2>Welcome to Nrityashaily</h2>
            <p>Experience the beauty of Indian classical dance with passion and discipline.</p>
        </section>
        <section class="location">
            <h3>Visit Us</h3>
            <iframe src="https://www.google.com/maps?q=Sector-3,+Vidhyadhar+Nagar,+Jaipur,+Rajasthan,+Biyani+College&output=embed" width="100%" height="300" frameborder="0" style="border:0;" allowfullscreen></iframe>
        </section>
    </main>
    <footer>
        <p>📧 ndancecarnival@gmail.com | 📸 <a href="https://instagram.com/nrityashaily_dance_institute" target="_blank">@nrityashaily_dance_institute</a></p>
    </footer>
</body>
</html>

<!-- about.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>About Us - Nrityashaily Dance Institute</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header><h1>About Nrityashaily</h1></header>
    <main class="fade-in">
        <p>Nrityashaily Dance Institute, located in Jaipur, Rajasthan, celebrates the legacy of classical Indian dance. We provide professional training in traditional dance forms with a modern perspective.</p>
    </main>
</body>
</html>

<!-- gallery.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Gallery - Nrityashaily Dance Institute</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header><h1>Dance Gallery</h1></header>
    <main class="gallery-grid">
        <img src="gallery/dance1.jpg" alt="Dance Image 1" class="fade-in">
        <img src="gallery/dance2.jpg" alt="Dance Image 2" class="fade-in">
        <img src="gallery/dance3.jpg" alt="Dance Image 3" class="fade-in">
        <img src="gallery/dance4.jpg" alt="Dance Image 4" class="fade-in">
        <img src="gallery/dance5.jpg" alt="Dance Image 5" class="fade-in">
    </main>
</body>
</html>

<!-- contact.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Join Us - Nrityashaily Dance Institute</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header><h1>Join Nrityashaily</h1></header>
    <main class="fade-in">
        <form action="mailto:ndancecarnival@gmail.com" method="post" enctype="text/plain">
            <input type="text" name="name" placeholder="Your Name"><br>
            <input type="text" name="email" placeholder="Your Email"><br>
            <textarea name="message" placeholder="Your Message"></textarea><br>
            <input type="submit" value="Send">
        </form>
    </main>
</body>
</html>

<!-- styles.css -->
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
    background: #fff8f0;
    color: #333;
}
header {
    background: #fbeec1;
    padding: 20px;
    text-align: center;
}
nav a {
    margin: 0 15px;
    text-decoration: none;
    color: #a0522d;
}
.fade-in {
    animation: fadeIn 1.5s ease-in;
}
@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}
.gallery-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    justify-content: center;
    padding: 20px;
}
.gallery-grid img {
    width: 200px;
    height: auto;
    border-radius: 10px;
}
input, textarea {
    width: 80%;
    margin: 10px auto;
    padding: 10px;
    display: block;
    border: 1px solid #ccc;
    border-radius: 5px;
}
