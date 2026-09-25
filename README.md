<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sujata Baby Care - Loving & Reliable Care for Your Little Ones</title>
    <style>
        :root {
            --primary-color: #ff8fab;
            --secondary-color: #ffe5ec;
            --accent-color: #fb6f92;
            --text-color: #4a4a4a;
            --bg-color: #fff9fb;
            --white: #ffffff;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
        }

        /* Header & Navigation */
        header {
            background-color: var(--white);
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .navbar {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: var(--accent-color);
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        .nav-links a {
            text-decoration: none;
            color: var(--text-color);
            font-weight: 600;
            transition: color 0.3s;
        }

        .nav-links a:hover {
            color: var(--accent-color);
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, var(--secondary-color) 0%, var(--white) 100%);
            padding: 80px 20px;
            text-align: center;
        }

        .hero h1 {
            font-size: 42px;
            color: var(--accent-color);
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 18px;
            max-width: 600px;
            margin: 0 auto 30px auto;
        }

        .btn {
            background-color: var(--accent-color);
            color: var(--white);
            padding: 12px 30px;
            border: none;
            border-radius: 25px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            text-decoration: none;
            transition: background 0.3s;
            display: inline-block;
        }

        .btn:hover {
            background-color: #e55a7d;
        }

        /* Services Section */
        .services {
            max-width: 1200px;
            margin: 60px auto;
            padding: 0 20px;
            text-align: center;
        }

        .services h2 {
            font-size: 32px;
            margin-bottom: 40px;
            color: var(--accent-color);
        }

        .service-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .service-card {
            background: var(--white);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.03);
            transition: transform 0.3s;
        }

        .service-card:hover {
            transform: translateY(-5px);
        }

        .service-card h3 {
            margin-bottom: 15px;
            color: var(--accent-color);
        }

        /* Pricing Section */
        .pricing-notice {
            background-color: var(--secondary-color);
            text-align: center;
            padding: 50px 20px;
            margin: 60px 0;
        }

        .pricing-notice h2 {
            color: var(--accent-color);
            margin-bottom: 15px;
            font-size: 28px;
        }

        .pricing-notice p {
            max-width: 700px;
            margin: 0 auto 20px auto;
            font-size: 16px;
        }

        /* Inquiry Form Section */
        .inquiry-section {
            max-width: 600px;
            margin: 60px auto;
            background: var(--white);
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
        }

        .inquiry-section h2 {
            text-align: center;
            color: var(--accent-color);
            margin-bottom: 30px;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
        }

        .form-group input, .form-group select {
            width: 100%;
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-size: 16px;
        }

        .form-group input:focus, .form-group select:focus {
            outline: none;
            border-color: var(--accent-color);
        }

        .submit-btn {
            width: 100%;
            background-color: var(--accent-color);
            color: var(--white);
            padding: 14px;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: background 0.3s;
        }

        .submit-btn:hover {
            background-color: #e55a7d;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: var(--white);
            text-align: center;
            padding: 20px;
            margin-top: 60px;
        }
    </style>
</head>
<body>

    <!-- Header & Nav -->
    <header>
        <div class="navbar">
            <div class="logo">🍼 Sujata Baby Care</div>
            <ul class="nav-links">
                <li><a href="#services">Services</a></li>
                <li><a href="#pricing">Pricing</a></li>
                <li><a href="#inquiry">Inquire Now</a></li>
            </ul>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Welcome to Sujata Baby Care</h1>
        <p>Providing a safe, nurturing, and loving home away from home for your little ones. Dedicated care you can always trust.</p>
        <a href="#inquiry" class="btn">Get in Touch</a>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <h2>Our Care Services</h2>
        <div class="service-grid">
            <div class="service-card">
                <h3>Infant & Newborn Care</h3>
                <p>Gentle, attentive, and specialized care tailored specifically for newborns and infants.</p>
            </div>
            <div class="service-card">
                <h3>Daily Daycare</h3>
                <p>A fun, engaging, and secure daytime environment packed with learning and supervised play.</p>
            </div>
            <div class="service-card">
                <h3>Part-Time / Nanny Care</h3>
                <p>Flexible hourly or part-time care arrangements tailored to suit your working schedule.</p>
            </div>
        </div>
    </section>

    <!-- Pricing Notice Section -->
    <section id="pricing" class="pricing-notice">
        <h2>Flexible & Personalized Pricing</h2>
        <p>Every child's needs are unique, which is why our pricing is customized based on the schedule, age, and specific type of care required. Reach out to us with your details, and we will discuss the best plan for your family!</p>
        <a href="#inquiry" class="btn">Inquire About Care</a>
    </section>

    <!-- Inquiry Form Section -->
    <section id="inquiry" class="inquiry-section">
        <h2>Parent Inquiry Form</h2>
        <form id="inquiryForm" onsubmit="handleFormSubmit(event)">
            <div class="form-group">
                <label for="parentsName">Parents Name:</label>
                <input type="text" id="parentsName" name="parentsName" required placeholder="Enter your full name">
            </div>

            <div class="form-group">
                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" required placeholder="Enter your phone number">
            </div>

            <div class="form-group">
                <label for="type">Type of Care:</label>
                <select id="type" name="type" required>
                    <option value="" disabled selected>Select type of care</option>
                    <option value="Infant Care">Infant Care</option>
                    <option value="Full Day Daycare">Full Day Daycare</option>
                    <option value="Part-Time / Nanny">Part-Time / Nanny</option>
                    <option value="Emergency Care">Emergency Care</option>
                </select>
            </div>

            <button type="submit" class="submit-btn">Submit Inquiry</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Sujata Baby Care. All rights reserved.</p>
    </footer>

    <script>
        function handleFormSubmit(event) {
            event.preventDefault();
            
            // Get form values
            const parentsName = document.getElementById('parentsName').value;
            const phone = document.getElementById('phone').value;
            const type = document.getElementById('type').value;

            // Simple success alert (You can replace this with backend submission logic)
            alert(`Thank you, ${parentsName}! Your inquiry for ${type} has been received. We will call you at ${phone} soon.`);
            
            // Reset the form
            document.getElementById('inquiryForm').reset();
        }
    </script>
</body>
</html>
