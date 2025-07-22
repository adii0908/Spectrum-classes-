
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title> Spectrum Classes</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f0f8ff;
      color: #333;
    }
    header {
      background: #0077cc;
      color: white;
      padding: 30px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 36px;
    }
    header p {
      font-size: 18px;
      margin-top: 10px;
    }
    .section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .section h2 {
      font-size: 28px;
      margin-bottom: 20px;
      text-align: center;
      color: #0077cc;
    }
    .about p {
      line-height: 1.7;
      font-size: 17px;
      text-align: center;
    }
    .courses {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .course-card {
      background: #fff;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .course-card h3 {
      color: #0077cc;
      margin-bottom: 10px;
    }
    .course-card p {
      font-size: 15px;
      line-height: 1.5;
    }
    .contact form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 500px;
      margin: auto;
    }
    .contact label {
      font-weight: bold;
    }
    .contact input, .contact textarea {
      padding: 10px;
      border: 1px solid #aaa;
      border-radius: 5px;
    }
    .contact button {
      background: #0077cc;
      color: white;
      border: none;
      padding: 12px;
      border-radius: 5px;
      cursor: pointer;
    }
    .contact button:hover {
      background: #005fa3;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #0077cc;
      color: white;
    }
  </style>
</head>
<body>

  <header>
    <h1>Spectrum Classes</h1>
    <p>Your Success, Our Mission</p>
  </header>

  <section class="section about">
    <h2>About Us</h2>
    <p>We are dedicated to guiding students from Classes 6 to 12 with expert teaching and personalized attention. Our mission is to build a strong academic foundation for each student through effective techniques and regular assessments.</p>
  </section>

  <section class="section">
    <h2>Courses Offered</h2>
    <div class="courses">
    <div class="course-card">
        <h3>Class 8 - Foundation Course</h3>
        <p>Subjects: Maths, Science, English</p>
        <p>Batch Time: 4:00 PM – 6:00 PM</p>
      </div>
      <div class="course-card">
        <h3>Class 10 (CBSE)</h3>
        <p>Subjects: Maths, Science, English<br>Batch Timings: 5–7 PM<br>Weekly Tests Included</p>
      </div>
      <div class="course-card">
        <h3>Class 12 (PCM)</h3>
        <p>Subjects: Physics, Chemistry, Maths<br>Timings: 4–6 PM<br>JEE Foundation Included</p>
      </div>
      <div class="course-card">
        <h3>NEET Coaching</h3>
        <p>Subjects: Biology, Physics, Chemistry<br>Timings: 6–8 PM<br>Mock Tests & Doubt Sessions</p>
      </div>
    </div>
  </section>

  <section class="section contact">
    <h2>Contact Us</h2>
    <form   
      action="https://formsubmit.co/htmlcoderbytqb.com@gmail.com"       <label for="name">Your Name</label>
      <input type="text" id="name" placeholder="Enter your name" required>

      <label for="phone">Phone Number</label>
      <input type="tel" id="phone" placeholder="Enter your phone number" required>

      <label for="message">Your Message</label>
      <textarea id="message" rows="5" placeholder="Write your message here..." required></textarea>

      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    &copy; 2025 Spectrum classes . All Rights Reserved.
  </footer>

</body>
</html>
