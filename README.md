# OCTANET_FEBRUARY
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Bike Rental</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <header>
    <h1>Your Bike Rental</h1>
  </header>

  <nav>
    <a href="#rental-options">Rental Options</a>
    <a href="#how-it-works">How It Works</a>
    <a href="#trust">Trust</a>
    <a href="#about-us">About Us</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="rental-options">
    <h2>Rental Options</h2>

    <div class="bike">
      <img src="bike1.jpg" alt="Mountain Bike">
      <div>
        <h3>Mountain Bike</h3>
        <p>Description of the mountain bike. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <p>Starting from $10/hour</p>
        <a class="cta-button" href="#">Rent Now</a>
      </div>
    </div>

    <!-- Repeat similar blocks for other bike options -->

  </section>

  <section id="how-it-works">
    <h2>How It Works</h2>

    <div class="how-it-works">
      <div>
        <h3>Choose Your Bike</h3>
        <p>Explore our selection of high-quality bikes.</p>
      </div>
      <div>
        <h3>Book Online</h3>
        <p>Use our easy online booking system to reserve your bike.</p>
      </div>
      <div>
        <h3>Pick Up and Enjoy</h3>
        <p>Visit our location, pick up your bike, and enjoy your ride!</p>
      </div>
    </div>
  </section>

  <section id="trust">
    <h2>Trust</h2>

    <div class="testimonial">
      <p>"Great service! I rented a bike for a weekend trip, and it was a fantastic experience."</p>
      <p>- John Doe, Happy Customer</p>
    </div>

    <!-- Add more testimonials or trust elements -->

  </section>

  <section id="about-us">
    <h2>About Us</h2>
    <p>Your Bike Rental is committed to providing high-quality bikes and exceptional service. Lorem ipsum dolor sit amet, consectetur adipiscing elit....</p>

    <!-- Add team profiles or additional information -->

  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Have questions or need assistance? Contact us!</p>

    <!-- Add contact form or contact information -->

  </section>

  <footer>
    <p>&copy; 2024 Your Bike Rental. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html

body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  background-image: url(https://www.technocrazed.com/wp-content/uploads/2015/12/bike-wallpaper-30.jpg); /* Replace with your actual image file path */
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
}

/* Other styles... */


header {
  background-color:#3b3c36; 
  color: #fff;
  padding: 8px;
  text-align: center;
}


CSS Code

nav {
  background-color:#d3d3d3  ;
  padding: 20px;
  text-align: left;
  text-color:#ffffff;
}

section {
  padding: 20px;
}

.cta-button {
  display: inline-block;
  padding: 10px 20px;
  background-color: #3b3c36;
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
}

.bike {
  display: flex;
  justify-content: space-between;
  margin-bottom: 20px;
}

.bike img {
  max-width: 200px;
  margin-right: 20px;
}

.how-it-works {
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.testimonial {
  border: 1px solid #ddd;
  padding: 10px;
  margin: 10px 0;
}

footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 10px;
  position: bottom;
  width: 100%;
  bottom: 0;
}
