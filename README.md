
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>All Sons IV Family Homes</title>
  <!-- Cursive Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      min-height: 100vh;
      background-image: url("image5.jpg");
      background-size: cover;
      background-position: center;
      font-family: Arial, sans-serif;
      color: white;
    }

    .content {
      max-width: 700px;
      margin: 50px auto;
      padding: 25px;
      background-color: rgba(0,0,0,0.5);
      border-radius: 10px;
      text-align: justify;
    }

    h1 {
      text-align: center;
      font-family: 'Dancing Script', cursive;
      font-size: 3em;
      margin-bottom: 20px;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.7);
    }

    .button {
      display: block;
      width: 200px;
      margin: 20px auto;
      padding: 10px;
      text-align: center;
      background-color: #007BFF;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }

    .button:hover {
      background-color: #0056b3;
    }

    .contact-form {
      margin-top: 30px;
      background-color: rgba(0,0,0,0.6);
      padding: 20px;
      border-radius: 10px;
    }

    .contact-form label {
      display: block;
      margin: 10px 0 5px;
      color: #FFD700;
      font-weight: bold;
    }

    .contact-form input,
    .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: none;
      border-radius: 5px;
      background-color: rgba(255,255,255,0.2);
      color: #FFD700;
    }

    .contact-form input::placeholder,
    .contact-form textarea::placeholder {
      color: #FFD700;
      opacity: 1;
    }

    .contact-form button {
      width: 100%;
      padding: 10px;
      background-color: #FFA500;
      color: white;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
    }

    .contact-form button:hover {
      background-color: #FF8C00;
    }
  </style>
</head>
<body>
  <div class="content">
    <h1>All Sons IV</h1>
    <p>
      This is a family owned and operated company always on the look to expand, we strive to bring you not just a house but a true home! 
      This started as just a one-time flip out in Westmoreland, TN and grew into something that has really brought the joy of being able to bring the perfect home to people just like you and me!
    </p>

    <a href="#" class="button">Learn More</a>

    <div class="contact-form">
      <h2 style="color:white; text-align:center;">Contact Us</h2>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" value="David Minch" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" value="davidminch612@gmail.com" required>

        <label for="phone">Phone:</label>
        <input type="tel" id="phone" name="phone" value="615-755-3657" required>

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="5" placeholder="Your Message" required></textarea>

        <button type="submit">Send Message</button>
      </form>
    </div>
  </div>
</body>
</html>
