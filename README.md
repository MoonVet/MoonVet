<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Moon Veterinary - Cabinet Medical Veterinar în Deva. Oferim consultații, vaccinări, deparazitări și tratamente pentru animalele de companie.">
    <meta name="keywords" content="cabinet veterinar Deva, veterinar, consultații animale, vaccinări animale, deparazitări, medic veterinar Deva, animale de companie, tratamente veterinare">
    <meta name="robots" content="index, follow">
    <title>Moon Veterinary - Cabinet Medical Veterinar Deva</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
            background-color: #333;
            color: white;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        nav ul li {
            margin-right: 20px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: 500;
        }
        .social-icons a {
            color: white;
            margin-left: 15px;
            text-decoration: none;
            font-size: 1.5rem;
        }
        .call-button {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 30px;
            transition: background-color 0.3s;
        }
        .call-button:hover {
            background-color: #218838;
        }
        .hero {
            background-image: url('https://via.placeholder.com/1200x600'); /* Înlocuiește cu imagine reală */
            background-size: cover;
            background-position: center;
            height: 60vh;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            position: relative;
        }
        .hero-overlay {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(0, 0, 0, 0.5);
        }
        .hero-content {
            position: relative;
            z-index: 2;
        }
        .hero h1 {
            font-size: 3.5rem;
            margin: 0;
        }
        .hero p {
            font-size: 1.2rem;
            margin: 10px 0;
        }
        .btn {
            background-color: #28a745;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 30px;
            font-weight: 500;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #218838;
        }
        #doctor {
            text-align: center;
            margin-top: 50px;
        }
        .doctor-profile {
            display: inline-block;
            text-align: center;
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .doctor-img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            margin-bottom: 20px;
        }
        h3 {
            font-size: 1.5rem;
            margin-bottom: 10px;
            color: #333;
        }
        p {
            font-size: 1rem;
            color: #555;
        }
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 40px;
        }
        .service {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            padding: 20px;
            transition: transform 0.3s;
        }
        .service:hover {
            transform: translateY(-5px);
        }
        .service img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        #orar {
            text-align: center;
            margin-top: 50px;
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .orar ul {
            list-style-type: none;
            padding: 0;
            font-size: 1.2rem;
            color: #333;
        }
        .orar li {
            margin: 10px 0;
        }
        .orar strong {
            color: #28a745;
        }
        iframe {
            width: 100%;
            height: 400px;
            border: 0;
        }
        #contact {
            text-align: center;
            margin-top: 50px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
    <!-- SEO Schema Markup -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "VeterinaryCare",
      "name": "Moon Veterinary",
      "address": {
        "@type": "PostalAddress",
        "streetAddress": "Strada Exemplu 10",
        "addressLocality": "Deva",
        "addressRegion": "HD",
        "postalCode": "330000"
      },
      "telephone": "+407322287057",
      "description": "Cabinet Medical Veterinar care oferă consultații, vaccinări și tratamente pentru animalele de companie.",
      "openingHours": "Mo-Fr 08:00-18:00",
      "url": "https://moonveterinary.ro"
    }
    </script>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">
                <h1>Moon Veterinary</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#despre">Despre noi</a></li>
                    <li><a href="#servicii">Servicii</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
            <div class="social-icons">
                <a href="https://m.facebook.com/p/Moon-Veterinary-100083518988337/" target="_blank"><i class="fab fa-facebook"></i></a>
                <a href="https://wa.me/407322287057" target="_blank"><i class="fab fa-whatsapp"></i></a>
            </div>
        </header>

        <section class="hero">
            <div class="hero-overlay"></div>
            <div class="hero-content">
                <h1>Îngrijim prietenii tăi necuvântători din 2022</h1>
                <p>Consultații și tratamente personalizate pentru animalele tale de companie.</p>
                <a href="#servicii" class="btn">Află mai multe</a>
            </div>
        </section>

        <section id="doctor">
            <h2>Despre Doamna Doctor</h2>
            <div class="doctor-profile">
                <img src="https://exemplu.com/poza-doctor.jpg" alt="Dr. Dancila Alexandra Elena - Medic Veterinar" class="doctor-img">
                <h3>Dr. Dancila Alexandra Elena</h3>
                <p>Medic Veterinar, Specializat în chirurgie veterinară și medicină internă.</p>
            </div>
        </section>

        <section id="servicii">
            <h2>Servicii oferite</h2>
            <div class="services">
                <div class="service">
                    <img src="https://via.placeholder.com/150/0000FF/808080?text=Consultatii" alt="Consultații veterinar Deva">
                    <h3>Consultații</h3>
                    <p>Consultații complete și personalizate.</p>
                </div>
                <div class="service">
                    <img src="https://via.placeholder.com/150/FF0000/FFFFFF?text=Vaccinari" alt="Vaccinări animale Deva">
                    <h3>Vaccinări</h3>
                    <p>Vaccinări pentru sănătatea animalelor tale.</p>
                </div>
                <div class="service">
                    <img src="https://via.placeholder.com/150/FF0000/FFFFFF?text=Deparazitari" alt="Deparazitări animale">
                    <h3>Deparazitări</h3>
                    <p>Deparazitări interne și externe.</p>
                </div>
            </div>
        </section>

        <section id="orar">
            <h2>Orar</h2>
            <ul>
                <li>Luni-Vineri: <strong>08:00 - 18:00</strong></li>
                <li>Sâmbătă: <strong>09:00 - 13:00</strong></li>
                <li>Duminică: <strong>Închis</strong></li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Ne poți contacta la telefon: <strong>+407322287057</strong></p>
            <p>Ne găsești pe <a href="https://m.facebook.com/p/Moon-Veterinary-100083518988337/" target="_blank">Facebook</a> și <a href="https://wa.me/407322287057" target="_blank">WhatsApp</a>.</p>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3150.7486848283524!2d-122.08219468468194!3d37.38521897982844!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808fb0b060beff91%3A0x94e3e49cd473d18!2sGoogleplex!5e0!3m2!1sen!2sus!4v1609990821838!5m2!1sen!2sus"></iframe>
        </section>

        <footer>
            <p>&copy; 2024 Moon Veterinary. Toate drepturile rezervate.</p>
        </footer>
    </div>
</body>
</html>
