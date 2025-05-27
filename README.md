<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Shmai.com – Analysis Services</title>
  <link rel="stylesheet" href="styles.css" />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
 <style>
        /* Reset and Base Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Inter', sans-serif;
  line-height: 1.6;
  color: #333;
  background-color: #f9f9f9;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: 0 auto;
}



/* Header Styles */
.header {
  background-color: #ffffff;
  padding: 20px 0;
  border-bottom: 1px solid #eaeaea;
  position: sticky;
  top: 0;
  z-index: 100;
}

.header-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo a {
  font-size: 24px;
  font-weight: 700;
  color: #2c3e50;
  text-decoration: none;
}

.logo span {
  color: #3498db;
}

/* Navigation */
.nav ul {
  list-style: none;
  display: flex;
  gap: 30px;
}

.nav a {
  text-decoration: none;
  color: #2c3e50;
  font-weight: 500;
  transition: color 0.3s ease;
}

.nav a:hover {
  color: #3498db;
}

/* Hamburger Icon */
.hamburger {
  display: none;
  font-size: 26px;
  cursor: pointer;
}

/* Responsive Styles */
@media (max-width: 768px) {
  .nav {
    position: absolute;
    top: 70px;
    right: 0;
    background-color: #fff;
    width: 100%;
    display: none;
    flex-direction: column;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  }

  .nav ul {
    flex-direction: column;
    gap: 0;
  }

  .nav ul li {
    border-bottom: 1px solid #eee;
  }

  .nav ul li a {
    display: block;
    padding: 15px;
  }

  .hamburger {
    display: block;
  }

  .nav.active {
    display: flex;
  }
}

/* Hero Section */
.hero {
  background: linear-gradient(to right, #3498db, #2980b9);
  color: #fff;
  padding: 60px 0;
  text-align: center;
}

.hero h2 {
  font-size: 36px;
  margin-bottom: 20px;
}

.hero p {
  font-size: 18px;
  margin-bottom: 30px;
}

.btn {
  background-color: #fff;
  color: #3498db;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
  font-weight: 600;
}

.btn:hover {
  background-color: #ecf0f1;
}
/* Services Section Styles */
.services {
  padding: 60px 0;
  background-color: #f9f9f9;
  text-align: center;
}

.services h2 {
  font-size: 32px;
  margin-bottom: 40px;
  color: #2c3e50;
}

.service-cards {
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
  justify-content: center;
}

.service-card {
  background-color: #ffffff;
  padding: 30px;
  border-radius: 10px;
  width: 300px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.service-card .icon {
  font-size: 40px;
  margin-bottom: 20px;
  color: #3498db;
}

.service-card h3 {
  font-size: 20px;
  margin-bottom: 15px;
  color: #2c3e50;
}

.service-card p {
  font-size: 16px;
  color: #555555;
}

/* Testimonials Section */
.testimonials {
  padding: 60px 0;
  background-color: #ecf0f1;
  text-align: center;
}

.testimonials h3 {
  font-size: 28px;
  margin-bottom: 30px;
}

.testimonial {
  max-width: 600px;
  margin: 0 auto;
  font-style: italic;
  color: #2c3e50;
}

.testimonial span {
  display: block;
  margin-top: 15px;
  font-weight: 600;
  color: #34495e;
}

/* Footer */
.footer {
  background-color: #2c3e50;
  color: #fff;
  padding: 20px 0;
  text-align: center;
}
a {
text-decoration: none;
}


 </style>
</head>
<body>
  <!-- Header -->
  <!-- Responsive Header -->
<header class="header">
    <div class="container header-container">
      <div class="logo">
        <a href="#">Shmai<span>.com</span></a>
      </div>
      <nav class="nav" id="nav-menu">
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="#">Portfolio</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
      <div class="hamburger" id="hamburger">
        ☰
      </div>
    </div>
  </header>
  
  

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h2>Unlock Insights with Our Analysis Services</h2>
      <p>Transform your data into actionable strategies with Shmai.com's expert analysis solutions.</p>
      <a href="https://www.shmai.com/contact" class="btn">Get Started</a>
    </div>
  </section>

  <!-- Services Section -->
  <section class="services">
    <div class="container">
      <h2>Our Services</h2>
      <div class="service-cards">
        <div class="service-card">
          <div class="icon">🌐</div>
          <a href="https://www.shmai.com/chicago-web-design-web-development/">
            <h3>Web Design & Development</h3>
          </a>
          
          <p>Scalable, SEO-optimized, and visually stunning websites tailored to your business needs.</p>
        </div>
        <div class="service-card">
          <div class="icon">📱</div>
          <h3>Mobile App Development</h3>
          <p>User-friendly, high-performance apps for iOS and Android platforms to enhance customer engagement.</p>
        </div>
        <div class="service-card">
          <div class="icon">🎨</div>
          <h3>Graphic Design Solutions</h3>
          <p>Stand out with a cohesive brand identity that resonates with your audience.</p>
        </div>
        <div class="service-card">
          <div class="icon">☁️</div>
          <h3>DevOps Services</h3>
          <p>Streamline operations with secure, scalable cloud solutions and modern DevOps practices.</p>
        </div>
        <div class="service-card">
          <div class="icon">📈</div>
          <a href="https://www.shmai.com/website-seo-audit-services/">          <h3>Digital Marketing</h3>
          </a>
          <p>Maximize online visibility with result-driven strategies in SEO, PPC, and social media marketing.</p>
        </div>
        <div class="service-card">
          <div class="icon">🛠️</div>
          <h3>IT Support & Maintenance</h3>
          <p>Ensure seamless IT operations with proactive support and timely issue resolution.</p>
        </div>
      </div>
    </div>
  </section>
  

  <!-- Testimonials Section -->
  <section class="testimonials">
    <div class="container">
      <h3>What Our Clients Say</h3>
      <div class="testimonial">
        <p>"Shmai.com's analysis services provided us with invaluable insights that propelled our business forward."</p>
        <span>- Alex Johnson, CEO of TechCorp</span>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="container">
      <p>&copy; 2025 Shmai.com. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>
