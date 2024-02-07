<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Accessible Me</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100;500&family=Stick+No+Bills:wght@300&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/main.css">
</head>
<body>
  <a href="#main-content" class="skip-link">Canadian Jerky</a>
  <header class="site-header">
    <h1>Canadian Jerky</h1>
    <nav class="main-nav">
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Products</a></li>
        <li><a href="#">Reservation</a></li>
        <li><a href="#">Studio</a></li>
      </ul>
    </nav>
  </header>
  <main class="main-content" role="main" id="main-content">
    <h1>Welcome to Canadian Jerky</h1>
    <p>Jerky has long appealed to its fans for its convenience (its portable!), tastiness, chewiness and its low-in-fat nature (jerky traditionally being made from lean cuts of meat, mainly beef).</p>
    <p>Some credit Native Americans for creating jerky centuries ago, while others say we have an ancient Inca tribe (the Quechua) to thank; either way, as a snack, this dried meat has proven its staying power.</p>
    <section class="owner">
      <h1>Meet the owner</h1>
      <ul>
        <li>Name: Danis</li>
        <li>Title: Supervisor</li>
        <li>Email: Danis@canadianjerky.ca</li>
        <li>Phone: 905 961 9822</li>
      </ul>
      <h1>Address</h1>
      <p>
        canadian Jerky
        2 - 2133 191 St,
         Surrey BC 
         V3Z 3M3
      </p>
    </section>
    <section class="contact-section">
      <h1>Contact Us</h1>
      <form action="thanks.html">
        <label for="fullName">Full Name</label>
        <input type="text" id="fullName" placeholder="Full Name" aria-label="Full Name" required>
        <label for="emailAddress">Email Address</label>
        <input type="email" id="emailAddress" placeholder="Email Address" aria-label="Email Address" required>
        <label for="subject">Subject</label>
        <input type="text" id="subject" placeholder="Subject" aria-label="Subject" required>
        <label for="message">Your Message</label>
        <textarea id="message" aria-label="Your Message" required></textarea>
        <button type="submit">Send</button>
      </form>
    </section>
  </main>
  <footer class="site-footer" role="contentinfo">
    &copy; 2024 Canadian Jerky
  </footer>
</body>
</html>
