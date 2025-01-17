# MathiasParadza.github.io
# Godspeed-Technologies
# HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Godspeed Technologies - Digital transformation for businesses">
  <meta name="keywords" content="Software Development, Web Development, Mobile App Development, Cybersecurity, IT Consulting, Data Analytics">
  <meta name="author" content="Godspeed Technologies">
  <title>Godspeed Technologies</title>
  <!--card stack new cdn-->
   <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css" />
   <script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>

  <!--overview swiper-->
  <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css">

  <!--round menu link-->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" rel="stylesheet">

  <!-- Link to Bootstrap CSS -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css">
  <!-- Link to custom stylesheet -->
  <link rel="stylesheet" href="assets/css/styles.css">
  <!--services slider-->
 <style>
    /* General Reset */
body, h1, h2, h3, h4, h5, h6, p {
  margin: 0;
  padding: 0;
  font-family: 'Arial', sans-serif;
  color: #333; /* Dark Grey for Text */
  line-height: 1.6;
}
body{
   background-color: #e2e7ec; /* Light Grey Background */
}
.container{
 max-width: 1200px;
  margin: 0 auto;
  padding: 15px;
}
/*logo*/
.navbar-brand{
 height: 40px;
  width: auto;
}
.navbar-brand {
  font-size: 20px;
  font-weight: bold;
  color: #333;
  text-decoration: none;
}
/* Nav Link Styling */
.nav-link {
  color: #333;
  position: relative;
  display: inline-block;
  padding-bottom: 5px;
  transition: color 0.3s ease;
}
.nav-link::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  height: 2px;
  width: 0;
  background-color: #e64a19;
  transition: width 0.3s ease;
}
.nav-link:hover {
  color: #020827; /* Keep the text color consistent */
}
.nav-link:hover::after {
  width: 100%;
}
/* Primary Button Styling */
.btn-primary {
  background-color: #007bff;
  border-color: #007bff;
  transition: background-color 0.3s ease;
}
.btn-primary:hover {
  background-color: #0056b3;
  border-color: #004085;
}
/* Primary Button Styling */
.btn-primary {
  background-color: #007bff;
  border-color: #007bff;
  transition: background-color 0.3s ease;
}
.btn-primary:hover {
  background-color: #0056b3;
  border-color: #004085;
}
/* Primary Button */
.btn-primary {
  background-color: #007bff;
  border-color: #007bff;
  transition: background-color 0.3s ease;
}
.btn-primary:hover {
  background-color: #0056b3;
  border-color: #004085;
}
/* Header Styles */
header {
  background: rgba(255, 255, 255, 0.9); /* Semi-transparent White */
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  position: fixed;
  width: 100%;
  z-index: 1000;
}
header .navbar-brand {
  font-size: 1.5rem;
  color: #007bff; /* Bright Blue */
  font-weight: bold;
  text-transform: uppercase;
}
header .navbar-nav .nav-link {
  color: #333333;
  margin-left: 10px;
}
header .btn-primary {
  background-color: #ff5722; /* Orange Button */
  border: none;
  font-weight: bold;
  padding: 10px 15px;
}
header .btn-primary:hover {
  background-color: #e64a19; /* Darker Orange */
}
/* Page Title Section */
.page-title {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white;
}
.page-title h1 {
  font-size: 3rem;
  font-weight: bold;
  text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5);
}
.page-title p {
  font-size: 1.25rem;
  margin-top: 15px;
  font-weight: 300;
}
/* Section Styling */
section {
  margin: 60px 0;
  padding: 40px 0;
}
section h2 {
  text-align: center;
  font-size: 2.5rem;
  color: #007bff;
  margin-bottom: 20px;
  text-transform: uppercase;
  position: relative;
}
section h2::after {
  content: '';
  width: 80px;
  height: 4px;
  background: #ff5722;
  display: block;
  margin: 10px auto;
  border-radius: 2px;
}
/* Cards for Services & Branches */
.card {
  border: none;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
  overflow: hidden;
  transition: transform 0.3s ease;
  background-color: #fff;
}
.card:hover {
  transform: translateY(-5px);
}
.card-body {
  padding: 20px;
  text-align: center;
}
.card-title {
  font-size: 1.25rem;
  font-weight: bold;
  color: #333;
}
.card-text {
  font-size: 1rem;
  color: #666;
}
.card i {
  font-size: 2rem;
  color: #007bff;
  margin-bottom: 10px;
}
/* Buttons */
.btn-primary {
  background-color: #007bff;
  border: none;
  font-weight: bold;
  color: white;
  padding: 10px 20px;
  border-radius: 5px;
}
.btn-primary:hover {
  background-color: #0056b3;
}
/* Footer */
footer {
  background: hsl(200, 9%, 74%);
  color: hsl(255, 36%, 96%);
  text-align: center;
  padding: 20px 0;
}
footer p {
  margin: 0;
  font-size: 1rem;
}
.swiper-slide {
  display: flex;
  justify-content: center;
  align-items: center;
}
.card {
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  overflow: hidden;
}
.card-body {
  padding: 20px;
}
.card-title {
  font-size: 18px;
  margin-bottom: 10px;
}
.card-text {
  font-size: 14px;
}
/* Responsive Design */
@media (max-width: 768px) {
  .page-title h1 {
    font-size: 2.5rem;
  }
.card {
    margin-bottom: 20px;
  }
.navbar-nav .nav-link {
    margin-left: 0;
    margin-top: 10px;
  }
}
.social-menu ul {
  list-style: none;
  margin: 0;
  padding: 0;
}
.social-menu ul li {
  display: inline-block;
  margin: 0 10px;
}
.social-menu ul li a {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 50px;
  height: 50px;
  border-radius: 50%;
  background-color: #007bff; /* Change color as needed */
  color: white;
  font-size: 20px;
  text-decoration: none;
  transition: all 0.3s ease-in-out;
}
.social-menu ul li a:hover {
  background-color: #0056b3; /* Darker shade on hover */
  transform: scale(1.1);
}
.contact-form {
  max-width: 600px;
  background-color: #f8f9fa;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
}
.contact-form .form-label {
  font-weight: 500;
  color: #333;
}
.contact-form .form-control {
  border-radius: 5px;
  border: 1px solid #ccc;
}
.contact-form .form-control:focus {
  border-color: #007bff;
  box-shadow: 0px 0px 4px rgba(0, 123, 255, 0.5);
}
.contact-form button {
  border-radius: 20px;
  padding: 10px 20px;
  background-color: #007bff;
  color: #fff;
  border: none;
  transition: all 0.3s ease-in-out;
}
.contact-form button:hover {
  background-color: #0056b3;
  transform: scale(1.05);
}
.card-stack-slider {
  position: relative;
}
.card {
  border-radius: 15px;
  overflow: hidden;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
}
.card-img-top {
  height: 200px;
  object-fit: cover;
}
.card-body {
  text-align: center;
  padding: 20px;
}
.swiper-slide {
  display: flex;
  justify-content: center;
  align-items: center;
}
.about-us {
  background-color: #f9f9f9;
  padding: 60px 0;
}
.about-us h2 {
  font-size: 32px;
  margin-bottom: 20px;
}
.about-us p {
  font-size: 16px;
  line-height: 1.6;
  color: #555;
}
.about-us img {
  border: 5px solid #fff;
  object-fit: cover;
}
.blog {
  background-color: #f9f9f9;
}
.blog h2 {
  font-size: 32px;
  color: #333;
  margin-bottom: 20px;
}
.blog p.text-muted {
  font-size: 16px;
  color: #777;
}
.card {
  border: none;
  transition: transform 0.3s, box-shadow 0.3s;
}
.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}
.card-img-top {
  height: 200px;
  object-fit: cover;
  border-bottom: 1px solid #ddd;
}
.card-title {
  font-size: 20px;
  color: #222;
}
.card-text {
  font-size: 14px;
  color: #666;
}
.btn-primary {
  background-color: #007bff;
  border: none;
}
.btn-primary:hover {
  background-color: #0056b3;
}
/* clients section*/
.clients {
  background-color: #f9f9f9;
}
.clients h2 {
  font-size: 32px;
  color: #333;
}
.clients p.text-muted {
  font-size: 16px;
  color: #777;
}
.client-logo {
  max-height: 100px;
  transition: transform 0.3s;
}
.client-logo:hover {
  transform: scale(1.1);
}
.small {
  font-size: 14px;
  color: #555;
}
/* Popup Container */
.popup {
  position: relative;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0);
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 1000;
  opacity: 0;
  visibility: hidden;
  transition: all 0.3s ease-in-out;
}
/* Popup Content */
.popup-content {
  background: #6f7575c5;
  padding: 30px;
  width: 90%;
  max-width: 500px;
  border-radius: 10px;
  text-align: center;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
}
/* Close Button */
.close-btn {
  position: relative;
  top: 10px;
  right: 10px;
  background: transparent;
  border: none;
  font-size: 1.5rem;
  cursor: pointer;
  color: #e64a19;
  font-weight: bold;
}
/* Show Popup */
.popup.show {
  opacity: 1;
  visibility: visible;
}
/* Blurred Background Styling */
#home {
  position: relative;
  background: url('home.jpg') no-repeat center center;
  background-size: cover;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  overflow: hidden;
}
#home::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.5); /* Adds a dark overlay */
  backdrop-filter: blur(1px); /* Blurs the background */
  z-index: 1; /* Ensures it stays below the text */
}
/* Text Styling */
#home .container {
  position: relative;
  z-index: 2; /* Ensures text is above the blurred background */
  color: #fff;
}
#home h1 {
  font-size: 4rem;
  font-weight: bold;
}
#home h3 {
  font-size: 1.8rem;
  margin-top: 20px;
}
/* Highlight Styling */
.highlight {
  color: #ff5722;
  font-weight: bold;
}
/* Responsive Adjustments */
@media (max-width: 768px) {
  #home h1 {
    font-size: 2.5rem;
  }
  #home h3 {
    font-size: 1.5rem;
  }
}
#vision-mission {
  background-color: #f8f9fa;
}
#vision-mission h2 {
  font-weight: bold;
}
#vision-mission .p-4 {
  transition: transform 0.3s, box-shadow 0.3s;
}
#vision-mission .p-4:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
}
#vision-mission .text-primary {
  color: #ff9800;
}
#vision-mission .text-muted {
  font-size: 1.1rem;
}
@media (max-width: 768px) {
  #vision-mission .p-4 {
    margin-bottom: 20px;
  }
}
#discover {
  background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
  position: relative;
  overflow: hidden;
  padding: 100px 20px;
}
#discover h2 {
  font-weight: bold;
  text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.5);
}
#discover .lead {
  color: #d1d1d1;
}
#discover .btn-primary {
  background-color: #ff5722;
  border-color: #ff9800;
  transition: background-color 0.3s ease, transform 0.3s ease;
}
#discover .btn-primary:hover {
  background-color: #e68900;
  transform: scale(1.1);
}
.tech-doodles {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 1;
  pointer-events: none;
}
.tech-doodles .doodle {
  position: absolute;
  opacity: 0.5;
  animation: float 6s ease-in-out infinite;
}
.tech-doodles .doodle-1 {
  top: 10%;
  left: 20%;
  width: 80px;
  animation-delay: 0s;
}
.tech-doodles .doodle-2 {
  top: 30%;
  right: 15%;
  width: 100px;
  animation-delay: 1s;
}
.tech-doodles .doodle-3 {
  bottom: 20%;
  left: 10%;
  width: 120px;
  animation-delay: 2s;
}
.tech-doodles .doodle-4 {
  bottom: 15%;
  right: 20%;
  width: 90px;
  animation-delay: 3s;
}
@keyframes float {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-20px);
  }
}
.email-section {
  background-color: #f5f5f5;
  color: #333;
  border-top: 3px solid #ff6600;
}
.section-title {
  font-size: 2.5rem;
  font-weight: bold;
  color: #0051ff;
}
.section-subtitle {
  font-size: 1.2rem;
  color: #555;
  margin-bottom: 1.5rem;
}
.email-form {
  max-width: 600px;
  width: 100%;
}
.email-form .form-control {
  border: 2px solid #ccc;
  border-radius: 25px;
  padding: 10px 15px;
  width: 70%;
}
.email-form .form-control:focus {
  border-color: #ff6600;
  outline: none;
  box-shadow: 0 0 5px rgba(255, 102, 0, 0.5);
}
.email-form .btn-primary {
  background-color: #007bff;
  border: none;
  border-radius: 25px;
  padding: 10px 20px;
  font-weight: bold;
  text-transform: uppercase;
}
.email-form .btn-primary:hover {
  background-color: #0023e6;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}
</style>
</head>
<body>

  <!-- Header Section -->
  <header class="navbar navbar-expand-lg navbar-transparent fixed-top">
    <div class="container">
      <a class="navbar-brand d-flex align-items-center" href="#">
        <img src="assets/images/logo.png" alt="" class="me-2" style="height: 40px;">
        <span>Godspeed Technologies</span>
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
          <li class="nav-item"><a class="nav-link" href="#clients">Clients</a></li>
          <li class="nav-item"><a class="nav-link" href="#blog">Blog</a></li>
          <li class="nav-item"><a class="nav-link" href="#branches">Branches</a></li>
          <li class="nav-item"><a class="nav-link" href="#products">Products</a></li>
          <li class="nav-item"><a class="nav-link btn btn-primary text-white" href="#contact">Get a Quote</a></li>
        </ul>
      </div>
    </div>
    
    
  </header>
  <!-- Home Section -->
  <section id="home" class="page-title text-center text-white" style="background-image: url('assets/images/home2.jpg'); height: 100vh; background-position: center; background-size: cover;">
    <div class="container d-flex flex-column justify-content-center align-items-center h-100 text-center">
      <h1 class="display-1 text-white animate__animated animate__fadeIn">
        <span class="highlight">GODSPEED TECHNOLOGIES</span>
      </h1>
      <h3 class="display-5 text-light mt-3 animate__animated animate__fadeIn animate__delay-1s">
        Innovating your digital future with <span class="highlight">cutting-edge</span> technology solutions
      </h3>
    </div>
    
    
     <!-- Popup Ad -->
<div id="popupAd" class="popup">
  <div class="popup-content text-center">
    <button class="close-btn" onclick="closePopup()">×</button>
    <h2>how can we help?</h2>
    <p class="lead mb-3">Need to add your business to the cloud?</p>
    <a href="#overview" class="btn btn-primary btn-sm mb-3">Learn More</a>
    <p class="lead mb-3">Looking for custom software development?</p>
    <a href="#services" class="btn btn-primary btn-sm mb-3">Get Started</a>
    <p class="lead mb-3">Enhance security with robust cybersecurity solutions.</p>
    <a href="#services" class="btn btn-primary btn-sm mb-3">Explore</a>
  </div>
</div>

  </section>
  <!--discover with doodles-->
  <section id="discover" class="py-5 text-white text-center">
    <div class="container position-relative">
      <h2 class="display-4 mb-4 animate__animated animate__fadeInDown">Discover The Power of Technology</h2>
      <p class="lead mb-5 animate__animated animate__fadeInUp">
        Unleashing the power of technology to transform your business into a digital powerhouse.
      </p>
      <p class="lead mb-5 animate__animated animate__fadeInUp">
        Technology is the backbone of modern innovation, shaping the way we live, work, and connect. At Godspeed Technologies, we embrace the limitless potential of tech to drive transformation and unlock opportunities for growth. From cutting-edge software development to robust cybersecurity solutions, we harness the power of innovation to empower businesses and individuals alike. With a focus on scalability, efficiency, and creativity, our goal is to lead the digital revolution and build a smarter, more connected world for generations to come.
      </p>
  
      <!-- Tech Doodles -->
      <div class="tech-doodles">
        <img src="assets/images/tech (1).jpg" alt="Doodle 1" class="doodle doodle-1">
        <img src="assets/images/tech (2).jpg" alt="Doodle 2" class="doodle doodle-2">
        <img src="assets/images/tech (3).jpg" alt="Doodle 3" class="doodle doodle-3">
        <img src="assets/images/tech (4).jpg" alt="Doodle 4" class="doodle doodle-4">
      </div>
  
      <!-- Call to Action Button -->
      <a href="#services" class="btn btn-primary btn-lg mt-4 animate__animated animate__pulse">
        Get started
      </a>
    </div>
  </section>
  
 
  <!--services sections-->
  <section class="services py-5" id="services">
    <div class="container">
      <h2 class="text-center mb-4">Services Offered</h2>
      <!-- Swiper Slider -->
      <div class="swiper services-swiper">
        <div class="swiper-wrapper">
          <!-- Service Slide 1 -->
          <div class="swiper-slide">
            <div class="card">
              <div class="card-body text-center">
                <img src="assets/images/software.jpg" class="card-img-top" alt="Cloud Solutions">
                <i class="lucide-software"></i>
                <h5 class="card-title">Software Development</h5>
                <p class="card-text">Custom software solutions tailored to client needs.</p>
              </div>
            </div>
          </div>
          <!-- Service Slide 2 -->
          <div class="swiper-slide">
            <div class="card">
              <div class="card-body text-center">
                <img src="assets/images/webdev.jpg" class="card-img-top" alt="Cloud Solutions">
                <i class="lucide-web"></i>
                <h5 class="card-title">Web Development</h5>
                <p class="card-text">Responsive and dynamic web applications.</p>
              </div>
            </div>
          </div>
          <!-- Service Slide 3 -->
          <div class="swiper-slide">
            <div class="card">
              <div class="card-body text-center">
                <img src="assets/images/mobile.jpg" class="card-img-top" alt="Cloud Solutions">
                <i class="lucide-web"></i>
                <h5 class="card-title">Mobile App Development</h5>
                <p class="card-text">iOS and Android app creation.</p>
              </div>
            </div>
          </div>
          <!-- Service Slide 4 -->
          <div class="swiper-slide">
            <div class="card">
              <div class="card-body text-center">
                <img src="assets/images/cyberp.jpg" class="card-img-top" alt="Cloud Solutions">
                <i class="lucide-web"></i>
                <h5 class="card-title">Cybersecurity</h5>
                <p class="card-text">Robust security measures and threat prevention.</p>
              </div>
            </div>
          </div>
          <!-- Add more slides for other services -->
        </div>
        <!-- Swiper Pagination -->
        <div class="swiper-pagination"></div>
        <!-- Swiper Navigation Buttons -->
        <div class="swiper-button-prev"></div>
        <div class="swiper-button-next"></div>
      </div>
    </div>
  </section>
  <!--blog section-->
  <section class="blog py-5" id="blog">
    <div class="container">
      <h2 class="text-center mb-4">Latest from Our Blog</h2>
      <p class="text-center text-muted mb-5">Stay updated with the latest trends and insights in technology and innovation.</p>
      <div class="row">
        <!-- Blog Post 1 -->
        <div class="col-md-4 mb-4">
          <div class="card shadow-sm">
            <img src="assets/images/emerging.jpg" class="card-img-top" alt="Blog Title 1">
            <div class="card-body">
              <h5 class="card-title">Emerging Trends in AI</h5>
              <p class="card-text text-muted">Discover how artificial intelligence is shaping industries and transforming the future of business.</p>
              <a href="#" class="btn btn-primary btn-sm">Read More</a>
            </div>
          </div>
        </div>
        <!-- Blog Post 2 -->
        <div class="col-md-4 mb-4">
          <div class="card shadow-sm">
            <img src="assets/images/cybersec.jpg" class="card-img-top" alt="Blog Title 2">
            <div class="card-body">
              <h5 class="card-title">Cybersecurity in 2025</h5>
              <p class="card-text text-muted">Learn about the latest threats and strategies to safeguard your digital assets.</p>
              <a href="#" class="btn btn-primary btn-sm">Read More</a>
            </div>
          </div>
        </div>
        <!-- Blog Post 3 -->
        <div class="col-md-4 mb-4">
          <div class="card shadow-sm">
            <img src="assets/images/cloudcom.jpg" class="card-img-top" alt="Blog Title 3">
            <div class="card-body">
              <h5 class="card-title">The Power of Cloud Computing</h5>
              <p class="card-text text-muted">Explore how businesses are leveraging the cloud for scalability and innovation.</p>
              <a href="#" class="btn btn-primary btn-sm">Read More</a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!--news later-->
<section id="email-section" class="email-section py-5 text-center">
  <div class="container">
    <h2 class="section-title mb-4">Stay Updated with Godspeed Technologies</h2>
    <p class="section-subtitle mb-4">
      Subscribe to our newsletter and receive the latest updates, news, and exclusive offers directly to your inbox.
    </p>
    <form class="email-form d-flex justify-content-center align-items-center">
      <input
        type="email"
        class="form-control me-2"
        placeholder="Enter your email address"
        required
      />
      <button type="submit" class="btn btn-primary">Subscribe</button>
    </form>
  </div>
</section>
  </section>
  
 
<!--products secton-->
  <section class="products py-5" id="products">
    <div class="container">
      <h2 class="text-center mb-4">Our Products</h2>
      <p class="text-center text-muted mb-5">Explore our innovative and cutting-edge solutions designed to drive your business forward.</p>
      <div class="row">
        <!-- Product 1 -->
        <div class="col-md-4 mb-4">
          <div class="card product-card">
            <img src="assets/images/product1.jpg" alt="Product 1" class="card-img-top product-image">
            <div class="card-body">
              <h5 class="card-title">Xyreod GFx </h5>
              <p class="card-text">A 360 Multi-Media Googles, equiped with wires Video and Audio .</p>
              <a href="#product1-details" class="btn btn-primary">Learn More</a>
            </div>
          </div>
        </div>
        <!-- Product 2 -->
        <div class="col-md-4 mb-4">
          <div class="card product-card">
            <img src="assets/images/product2.jpg" alt="Product 2" class="card-img-top product-image">
            <div class="card-body">
              <h5 class="card-title">Wyomiong Gxv Hand Watch</h5>
              <p class="card-text">A Multi-Media watch Hand Watch Equiped Gaming,Screen Projection and Video Capabilities.</p>
              <a href="#product2-details" class="btn btn-primary">Learn More</a>
            </div>
          </div>
        </div>
        <!-- Product 3 -->
        <div class="col-md-4 mb-4">
          <div class="card product-card">
            <img src="assets/images/product3.jpg" alt="Product 3" class="card-img-top product-image">
            <div class="card-body">
              <h5 class="card-title">Hand Drone Controller</h5>
              <p class="card-text">A Hand Glove Equiped with Six Drones, Provides Resolution Photgraphy and Video Shoot, also used for Aerial Gaming.</p>
              <a href="#product3-details" class="btn btn-primary">Learn More</a>
            </div>
          </div>
        </div>
        <!-- Add more products as needed -->
      </div>
    </div>
  </section>
  
 <!-- Our Branches Section -->
 <section class="branches py-5" id="branches">
  <div class="container">
    <h2 class="text-center mb-4">Our Branches</h2>
    <div class="row">
      <!-- Branch Cards -->
      <div class="col-md-4">
        <div class="card">
          <div class="card-body">
            <img src="assets/images/lusaka.jpg" class="card-img-top" alt="Zambia">
            <i class="lucide-map-pin"></i>
            <h5 class="card-title">Zambia (Lusaka)</h5>
            <p class="card-text">123 Trades building Cairo Rd, Lusaka</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <div class="card-body">
            <img src="assets/images/birmingham.jpg" class="card-img-top" alt="united kingdom">
            <i class="lucide-map-pin"></i>
            <h5 class="card-title">United Kingdom (Birmingham)</h5>
            <p class="card-text">456 Central Square Rd,Birmingham </p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <div class="card-body">
            <img src="assets/images/dubai.jpg" class="card-img-top" alt="united arab Emirates">
            <i class="lucide-map-pin"></i>
            <h5 class="card-title">United Arab Emirates (Dubai)</h5>
            <p class="card-text">478 Equadr Se ot Rd,Dubai </p>
          </div>
        </div>
      </div>
      <!-- Add other branch cards for Livingstone, Kasama, Mongu -->
    </div>
  </div>
</section>

  <section id="about" class="py-5">
    <div class="container">
      <div class="row">
        <!-- Vision Section -->
        <div class="col-md-6 text-center">
          <div class="p-4 shadow-lg bg-white rounded">
            <h2 class="display-5 text-primary mb-3">Our Vision</h2>
            <p class="lead text-muted">
              To be a global leader in driving technological innovation, empowering businesses to achieve limitless possibilities through cutting-edge solutions.
            </p>
          </div>
        </div>
        <!-- Mission Section -->
        <div class="col-md-6 text-center">
          <div class="p-4 shadow-lg bg-white rounded">
            <h2 class="display-5 text-primary mb-3">Our Mission</h2>
            <p class="lead text-muted">
              To provide innovative, scalable, and secure technology solutions tailored to meet the evolving needs of our clients, fostering sustainable growth and success.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
  
 <!--about us section-->
 <section class="about-us py-5" id="about">
  <div class="container">
    <h2 class="text-center mb-4">About Us</h2>
    <div class="row align-items-center">
      <!-- Founder Photo -->
      <div class="col-md-4 text-center">
        <img src="assets/images/profile.jpg" alt="Mathias Paradza" class="img-fluid rounded-circle shadow" style="width: 200px; height: 200px;">
      </div>
      <!-- About Content -->
      <div class="col-md-8">
        <h3 class="mb-3">Our Story</h3>
        <p>
          Godspeed Technologies was founded with a vision to revolutionize the tech landscape by providing cutting-edge solutions tailored to modern business challenges. Since its inception, the company has been at the forefront of innovation, helping businesses harness the power of technology to grow and succeed.
        </p>
        <p>
          Our journey began with a dream to make advanced technology accessible and effective for businesses of all sizes. Today, we continue to push boundaries and deliver exceptional value to our clients worldwide.
        </p>
        <h3 class="mb-3">About Our Founder</h3>
        <p>
          <strong>Mathias Paradza</strong>, the visionary behind Godspeed Technologies, is a passionate entrepreneur with a deep love for technology and innovation. With years of experience in software development and IT consulting, Mathias founded the company to turn bold ideas into impactful solutions. His leadership and commitment to excellence have been the driving force behind Godspeed Technologies' success.
        </p>
      </div>
    </div>
  </div>
</section>

 
  <!--clients section-->
<section class="clients py-5" id="clients">
  <div class="container">
    <h2 class="text-center mb-4">Our Clients & Partners</h2>
    <p class="text-center text-muted mb-5">We are proud to collaborate with industry leaders and innovators across the globe.</p>
    <div class="row justify-content-center">
      <!-- Client/Partner Logo 1 -->
      <div class="col-md-2 col-6 mb-4 text-center">
        <img src="assets/images/mobiletech.jpg" alt="Client 1" class="client-logo img-fluid">
        <p class="mt-2 small">Mobile Tech</p>
      </div>
      <!-- Client/Partner Logo 2 -->
      <div class="col-md-2 col-6 mb-4 text-center">
        <img src="assets/images/motion.jpg" alt="Client 2" class="client-logo img-fluid">
        <p class="mt-2 small">Motion</p>
      </div>
      <!-- Client/Partner Logo 3 -->
      <div class="col-md-2 col-6 mb-4 text-center">
        <img src="assets/images/infinity.png" alt="Client 3" class="client-logo img-fluid">
        <p class="mt-2 small">Infinity</p>
      </div>
      <!-- Client/Partner Logo 4 -->
      <div class="col-md-2 col-6 mb-4 text-center">
        <img src="assets/images/techdeal.jpg" alt="Client 4" class="client-logo img-fluid">
        <p class="mt-2 small">Tech Deal</p>
      </div>
      <!-- Client/Partner Logo 5 -->
      <div class="col-md-2 col-6 mb-4 text-center">
        <img src="assets/images/creative.jpg" alt="Client 5" class="client-logo img-fluid">
        <p class="mt-2 small">Creative Solutions</p>
      </div>
      <!-- Add more logos as needed -->
    </div>
  </div>
</section>



  <!-- Contact Section -->
  <section class="contact py-5" id="contact">
    <div class="container">
        <h2 class="text-center mb-4">Contact Us</h2>
        <p class="text-center">Reach out to us for any inquiries or quotes</p>
        <form action="/submit-form" method="POST" class="contact-form mx-auto">
          <div class="mb-3">
            <label for="name" class="form-label">Full Name</label>
            <input type="text" id="name" name="name" class="form-control" placeholder="Enter your full name" required>
          </div>
          <div class="mb-3">
            <label for="email" class="form-label">Email Address</label>
            <input type="email" id="email" name="email" class="form-control" placeholder="Enter your email address" required>
          </div>
          <div class="mb-3">
            <label for="subject" class="form-label">Subject</label>
            <input type="text" id="subject" name="subject" class="form-control" placeholder="Enter the subject" required>
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">Message</label>
            <textarea id="message" name="message" class="form-control" rows="5" placeholder="Write your message here..." required></textarea>
          </div>
          <div class="text-center">
            <button type="submit" class="btn btn-primary">Send Message</button>
          </div>
        </form>
      </div>
      
    
  </section>
<!--thank you-->
  <section id="thank-you" class="thank-you-section text-center py-5">
    <div class="container">
      <h2 class="display-4 mb-4">Thank You for Visiting!</h2>
      <p class="lead mb-5">
        We’re here to assist you. Feel free to reach out to us at the following emails:
      </p>
      <div class="emails d-flex justify-content-center flex-wrap">
        <div class="email-card mx-3 my-2 p-3">
          <h5>General Inquiries</h5>
          <a href="mailto:info@godspeedtech.com" class="email-link">info@godspeedtech.com</a>
        </div>
        <div class="email-card mx-3 my-2 p-3">
          <h5>Support</h5>
          <a href="mailto:support@godspeedtech.com" class="email-link">support@godspeedtech.com</a>
        </div>
      </div>
    </div>
  </section>
  
  <!-- Footer -->
  <footer class="text-center py-4">
    <!-- Call to Action Button -->
    <div class="social-menu text-center mt-4">
      <h2 class="text-center mb-4">Follow Us On</h2>
      <ul class="d-inline-flex justify-content-center p-0 m-0">
        <li><a href="https://facebook.com" target="_blank"><i class="fab fa-facebook-f"></i></a></li>
        <li><a href="https://twitter.com" target="_blank"><i class="fab fa-twitter"></i></a></li>
        <li><a href="https://instagram.com" target="_blank"><i class="fab fa-instagram"></i></a></li>
        <li><a href="https://linkedin.com" target="_blank"><i class="fab fa-linkedin-in"></i></a></li>
      </ul>
    </div>

    <p>&copy; 2025 Godspeed Technologies.</p>
  </footer>

<!--swiper-->
<script>
   const swiper = new Swiper('.card-stack-swiper', {
  effect: 'cards',
  grabCursor: true,
  loop: true,
  autoplay: {
    delay: 3000,
    disableOnInteraction: false,
  },
  pagination: {
    el: '.swiper-pagination',
    clickable: true,
  },
});

const servicesSwiper = new Swiper('.services-swiper', {
    loop: true, // Enables looping through slides
    autoplay: {
      delay: 3000, // Auto-slide every 3 seconds
      disableOnInteraction: false,
    },
    pagination: {
      el: '.swiper-pagination',
      clickable: true,
    },
    navigation: {
      nextEl: '.swiper-button-next',
      prevEl: '.swiper-button-prev',
    },
    slidesPerView: 1, // Number of slides to show
    spaceBetween: 20, // Space between slides in px
    breakpoints: {
      768: {
        slidesPerView: 2,
        spaceBetween: 30,
      },
      1024: {
        slidesPerView: 3,
        spaceBetween: 40,
      },
    },
  });


   // Show the popup when the page loads
   window.onload = function () {
    setTimeout(() => {
      document.getElementById('popupAd').classList.add('show');
    }, 1000); // Delay for 1 second
  };

  // Close the popup
  function closePopup() {
    document.getElementById('popupAd').classList.remove('show');
  }
  </script>

<!-- Swiper JS -->
<script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>


  <!-- Bootstrap JS and Lucide Icons -->
  <script src="https://cdn.jsdelivr.net/npm/@lucide/icons/dist/index.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

