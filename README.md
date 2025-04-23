<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Your Mental Health Space</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f7fa;
      color: #333;
    }
    header, section, footer {
      padding: 40px 20px;
      text-align: center;
    }
    header {
      background: #c2e7da;
      color: #004d40;
    }
    .section-title {
      font-size: 28px;
      margin-bottom: 20px;
    }
    .btn {
      background-color: #00897b;
      color: white;
      padding: 12px 24px;
      border: none;
      border-radius: 8px;
      text-decoration: none;
      font-size: 16px;
    }
    .service-card {
      background: #fff;
      margin: 10px auto;
      padding: 20px;
      border-radius: 12px;
      max-width: 400px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    footer {
      background: #eeeeee;
      font-size: 14px;
    }
  </style>
</head>
<body>

<header>
  <h1>Welcome to Your Mental Health Space</h1>
  <p>A safe place for support, healing, and growth.</p>
  <a href="#services" class="btn">Explore Services</a>
</header>

<section id="about">
  <h2 class="section-title">About Me</h2>
  <p>Hi, I’m Tess. I created this space to support teens and young adults in their mental health journeys. My mission is to provide compassionate, accessible, and uplifting care.</p>
</section>

<section id="services">
  <h2 class="section-title">Our Services</h2>
  <div class="service-card">
    <h3>1:1 Virtual Sessions</h3>
    <p>Personal, private support sessions tailored to your needs.</p>
  </div>
  <div class="service-card">
    <h3>Support Groups</h3>
    <p>Weekly group chats and discussions to feel connected and understood.</p>
  </div>
  <div class="service-card">
    <h3>Wellness Workshops</h3>
    <p>Interactive sessions on stress, anxiety, confidence, and more.</p>
  </div>
</section>

<section id="appointments">
  <h2 class="section-title">Book an Appointment</h2>
  <p>Use the form below to schedule your session.</p>
  <p><a href="https://calendly.com/" class="btn" target="_blank">Book with Calendly</a></p>
</section>

<section id="contact">
  <h2 class="section-title">Get in Touch</h2>
  <form action="https://formsubmit.co/your-email@example.com" method="POST">
    <input type="text" name="name" placeholder="Your Name" required /><br/><br/>
    <input type="email" name="email" placeholder="Your Email" required /><br/><br/>
    <textarea name="message" placeholder="How can I help you?" rows="4" required></textarea><br/><br/>
    <button type="submit" class="btn">Send Message</button>
  </form>
</section>

<footer>
  <p>© 2025 Your Mental Health Space | Follow on Instagram @yourhandle</p>
</footer>

</body>
</html>
