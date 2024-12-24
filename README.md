<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="SARACEEN KENYA SECURITY SERVICES COMPANY - Providing trusted security solutions in Kenya">
    <title>SARACEEN KENYA SECURITY SERVICES</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <h1>SARACEEN KENYA SECURITY SERVICES</h1>
            <p>Your Trusted Security Partner</p>
            <button><a href="#contact">Contact Us</a></button>
        </div>
    </header>

    <!-- About Us Section -->
    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>SARACEEN KENYA SECURITY SERVICES offers expert security solutions tailored for businesses and individuals in Kenya. With a team of well-trained security personnel and cutting-edge technology, we ensure peace of mind for our clients.</p>
        </div>
    </section>

    <!-- Vision and Mission Section -->
    <section id="vision-mission">
        <div class="container">
            <h2>Our Vision & Mission</h2>
            <div class="mission-vision">
                <div class="vision">
                    <h3>Vision</h3>
                    <p>To be the leading provider of trusted security services in Kenya, ensuring safety and peace of mind for every individual and organization we serve.</p>
                </div>
                <div class="mission">
                    <h3>Mission</h3>
                    <p>To deliver comprehensive security solutions with integrity, professionalism, and the latest technology, committed to exceeding client expectations.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services">
        <div class="container">
            <h2>Our Services</h2>
            <p>We offer a variety of professional security services:</p>
            <ul>
                <li>Security Guard Services</li>
                <li>Alarm Monitoring</li>
                <li>Mobile Patrols</li>
                <li>Event Security</li>
                <li>Risk Assessment</li>
            </ul>
            <button><a href="#contact">Get a Quote</a></button>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Get in touch with us for more information or to request our services.</p>
            <p><strong>Phone:</strong> +254700439828 | +254711889619</p>
            <p><strong>Email:</strong> contact@saraceenkenya.com</p>
            <form action="#">
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Submit</button>
            </form>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="container">
            <p>&copy; 2024 SARACEEN KENYA SECURITY SERVICES. All Rights Reserved.</p>
            <div class="social-links">
                <a href="#">Facebook</a> | <a href="#">Twitter</a> | <a href="#">LinkedIn</a>
            </div>
        </div>
    </footer>
</body>

</html>
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

/* Container for content */
.container {
    width: 80%;
    margin: 0 auto;
    padding: 20px;
}

/* Header Section */
header {
    background-color: skyblue;
    color: white;
    text-align: center;
    padding: 60px 0;
}

header h1 {
    font-size: 3rem;
    margin-bottom: 10px;
}

header p {
    font-size: 1.2rem;
    margin-bottom: 20px;
}

header button a {
    text-decoration: none;
    background-color: #003366;
    color: white;
    padding: 10px 20px;
    border-radius: 5px;
}

/* About Us Section */
#about {
    background-color: white;
    padding: 40px 0;
    text-align: center;
}

#about p {
    font-size: 1.1rem;
}

/* Vision and Mission Section */
#vision-mission {
    background-color: #e9e9e9;
    padding: 40px 0;
}

#vision-mission .mission-vision {
    display: flex;
    justify-content: space-around;
    gap: 20px;
}

#vision-mission h3 {
    font-size: 1.5rem;
}

/* Services Section */
#services {
    background-color: white;
    padding: 40px 0;
    text-align: center;
}

#services ul {
    list-style: none;
    padding: 0;
}

#services li {
    font-size: 1.2rem;
    margin: 10px 0;
}

#services button a {
    text-decoration: none;
    background-color: #003366;
    color: white;
    padding: 10px 20px;
    border-radius: 5px;
}

/* Contact Section */
#contact {
    background-color: #f9f9f9;
    padding: 40px 0;
}

#contact form {
    display: flex;
    flex-direction: column;
    gap: 10px;
    max-width: 400px;
    margin: 0 auto;
}

#contact label {
    font-size: 1.1rem;
}

#contact input,
#contact textarea {
    padding: 10px;
    font-size: 1rem;
    border: 1px solid #ddd;
    border-radius: 5px;
}

#contact button {
    background-color: #003366;
    color: white;
    padding: 10px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

/* Footer Section */
footer {
    background-color: #003366;
    color: white;
    text-align: center;
    padding: 20px 0;
}

footer .social-links a {
    color: white;
    text-decoration: none;
    margin: 0 10px;
}
