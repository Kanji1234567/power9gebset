
#power9genset autoservice


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Power9 Genset Auto Service - Offering expert generator installation, maintenance, and repair services.">
    <meta name="keywords" content="generator, service, maintenance, repair, installation, Power9 Genset">
    <meta name="author" content="Power9 Genset">
    <title>Power9 Genset Auto Service</title>
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Open Sans', sans-serif;
            background-color: #f8f8f8;
            color: #333;
            line-height: 1.6;
            scroll-behavior: smooth;
        }

        /* Header Section */
        header {
            background-color: #00695C;
            color: white;
            text-align: center;
            padding: 50px 0;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            font-size: 3.5rem;
            letter-spacing: 2px;
            font-weight: bold;
        }

        /* Navigation */
        nav {
            background-color: #004D40;
            padding: 15px 0;
            text-align: center;
            position: sticky;
            top: 0;
            width: 100%;
            z-index: 100;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            margin: 0 20px;
            padding: 12px;
            display: inline-block;
            transition: all 0.3s ease;
        }
        nav a:hover {
            background-color: #00796b;
            border-radius: 5px;
        }

        /* Hero Section */
        .hero {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            padding: 100px 20px;
            color: white;
            text-align: center;
            border-bottom: 5px solid #00695C;
        }
        .hero h2 {
            font-size: 3.5rem;
            margin-bottom: 20px;
        }
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
        }
        .hero button {
            padding: 15px 30px;
            background-color: #00695C;
            color: white;
            border: none;
            font-size: 18px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .hero button:hover {
            background-color: #00796b;
        }

        /* Services Section */
        .section {
            padding: 80px 20px;
            text-align: center;
            background-color: #ffffff;
            margin: 40px 0;
            border-radius: 10px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }

        .services-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            flex-direction: row;
        }
        .service-item {
            background-color: #ffffff;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
            width: 280px;
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease, background-color 0.3s ease;
        }
        .service-item:hover {
            transform: scale(1.05);
            box-shadow: 0px 6px 15px rgba(0, 0, 0, 0.2);
            background-color: #f9f9f9;
        }
        .service-item i {
            font-size: 50px;
            color: #00695C;
        }
        .service-item h3 {
            font-size: 1.6rem;
            margin-top: 15px;
            color: #333;
        }

        /* Testimonials Section */
        .testimonial-carousel {
            display: flex;
            overflow-x: auto;
            gap: 20px;
            padding: 20px;
            justify-content: center;
        }
        .testimonial {
            background-color: #eeeeee;
            padding: 20px;
            border-radius: 8px;
            width: 300px;
            box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
        }
        .testimonial p {
            font-style: italic;
            margin-bottom: 15px;
        }

        /* Contact Form */
        .contact-form {
            max-width: 600px;
            margin: 30px auto;
            padding: 30px;
            background-color: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.1);
        }
        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 12px;
            margin-bottom: 15px;
            border-radius: 5px;
            border: 1px solid #ccc;
            font-size: 16px;
        }
        .contact-form button {
            width: 100%;
            padding: 15px;
            background-color: #00695C;
            color: white;
            border: none;
            font-size: 18px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .contact-form button:hover {
            background-color: #00796b;
        }

        /* Footer Section */
        footer {
            background-color: #004D40;
            color: white;
            text-align: center;
            padding: 40px 0;
            margin-top: 40px;
        }
        footer a {
            color: white;
            margin: 0 10px;
            text-decoration: none;
            font-size: 18px;
            transition: color 0.3s ease;
        }
        footer a:hover {
            color: #4CAF50;
        }
        footer .social-icons {
            margin-top: 20px;
        }
        footer .social-icons i {
            font-size: 30px;
            margin: 0 15px;
            transition: color 0.3s ease;
        }
        footer .social-icons i:hover {
            color: #00796b;
        }

        /* Scroll to Top Button */
        .scroll-top {
            position: fixed;
            bottom: 30px;
            right: 30px;
            background-color: #00695C;
            color: white;
            padding: 15px;
            border-radius: 50%;
            font-size: 24px;
            cursor: pointer;
            display: none;
            transition: all 0.3s ease;
        }
        .scroll-top:hover {
            background-color: #00796b;
        }

        /* Media Query for Mobile */
        @media (max-width: 768px) {
            .services-list {
                flex-direction: column;
                align-items: center;
            }
            .testimonial-carousel {
                flex-direction: column;
            }
        }
    </style>
    <script>
        // Scroll to Top Button functionality
        window.onscroll = function() {
            let scrollTopBtn = document.querySelector('.scroll-top');
            if (document.body.scrollTop > 300 || document.documentElement.scrollTop > 300) {
                scrollTopBtn.style.display = "block";
            } else {
                scrollTopBtn.style.display = "none";
            }
        };

        function scrollToTop() {
            document.body.scrollTop = 0;
            document.documentElement.scrollTop = 0;
        }
    </script>
</head>
<body>
    <header>
        <h1>Power9 Genset Auto Service</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="home" class="hero">
        <h2>Your Trusted Generator Experts</h2>
        <p>Installation, Maintenance, and Repair Services for Your Generators.</p>
        <button onclick="window.location.href='#contact'">Contact Us Today</button>
    </section>
    <div id="thank-you-message" style="display:none;">
        <h2>Thank You for Contacting Us!</h2>
        <p>We will get back to you shortly. Stay tuned!</p>
    </div>
    
    <section id="services" class="section">
        <h2>Our Services</h2>
        <div class="services-list">
            <div class="service-item">
                <i class="fas fa-cogs"></i>
                <h3>Installation</h3>
                <p>We offer professional generator installation services tailored to your needs, ensuring efficiency and reliability.</p>
            </div>
            <div class="service-item">
                <i class="fas fa-wrench"></i>
                <h3>Maintenance</h3>
                <p>Regular maintenance to ensure your generator is always ready to perform when you need it most.</p>
            </div>
            <div class="service-item">
                <i class="fas fa-plug"></i>
                <h3>Sales & Consultation</h3>
                <p>Explore our range of generators and get expert advice to choose the perfect one for your requirements.</p>
            </div>
            <div class="service-item">
                <i class="fas fa-headset"></i>
                <h3>Emergency Support</h3>
                <p>Our 24/7 emergency support guarantees that we are always there when you need us the most.</p>
            </div>
        </div>
    </section>

    <section id="testimonials" class="section">
        <h2>What Our Clients Say</h2>
        <div class="testimonial-carousel">
            <div class="testimonial">
                <p>"Power9 Genset's service was incredible. My generator has never run better!"</p>
                <h4>- John Doe</h4>
            </div>
            <div class="testimonial">
                <p>"Reliable and professional! I highly recommend them for all generator services."</p>
                <h4>- Jane Smith</h4>
            </div>
        </div>
    </section>

    <section id="contact" class="container section">
        <h2>Contact Us</h2>
        <form class="contact-form" name="contactForm" onsubmit="return validateForm()" method="POST" action="https://formspree.io/f/YOUR_FORM_ID">
            <!-- Name Field -->
            <input type="text" name="name" placeholder="Enter your Name" required>
    
            <!-- Email Field -->
            <input type="email" name="email" placeholder="Enter your Email" required pattern="[^@]+@[^@]+\.[^@]+" title="Please enter a valid email address.">
    
            <!-- Message Field -->
            <textarea name="message" placeholder="Write your message here..." rows="5" required></textarea>
    
            <!-- Optional Phone Field (Example) -->
            <input type="tel" name="phone" placeholder="Enter your Phone Number" pattern="(\+?[0-9]{1,3})?([0-9]{10})" title="Please enter a valid phone number.">
    
            <!-- Submit Button -->
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Power9 Genset Auto Service</p>
        <div class="social-icons">
            <a href="#"><i class="fab fa-facebook"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
            <a href="#"><i class="fab fa-linkedin"></i></a>
        </div>
    </footer>

    <button class="scroll-top" onclick="scrollToTop()">↑</button>

</body>

</html>
