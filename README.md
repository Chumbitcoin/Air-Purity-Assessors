# Air-Purity-Assessors
Mold Testing, Air quality service experts

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Air Purity Assessors - Mold Testing & Air Quality</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header -->
    <header>
        <div class="container">
            <h1>Air Purity Assessors</h1>
            <p>Expert Mold Testing & Air Quality Services</p>
            <a href="#book" class="btn">Book a Test Now</a>
        </div>
    </header>

    <!-- Home Section -->
    <section id="home">
        <div class="container">
            <h2>Protecting Your Home and Health</h2>
            <p>We specialize in mold testing and air quality assessments, providing peace of mind for new parents, first-time homeowners, and individuals with respiratory concerns.</p>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services">
        <div class="container">
            <h2>Our Services</h2>
            <ul>
                <li><strong>Mold Testing:</strong> Identify mold growth in your home before it becomes a serious issue.</li>
                <li><strong>Air Quality Assessments:</strong> Ensure the air you breathe is clean and safe.</li>
                <li><strong>Professional Reports:</strong> Receive certified reports for realtors, home inspectors, and HVAC professionals.</li>
            </ul>
        </div>
    </section>

    <!-- For Professionals Section -->
    <section id="for-professionals">
        <div class="container">
            <h2>For HVAC, Realtors, and Plumbers</h2>
            <p>We partner with professionals to help your clients keep their homes safe and mold-free. Contact us to learn more about our referral program and how we can assist you.</p>
        </div>
    </section>

    <!-- Booking Section -->
    <section id="book">
        <div class="container">
            <h2>Schedule a Test</h2>
            <form action="https://www.example.com/book" method="post">
                <label for="name">Your Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Your Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="date">Preferred Date:</label>
                <input type="date" id="date" name="date" required>

                <label for="service">Choose Service:</label>
                <select id="service" name="service">
                    <option value="mold-testing">Mold Testing</option>
                    <option value="air-quality">Air Quality Assessment</option>
                </select>

                <button type="submit" class="btn">Book Now</button>
            </form>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <p>If you have any questions, feel free to reach out to us!</p>
            <p>Email: <a href="mailto:info@airpurityassessors.com">info@airpurityassessors.com</a></p>
            <p>Phone: <a href="tel:+1234567890">+1 (234) 567-890</a></p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Air Purity Assessors. All Rights Reserved.</p>
        </div>
    </footer>

</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

header {
    background: #00796B;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin-bottom: 10px;
}

.btn {
    background: #FF5722;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

section {
    padding: 20px 0;
}

section h2 {
    margin-bottom: 20px;
    color: #00796B;
}

section p {
    margin-bottom: 10px;
}

ul {
    list-style: none;
    padding-left: 0;
}

ul li {
    margin-bottom: 10px;
}

form {
    display: flex;
    flex-direction: column;
}

form label {
    margin-bottom: 5px;
    color: #333;
}

form input, form select {
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    background: #00796B;
    color: #fff;
    padding: 10px;
    border: none;
    cursor: pointer;
}

form button:hover {
    background: #004D40;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}

footer p {
    margin: 0;
}
<script src="https://assets.calendly.com/assets/external/widget.js" async></script>
<a href="" onclick="Calendly.showPopupWidget('https://calendly.com/airpurityassessors/consultation');return false;" class="btn">Book a Test Now</a>

