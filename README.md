<!DOCTYPE html>
<html lang="en-GB">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brighton Legal Partners | Personal Injury Claims Specialists</title>
    <meta name="description" content="Expert personal injury claims solicitors in England. No Win No Fee compensation claims. Free initial consultation.">
    <style>
        :root {
            --primary-color: #1a3c6c;
            --secondary-color: #c8102e;
            --accent-color: #f8f9fa;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
        }

        .header {
            background: var(--primary-color);
            padding: 1rem;
            color: white;
        }

        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }

        .nav-links {
            display: flex;
            gap: 2rem;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
        }

        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('law-bg.jpg');
            background-size: cover;
            color: white;
            text-align: center;
            padding: 4rem 1rem;
        }

        .cta-button {
            background: var(--secondary-color);
            color: white;
            padding: 1rem 2rem;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 1rem;
        }

        .services {
            padding: 3rem 1rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .service-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .service-card {
            border: 1px solid #ddd;
            padding: 1.5rem;
            border-radius: 5px;
        }

        footer {
            background: var(--primary-color);
            color: white;
            padding: 2rem 1rem;
            margin-top: 3rem;
        }

        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }

        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            
            .mobile-menu {
                display: block;
            }
        }
    </style>
</head>
<body>
    <header class="header">
        <nav class="nav-container">
            <div class="logo">BLP Legal</div>
            <div class="nav-links">
                <a href="#home">Home</a>
                <a href="#about">About Us</a>
                <a href="#services">Services</a>
                <a href="#contact">Contact</a>
            </div>
        </nav>
    </header>

    <section class="hero">
        <h1>Expert Personal Injury Claims Solicitors</h1>
        <p>No Win No Fee Compensation Claims | 24/7 Support | Accredited Specialists</p>
        <a href="#contact" class="cta-button">Start Your Free Consultation</a>
    </section>

    <section class="services" id="services">
        <h2>Our Specialisms</h2>
        <div class="service-grid">
            <div class="service-card">
                <h3>Road Traffic Accidents</h3>
                <p>Car, motorcycle, and cycling accident claims</p>
            </div>
            <div class="service-card">
                <h3>Workplace Injuries</h3>
                <p>Construction accidents and employer negligence</p>
            </div>
            <div class="service-card">
                <h3>Medical Negligence</h3>
                <p>Surgical errors and misdiagnosis claims</p>
            </div>
            <div class="service-card">
                <h3>Public Liability</h3>
                <p>Slip and fall accidents in public spaces</p>
            </div>
        </div>
    </section>

    <section class="why-choose">
        <div class="content">
            <h2>Why Choose Us?</h2>
            <ul>
                <li>✓ 100% No Win No Fee Policy</li>
                <li>✓ SRA Regulated Solicitors</li>
                <li>✓ 95% Success Rate</li>
                <li>✓ Free Case Evaluation</li>
            </ul>
        </div>
    </section>

    <section class="contact" id="contact">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Name" required>
            <input type="email" placeholder="Email" required>
            <input type="tel" placeholder="Phone Number">
            <textarea placeholder="Brief details of your case"></textarea>
            <button type="submit" class="cta-button">Submit Enquiry</button>
        </form>
    </section>

    <footer>
        <div class="footer-content">
            <div>
                <h4>Contact Details</h4>
                <p>Address: 123 High Street, London, EC1V 9LB</p>
                <p>Phone: 020 8123 4567</p>
                <p>Email: enquiries@blplegal.co.uk</p>
            </div>
            <div>
                <h4>Regulatory Information</h4>
                <p>SRA Number: 123456</p>
                <p>ICO Registration: ZA123456</p>
                <p>VAT Number: GB 123 4567 89</p>
            </div>
            <div>
                <h4>Legal</h4>
                <p><a href="/privacy">Privacy Policy</a></p>
                <p><a href="/terms">Terms of Service</a></p>
                <p><a href="/complaints">Complaints Procedure</a></p>
            </div>
        </div>
        <p style="text-align: center; margin-top: 1rem;">© 2023 BLP Legal. All rights reserved.</p>
    </footer>

    <script>
        // Mobile menu toggle
        const mobileMenu = document.createElement('div');
        mobileMenu.className = 'mobile-menu';
        mobileMenu.innerHTML = '☰';
        document.querySelector('.nav-container').appendChild(mobileMenu);
        
        mobileMenu.addEventListener('click', () => {
            document.querySelector('.nav-links').classList.toggle('show');
        });
    </script>
</body>
</html># bobman
