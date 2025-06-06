


<!doctype html>
<html lang="en">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>IRON BLOOM</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f8f9fa;
      color: #333;
    }

    .header {
      background-color: #000;
      color: #fff;
      padding: 20px 40px;
      text-align: center;
      font-size: 2.5em;
      font-weight: bold;
      letter-spacing: 2px;
    }

    nav {
      display: flex;
      justify-content: center;
      background-color: #343a40;
      padding: 10px 0;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav a {
      color: white;
      text-decoration: none;
      padding: 12px 20px;
      font-size: 18px;
      transition: background 0.3s;
    }

    nav a:hover {
      background-color: #495057;
      border-radius: 5px;
    }

    .hero-container {
      width: 100%;
      overflow: hidden;
    }

    .hero-container img {
      width: 100%;
      height: auto;
      object-fit: cover;
      aspect-ratio: 16 / 9;
    }

    .welcome-cta {
      text-align: center;
      padding: 50px 20px;
      background-color: beige;
    }

    .welcome-cta h2 {
      font-size: 2.5em;
      color: #333;
    }

    .cta-button {
      margin-top: 20px;
      background-color: #333;
      color: white;
      font-size: 1.2em;
      padding: 15px 30px;
      border: none;
      cursor: pointer;
      border-radius: 5px;
      transition: background 0.3s;
    }

    .cta-button:hover {
      background-color: #495057;
    }

    .about-us {
      background-color: #808080;
      color: black;
      text-align: center;
      padding: 50px 20px;
    }

    .about-us h2 {
      font-size: 2.5em;
      margin-bottom: 20px;
    }

    .programs {
      padding: 50px 20px;
      text-align: center;
      background-color: #f1f1f1;
    }

    .programs h2 {
      font-size: 2.5em;
      margin-bottom: 30px;
    }

    .flashcards {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }

    .flashcard {
      background-color: #fff;
      width: 250px;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
      text-align: center;
    }

    .flashcard:hover {
      transform: translateY(-10px);
    }

    .flashcard img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 10px;
    }

    .flashcard h3 {
      font-size: 1.5em;
      margin-top: 15px;
      margin-bottom: 10px;
    }

    .flashcard p {
      font-size: 1.1em;
      color: #555;
    }

    .price-cta {
      text-align: center;
      padding: 50px 20px;
      background-color: #f8f9fa;
    }

    .price-cta a {
      text-decoration: none;
      font-size: 1.5em;
      padding: 15px 30px;
      background-color: #333;
      color: white;
      border-radius: 5px;
      transition: background 0.3s;
    }

    .price-cta a:hover {
      background-color: #495057;
    }

    .testimonials {
      background-color: #f1f1f1;
      padding: 50px 20px;
    }

    .testimonials h2 {
      font-size: 2.5em;
      text-align: center;
      margin-bottom: 20px;
    }

    .testimonial-carousel {
      width: 80%;
      max-width: 600px;
      margin: 0 auto;
      position: relative;
      overflow: hidden;
    }

    .testimonial-carousel .testimonial {
      display: none;
      text-align: center;
      font-size: 1.2em;
      font-style: italic;
      color: #555;
      background-color: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    .testimonial-carousel .testimonial.active {
      display: block;
    }

    .testimonial-carousel .dots {
      text-align: center;
      margin-top: 20px;
    }

    .testimonial-carousel .dots span {
      width: 15px;
      height: 15px;
      border-radius: 50%;
      background-color: #aaa;
      display: inline-block;
      margin: 0 5px;
      cursor: pointer;
    }

    .testimonial-carousel .dots span.active {
      background-color: #333;
    }

    .online-training {
      background-color: darkgray;
      padding: 50px 20px;
      text-align: center;
    }

    .online-training h2 {
      font-size: 2.3em;
      margin-bottom: 20px;
    }

    .online-training img {
      width: 90%;
      max-width: 600px;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      margin-bottom: 20px;
    }

    .online-training p {
      font-size: 1.2em;
      max-width: 700px;
      margin: 0 auto;
      color: #444;
    }
  </style>
 </head>
 <body>
  <div class="header">
   IRON BLOOM
  </div>
  <nav>
   <a href="#welcome">Home</a> <a href="#about">About Us</a> <a href="#programs">Programs</a> <a href="#price">Price Chart</a> <a href="#trial-form">Trial Form</a> <a href="#testimonials">Testimonials</a>
  </nav>
  <div class="hero-container">
   <img src="https://i.imgur.com/JHkQ7Ib.jpeg" alt="Hero Image">
  </div>
  <div class="welcome-cta" id="welcome">
   <h2>Welcome to IRON BLOOM</h2>
  </div>
  <div class="about-us" id="about">
   <h2>About Us</h2>
   <p>Iron Bloom Gym is known since 2015. Its Siliguri branch offers world-class equipment, certified trainers, and a variety of programs including personal training, Zumba, yoga, and CrossFit. What makes it unique is its science-backed approach to fitness, international standards, and a focus on holistic wellness—combining training, nutrition, and lifestyle coaching.</p>
  </div>
  <div class="programs" id="programs">
   <h2>Our Programs</h2>
   <div class="flashcards">
    <div class="flashcard">
     <img src="https://i.imgur.com/1zLnisn.jpeg" alt="Yoga">
     <h3>Yoga</h3>
     <p>Relax your body and mind</p>
    </div>
    <div class="flashcard">
     <img src="https://i.imgur.com/j3sbM5D.jpeg" alt="Gym Training">
     <h3>Gym Training</h3>
     <p>Get stronger every day</p>
    </div>
    <div class="flashcard">
     <img src="https://i.imgur.com/zFWwmLj.jpeg" alt="Zumba">
     <h3>Zumba</h3>
     <p>Fun and energetic workout</p>
    </div>
    <div class="flashcard">
     <img src="https://i.imgur.com/7YFhGqX.jpeg" alt="Personal Training">
     <h3>Personal Training</h3>
     <p>Training tailored to your needs</p>
    </div>
    <div class="flashcard">
     <img src="https://i.imgur.com/DcUr8WL.jpeg" alt="Nutrition Diet">
     <h3>Nutrition Diet</h3>
     <p>Healthy eating habits</p>
    </div>
   </div>
  </div><!-- New Online Training Section -->
  <div class="online-training">
   <h2>Introducing Our First Ever Online Yoga Class</h2><img src="https://i.imgur.com/WLIpSbd.jpeg" alt="Online Yoga Class">
   <p>We are excited to launch our first-ever online yoga training sessions! Join us from the comfort of your home through Zoom video calls. Connect, stretch, and grow with our certified trainers in real-time!</p>
  </div>
  <div class="price-cta" id="price">
   <a href="price.html">View Price Chart</a>
  </div><!-- Aesthetic Testimonial Carousel Section -->
  <section class="testimonial-carousel-section" style="background-color: white; padding: 60px 20px;">
   <h2 style="text-align: center; font-size: 2.2rem; margin-bottom: 40px; font-family: 'Playfair Display', serif;">What Our Yoga Clients Are Saying</h2>
   <div class="carousel-container" style="position: relative; max-width: 800px; margin: 0 auto;">
    <div class="testimonial-slide active" style="transition: opacity 0.5s ease;">
     <p style="font-size: 1.2rem; font-style: italic; text-align: center;">“Practicing yoga with MOTIV8 online has been a soul-refreshing experience. The sessions are peaceful, and I’ve become more flexible and calm.”</p>
     <p style="text-align: center; font-weight: bold; margin-top: 15px;">- Riya S.</p>
    </div>
    <div class="testimonial-slide" style="display: none;">
     <p style="font-size: 1.2rem; font-style: italic; text-align: center;">“Never thought I could feel so connected through a screen. The online yoga class is seamless, and the trainers are warm and professional.”</p>
     <p style="text-align: center; font-weight: bold; margin-top: 15px;">- Ananya T.</p>
    </div>
    <div class="testimonial-slide" style="display: none;">
     <p style="font-size: 1.2rem; font-style: italic; text-align: center;">“The best part of my day is tuning in to MOTIV8's yoga classes. My posture, breathing, and mental focus have all improved.”</p>
     <p style="text-align: center; font-weight: bold; margin-top: 15px;">- Kavya M.</p>
    </div><!-- Grey Dots -->
    <div class="carousel-dots" style="text-align: center; margin-top: 30px;">
     <span class="dot active" onclick="showSlide(0)"></span> <span class="dot" onclick="showSlide(1)"></span> <span class="dot" onclick="showSlide(2)"></span>
    </div>
   </div>
  </section><!-- Carousel Styles -->
  <style>
  .dot {
    height: 12px;
    width: 12px;
    margin: 0 6px;
    background-color: grey;
    border-radius: 50%;
    display: inline-block;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }

  .dot.active {
    background-color: #333;
  }

  .testimonial-slide {
    position: absolute;
    width: 100%;
    opacity: 0;
    transition: opacity 0.6s ease-in-out;
  }

  .testimonial-slide.active {
    position: relative;
    opacity: 1;
    display: block;
  }

  .carousel-container {
    position: relative;
    height: 180px;
  }

  @media (max-width: 600px) {
    .carousel-container {
      height: 250px;
    }
  }
</style><!-- Carousel Functionality -->
  <script>
  let currentIndex = 0;
  const slides = document.querySelectorAll(".testimonial-slide");
  const dots = document.querySelectorAll(".dot");

  function showSlide(index) {
    slides.forEach((slide, i) => {
      slide.classList.remove("active");
      slide.style.display = "none";
      dots[i].classList.remove("active");
    });

    slides[index].classList.add("active");
    slides[index].style.display = "block";
    dots[index].classList.add("active");
    currentIndex = index;
  }

  function autoSlide() {
    currentIndex = (currentIndex + 1) % slides.length;
    showSlide(currentIndex);
  }

  setInterval(autoSlide, 5000); // Change slide every 5 seconds
  </script> <!-- Why Choose Us Section as Flashcards -->
  <section style="background-color: #fff; padding: 60px 20px;">
   <h2 style="font-size: 2.5em; text-align: center; margin-bottom: 30px; color: #333;">Why Do Customers Choose IRON BLOOM?</h2>
   <div class="flashcards" style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
    <div class="flashcard" style="background-color: #fff; width: 250px; padding: 20px; border-radius: 10px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
     <h3 style="font-size: 1.5em; margin-bottom: 10px;">Supportive Environment</h3>
     <p style="font-size: 1.1em; color: #555;">We prioritize your well-being and growth in a space where you feel welcomed and supported.</p>
    </div>
    <div class="flashcard" style="background-color: #fff; width: 250px; padding: 20px; border-radius: 10px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
     <h3 style="font-size: 1.5em; margin-bottom: 10px;">Top-notch Tools and Training</h3>
     <p style="font-size: 1.1em; color: #555;">From equipment to expert-led sessions, we ensure you have everything to achieve your goals.</p>
    </div>
    <div class="flashcard" style="background-color: #fff; width: 250px; padding: 20px; border-radius: 10px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
     <h3 style="font-size: 1.5em; margin-bottom: 10px;">Convenience</h3>
     <p style="font-size: 1.1em; color: #555;">Both online and offline programs to suit your lifestyle and schedule.</p>
    </div>
    <div class="flashcard" style="background-color: #fff; width: 250px; padding: 20px; border-radius: 10px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
     <h3 style="font-size: 1.5em; margin-bottom: 10px;">Thriving Community</h3>
     <p style="font-size: 1.1em; color: #555;">Be part of a motivating and positive community that encourages each other every step of the way.</p>
    </div>
   </div>
  </section><!-- Free Trial Section -->
  <section style="background-color: beige; padding: 60px 20px; text-align: center;">
   <h2 style="font-size: 2.3em; color: #333; margin-bottom: 20px;">Start Your Free 3-Day Trial</h2>
   <p style="font-size: 1.2em; color: #555; max-width: 700px; margin: 0 auto 30px;">Experience IRON BLOOM Fitness with a complimentary 3-day trial. Discover what makes us the best choice for your wellness journey.</p><button class="cta-button" onclick="document.getElementById('trial-form').scrollIntoView({ behavior: 'smooth' });">Claim Your Trial</button>
  </section><!-- Trial Form Section -->
  <section id="trial-form" style="background-color: beige; padding: 60px 20px;">
   <h2 style="text-align: center; font-size: 2.3em; margin-bottom: 30px;">Trial Registration Form</h2>
   <form style="max-width: 600px; margin: 0 auto; display: flex; flex-direction: column; gap: 15px;">
    <input type="text" placeholder="Your Name" required style="padding: 12px; font-size: 1em;"> <input type="email" placeholder="Your Email" required style="padding: 12px; font-size: 1em;"> <input type="tel" placeholder="Your Phone Number" required style="padding: 12px; font-size: 1em;"> <input type="date" placeholder="Preferred Joining Date" required style="padding: 12px; font-size: 1em;"> <button type="submit" class="cta-button" style="align-self: center;">Submit</button>
   </form>
  </section>
  <style>
    /* Global Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }
    
    /* Contact Us Section Styles */
    .contact-us {
      background-color: #f1f1f1;
      padding: 60px 0;
    }

    .contact-us .container {
      max-width: 1200px;
      margin: 0 auto;
      text-align: center;
    }

    .contact-us h2 {
      font-size: 2.5rem;
      font-weight: bold;
      margin-bottom: 20px;
    }

    .contact-us p {
      font-size: 1.1rem;
      color: #555;
      margin-bottom: 40px;
    }

    .contact-us .grid {
      display: grid;
      grid-template-columns: 1fr;
      gap: 30px;
    }

    .contact-us .grid .contact-item {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 15px;
      font-size: 1.2rem;
    }

    .contact-us .grid i {
      font-size: 2rem;
      color: #4CAF50; /* Green color for icons */
    }

    .contact-us .grid .contact-item a {
      color: #333;
      text-decoration: none;
      font-weight: 600;
    }

    .contact-us .grid .contact-item a:hover {
      color: #4CAF50;
    }

    /* Responsive Styles */
    @media (min-width: 768px) {
      .contact-us .grid {
        grid-template-columns: 1fr 1fr;
      }
    }

    @media (min-width: 1024px) {
      .contact-us .grid {
        grid-template-columns: 1fr 1fr 1fr 1fr;
      }
    }
  </style> <!-- Contact Us Section -->
  <section style="background-color:#fff; padding: 60px 20px;">
   <h2 style="font-size: 2.5em; text-align: center; margin-bottom: 30px; color: #333;">Contact Us</h2>
   <div style="display: flex; flex-direction: column; align-items: center;">
    <div style="text-align: center; margin-bottom: 15px;">
     <p style="font-size: 1.2em; color: #555;">Phone: 9641258355</p>
    </div>
    <div style="text-align: center; margin-bottom: 15px;">
     <p style="font-size: 1.2em; color: #555;">WhatsApp: 9641258355</p>
    </div>
    <div style="text-align: center; margin-bottom: 15px;">
     <p style="font-size: 1.2em; color: #555;">Email: info@ironbloom.com</p>
    </div>
    <div style="text-align: center;">
     <p style="font-size: 1.2em; color: #555;">Address: Champasari, West Bengal,India.</p>
    </div>
   </div>
  </section> <!-- Footer Section -->
  <footer style="background-color: #343a40; color: white; text-align: center; padding: 30px 20px; margin-top: 60px;">
   <p style="margin: 0; font-size: 1em;">© IRON BLOOM. All rights reserved.</p>
  </footer>
  <script>
  let currentSlide = 0;
  const slides = document.querySelectorAll('.testimonial-slide');
  const dots = document.querySelectorAll('.dot');

  function showSlide(index) {
    slides.forEach((slide, i) => {
      slide.style.display = 'none';
      dots[i].classList.remove('active');
    });
    slides[index].style.display = 'block';
    dots[index].classList.add('active');
    currentSlide = index;
  }

  showSlide(currentSlide) 
  </script>
