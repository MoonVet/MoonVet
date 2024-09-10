<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moon Veterinary - Cabinet Medical Veterinar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f3f3f3;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 10px;
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
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        .call-button {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }
        .hero {
            background-color: #4a90e2; /* Culoare de fundal temporară */
            height: 60vh;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .btn {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }
        .services {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap; /* Afișare flexibilă pentru mobil */
        }
        .service {
            background-color: #f0f0f0;
            padding: 20px;
            margin: 10px;
            border-radius: 5px;
            text-align: center;
            flex: 1 1 calc(25% - 20px); /* Ajustează lățimea pe desktop */
            box-sizing: border-box;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }

        /* Media Queries pentru ecrane mai mici */
        @media (max-width: 768px) {
            header {
                flex-direction: column;
                align-items: flex-start;
            }
            nav ul {
                display: flex;
                flex-direction: column;
            }
            nav ul li {
                margin: 10px 0;
            }
            .services {
                flex-direction: column;
            }
            .service {
                flex: 1 1 100%; /* Ajustează lățimea pe mobil */
            }
            .hero {
                height: 40vh; /* Dimensiune mai mică pentru mobil */
            }
            .btn {
                padding: 10px;
            }
        }
    </style>
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
            <a href="tel:07322878057" class="call-button">Sună acum</a>
        </header>

        <section class="hero">
            <div class="hero-content">
                <h2>Îngrijim prietenii tăi necuvântători din 2022</h2>
                <p>Consultații și tratamente personalizate pentru animalele tale de companie.</p>
                <a href="#servicii" class="btn">Află mai multe</a>
            </div>
        </section>

        <section id="servicii">
            <h2>Servicii oferite</h2>
            <div class="services">
                <div class="service">
                    <h3>Consultații</h3>
                    <p>Consultații complete și personalizate.</p>
                </div>
                <div class="service">
                    <h3>Deparazitări</h3>
                    <p>Deparazitări interne și externe.</p>
                </div>
                <div class="service">
                    <h3>Vaccinări</h3>
                    <p>Vaccinări pentru sănătatea animalelor tale.</p>
                </div>
                <div class="service">
                    <h3>Tratamente</h3>
                    <p>Tratamente adaptate fiecărei situații.</p>
                </div>
            </div>
        </section>

        <footer>
            <p>Ne găsești la: Strada Mihai Eminescu, Bloc B, scara D, Deva, Jud. Hunedoara</p>
            <p>Telefon: 0732 287 057 | Email: contact@moonveterinary.ro</p>
        </footer>
    </div>
</body>
</html>
