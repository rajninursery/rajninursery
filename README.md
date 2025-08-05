
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Rajni Nursery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f9f0;
            color: #2d472d;
        }
        header {
            background-color: #4CAF50;
            padding: 20px;
            text-align: center;
            color: white;
        }
        nav {
            background-color: #388E3C;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        h1, h2 {
            color: #2e7d32;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .gallery img {
            width: 300px;
            height: 200px;
            object-fit: cover;
        }
        form {
            max-width: 400px;
            margin: auto;
            text-align: left;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        footer {
            background-color: #2E7D32;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
        .whatsapp-btn {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #25D366;
            color: white;
            border-radius: 50%;
            width: 60px;
            height: 60px;
            font-size: 30px;
            text-align: center;
            line-height: 60px;
            text-decoration: none;
            box-shadow: 2px 2px 10px rgba(0,0,0,0.3);
        }
    </style>
</head>
<body>

    <header>
        <h1>Rajni Nursery</h1>
        <p>Greenery That Grows With Love</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="home">
        <h2>Welcome to Rajni Nursery</h2>
        <img src="https://images.unsplash.com/photo-1587502537150-4c1d23714f9c" alt="Nursery Image">
        <p>We provide a wide range of plants, trees, and greenery solutions to make your space beautiful and eco-friendly.</p>
    </section>

    <section id="gallery">
        <h2>Our Plants Gallery</h2>
        <div class="gallery">
            <img src="https://images.unsplash.com/photo-1501004318641-b39e6451bec6" alt="Plant 1">
            <img src="https://images.unsplash.com/photo-1616401788028-4f3f881a4e3d" alt="Plant 2">
            <img src="https://images.unsplash.com/photo-1587300003388-59208cc962cb" alt="Plant 3">
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form action="#" method="post">
            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Your Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <input type="submit" value="Send Message">
        </form>
    </section>

    <section id="map">
        <h2>Visit Us</h2>
        <iframe 
            src="https://www.google.com/maps?q=chamarawali,ramgarh,greater%20noida&output=embed" 
            width="100%" 
            height="300" 
            style="border:0;" 
            allowfullscreen="" 
            loading="lazy">
        </iframe>
    </section>

    <footer>
        <p>📞 9354077042 | WhatsApp: 9548051962</p>
        <p>📧 harendrakashyap497@gmail.com</p>
        <p>📍 Chamarawali, Ramgarh, Greater Noida</p>
    </footer>

    <!-- WhatsApp Chat Button -->
    <a class="whatsapp-btn" href="https://wa.me/919548051962" target="_blank" title="Chat with us on WhatsApp">
        💬
    </a>

</body>
</html>
