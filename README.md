# metamorphmedia.com
At Metamorph Media, we don’t just redesign websites—we reimagine them. Whether your current site feels outdated, underperforms, or no longer reflects your brand’s evolution, we craft modern, user-centric websites that captivate audiences and drive results.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WebCare Pro | Website Maintenance Services</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/milligram/1.4.1/milligram.min.css">
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
        }
        .hero {
            padding: 4rem 0;
            background: #f8f9fa;
            text-align: center;
        }
        .services {
            padding: 3rem 0;
        }
        .price-card {
            border: 1px solid #ddd;
            padding: 2rem;
            margin: 1rem;
            border-radius: 5px;
            text-align: center;
        }
        footer {
            background: var(--primary-color);
            color: white;
            padding: 2rem 0;
            margin-top: 3rem;
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="navigation">
        <section class="container">
            <a href="#home" class="navigation-title">WebCare Pro</a>
            <ul class="navigation-list float-right">
                <li class="navigation-item"><a href="#services" class="navigation-link">Services</a></li>
                <li class="navigation-item"><a href="#pricing" class="navigation-link">Pricing</a></li>
                <li class="navigation-item"><a href="#contact" class="navigation-link">Contact</a></li>
            </ul>
        </section>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1>Professional Website Maintenance</h1>
            <p>Keep your website secure, updated, and running smoothly</p>
            <a href="#contact" class="button">Get Started</a>
        </div>
    </section>

    <!-- Services -->
    <section id="services" class="services">
        <div class="container">
            <h2>Our Services</h2>
            <div class="row">
                <div class="column">
                    <h3>🛠️ Core Maintenance</h3>
                    <ul>
                        <li>Weekly content updates</li>
                        <li>Security monitoring</li>
                        <li>Backup management</li>
                    </ul>
                </div>
                <div class="column">
                    <h3>⚡ Performance</h3>
                    <ul>
                        <li>Speed optimization</li>
                        <li>Mobile responsiveness</li>
                        <li>Uptime monitoring</li>
                    </ul>
                </div>
                <div class="column">
                    <h3>🔍 SEO & Analytics</h3>
                    <ul>
                        <li>Monthly SEO reports</li>
                        <li>Broken link checks</li>
                        <li>Google Analytics setup</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing -->
    <section id="pricing" class="container">
        <h2>Simple Pricing</h2>
        <div class="row">
            <div class="column price-card">
                <h3>Basic Care</h3>
                <h4>$50/mo</h4>
                <ul>
                    <li>Weekly updates</li>
                    <li>Security checks</li>
                    <li>Email support</li>
                </ul>
            </div>
            <div class="column price-card">
                <h3>Pro Care</h3>
                <h4>$100/mo</h4>
                <ul>
                    <li>Everything in Basic</li>
                    <li>Daily monitoring</li>
                    <li>Priority support</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Contact Form -->
    <section id="contact" class="container">
        <h2>Contact Us</h2>
        <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
            <div class="row">
                <div class="column">
                    <label for="name">Name</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="column">
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" required>
                </div>
            </div>
            <label for="message">Message</label>
            <textarea id="message" name="message" rows="5"></textarea>
            <input type="submit" class="button button-outline" value="Send Message">
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>© 2024 WebCare Pro. All rights reserved.</p>
        </div>
    </footer>

    <script>
        // Smooth scroll for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
