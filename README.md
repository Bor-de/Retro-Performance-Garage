<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Retro Performance Garage</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="hero">
    <h1>Welcome to Retro Performance Garage</h1>
    <p>Rebuilding Cars and Tomos Motorcycles with Expertise</p>
    <a href="#contact" class="cta-button">Contact Us Now</a>
  </header>

  <main>
    <section class="features">
      <h2>Our Services</h2>
      <div class="feature">
        <h3>Expert Car Rebuilding</h3>
        <p>Restoring your vehicles to peak performance with precision and care.</p>
      </div>
      <div class="feature">
        <h3>Tomos Motorcycle Specialists</h3>
        <p>Specializing in the restoration and customization of Tomos bikes.</p>
      </div>
    </section>

    <section id="contact" class="contact">
      <h2>Contact Us</h2>
      <p>Email: <a href="mailto:bor.cvetko13@gmail.com">bor.cvetko13@gmail.com</a></p>
      <!-- Add phone/address details here -->
    </section>
  </main>

  <footer>
    <p>© 2024 Retro Performance Garage. All rights reserved.</p>
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
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: #333;
  color: #fff;
}

/* Hero Section */
.hero {
  text-align: center;
  padding: 2rem;
  background-color: #d35400; /* Dark Orange */
  color: white;
}
.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}
.hero p {
  font-size: 1.2rem;
  margin-bottom: 1.5rem;
}
.cta-button {
  display: inline-block;
  background: orange;
  color: #fff;
  padding: 0.8rem 1.5rem;
  text-decoration: none;
  border-radius: 5px;
  font-weight: bold;
}
.cta-button:hover {
  background: #e67e22;
}

/* Features Section */
.features {
  padding: 2rem;
  text-align: center;
}
.features h2 {
  font-size: 2rem;
  margin-bottom: 1.5rem;
}
.feature {
  margin-bottom: 1rem;
}
.feature h3 {
  font-size: 1.5rem;
  margin-bottom: 0.5rem;
}

/* Contact Section */
.contact {
  padding: 2rem;
  text-align: center;
  background-color: #444;
}
.contact a {
  color: orange;
  text-decoration: none;
}
.contact a:hover {
  text-decoration: underline;
}

/* Footer */
footer {
  text-align: center;
  padding: 1rem;
  background-color: #222;
  color: #bbb;
}
