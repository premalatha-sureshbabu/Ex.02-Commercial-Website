# Ex02 Commercial Website
## Date:11.03.25

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
### Index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home - Procart</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul class="navbar">
        <li><a href="index.html">Home</a></li>
        <li><a href="services.html">Services</a></li>
        <li><a href="about.html">About Us</a></li>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="account.html">Account</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="section">
    <h1>Welcome to Procart</h1>
    <img src="hero.png" alt="Hero Image" class="hero-img">
    <p>Discover amazing products and services that meet all your needs.</p>
  </section>

  <footer>
    <p>&copy; 2025 Commercial Inc. | Follow us on
      <a href="#">Facebook</a>, <a href="#">Twitter</a>, <a href="#">Instagram</a>
    </p>
  </footer>
</body>
</html>
```
### Services.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Services - Procart</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul class="navbar">
        <li><a href="index.html">Home</a></li>
        <li><a href="services.html">Services</a></li>
        <li><a href="about.html">About Us</a></li>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="account.html">Account</a></li>
      </ul>
    </nav>
  </header>

  <section id="services" class="section">
    <h2>Our Services</h2>
    <div class="service-list">
      <div class="service-item">
        <h3>E-commerce Storefront</h3>
        <p>A user-friendly platform offering a wide range of products, including electronics, fashion, home goods, and more, with seamless online shopping and secure checkout options.</p>
      </div>
      <div class="service-item">
        <h3>Fast & Reliable Delivery</h3>
        <p>We ensure quick and reliable shipping to your doorstep, with real-time tracking and delivery updates, so you can shop with confidence.</p>
      </div>
      <div class="service-item">
        <h3>Customer Support & Returns</h3>
        <p>Our dedicated customer support team is available to assist you with any inquiries or issues. We offer hassle-free returns and exchanges to ensure your satisfaction with every purchase.</p>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Commercial Inc. | Follow us on
      <a href="#">Facebook</a>, <a href="#">Twitter</a>, <a href="#">Instagram</a>
    </p>
  </footer>
</body>
</html>
```
### About.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Us - Procart</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul class="navbar">
        <li><a href="index.html">Home</a></li>
        <li><a href="services.html">Services</a></li>
        <li><a href="about.html">About Us</a></li>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="account.html">Account</a></li>
      </ul>
    </nav>
  </header>

  <section id="about" class="section">
    <h2>About Us</h2>
    <p>Welcome to ProCart, your one-stop destination for premium products at unbeatable prices. We are a dynamic e-commerce platform dedicated to providing our customers with a wide range of high-quality goods, from the latest electronics to stylish fashion and home essentials. At ProCart, our mission is simple – to make shopping easy, fast, and enjoyable. We focus on delivering an exceptional user experience with secure payments, fast shipping, and outstanding customer service. Whether you're shopping for yourself or looking for the perfect gift, ProCart is here to help you find exactly what you need. Thank you for choosing us – your satisfaction is our priority!</p>
  </section>

  <footer>
    <p>&copy; 2025 Commercial Inc. | Follow us on
      <a href="#">Facebook</a>, <a href="#">Twitter</a>, <a href="#">Instagram</a>
    </p>
  </footer>
</body>
</html>
```
### Contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - Commercial Website</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul class="navbar">
        <li><a href="index.html">Home</a></li>
        <li><a href="services.html">Services</a></li>
        <li><a href="about.html">About Us</a></li>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="account.html">Account</a></li>
      </ul>
    </nav>
  </header>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <p>Have any questions? Reach out to us through the following channels:</p>
    <ul>
      <li>Email: contact@Procart.com</li>
      <li>Phone: (+91)7654347891</li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 Commercial Inc. | Follow us on
      <a href="#">Facebook</a>, <a href="#">Twitter</a>, <a href="#">Instagram</a>
    </p>
  </footer>
</body>
</html>
```
### Account.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Account - ProCart</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul class="navbar">
        <li><a href="index.html">Home</a></li>
        <li><a href="services.html">Services</a></li>
        <li><a href="about.html">About Us</a></li>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="account.html">Account</a></li>
      </ul>
    </nav>
  </header>

  <section id="account" class="section">
    <h2>User Account</h2>
    <p>Create an account to manage your orders and track your purchases.</p>

    <!-- Account Form Box -->
    <div class="account-box">
      <h3>Sign Up</h3>
      <form action="#" method="POST" id="signUpForm">
        <div class="form-field">
          <label for="username">Username</label>
          <input type="text" id="username" name="username" required placeholder="Enter your username">
        </div>
        <div class="form-field">
          <label for="email">Email Address</label>
          <input type="email" id="email" name="email" required placeholder="Enter your email">
        </div>
        <div class="form-field">
          <label for="password">Password</label>
          <input type="password" id="password" name="password" required placeholder="Enter your password">
        </div>
        <div class="form-field">
          <label for="confirm-password">Confirm Password</label>
          <input type="password" id="confirm-password" name="confirm-password" required placeholder="Confirm your password">
        </div>
        <button type="submit" class="sign-up-btn">Sign Up</button>
      </form>

      <p>Already have an account? <a href="login.html">Log in</a></p>
    </div>

  </section>

  <footer>
    <p>&copy; 2025 ProCart. Follow us on 
      <a href="#">Facebook</a>, <a href="#">Twitter</a>, <a href="#">Instagram</a>
    </p>
  </footer>

  <script>
    // Basic validation for password match
    document.getElementById('signUpForm').addEventListener('submit', function(event) {
      const password = document.getElementById('password').value;
      const confirmPassword = document.getElementById('confirm-password').value;

      if (password !== confirmPassword) {
        alert("Passwords do not match!");
        event.preventDefault(); // Prevent form submission
      }
    });
  </script>
</body>
</html>
```
Style.css
```
/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', sans-serif;
}

body {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
    background-color: #f8f8f8;
}

header {
    background-color: #333;
    padding: 10px 0;
}

.navbar {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 30px;
}

.navbar a {
    color: white;
    text-decoration: none;
    transition: color 0.3s;
}

.navbar a:hover {
    color: #f0a500;
}

.section {
    flex: 1;
    padding: 40px;
    text-align: center;
    background-color: #f4f4f4;
    border-bottom: 1px solid #ddd;
}

.hero-img {
    width: 100%;
    height: auto;
    max-width: 1200px;
    margin-top: 20px;
}

.service-list {
    display: flex;
    justify-content: space-around;
    gap: 20px;
}

.service-item {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    width: 30%;
}

footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 15px;
}

footer a {
    color: #f0a500;
    text-decoration: none;
}

footer a:hover {
    text-decoration: underline;
}

/* Account Page Specific Styles */
#account .account-box {
    background-color: white;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    width: 350px;
    margin: 40px auto;
    border: 2px solid #007bff; /* Border for the box */
}

#account .account-box h3 {
    margin-bottom: 20px;
}

#account .account-box .form-field {
    margin-bottom: 20px;
}

#account .account-box .form-field label {
    display: block;
    font-weight: bold;
    margin-bottom: 5px;
}

#account .account-box .form-field input {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
    border: 1px solid #ccc;
    border-radius: 5px;
    background-color: #f9f9f9;
}

#account .account-box .sign-up-btn {
    width: 100%;
    padding: 12px;
    background-color: #007bff;
    color: white;
    border: none;
    cursor: pointer;
    border-radius: 5px;
    font-size: 16px;
}

#account .account-box .sign-up-btn:hover {
    background-color: #0056b3;
}

#account .account-box p {
    margin-top: 20px;
}

#account .account-box p a {
    text-decoration: none;
    color: #007bff;
}

#account .account-box p a:hover {
    text-decoration: underline;
}
```
## OUTPUT
![Screenshot (37)](https://github.com/user-attachments/assets/2f7ea0c7-43de-4e92-82de-bdab1743d5a9)
![Screenshot (38)](https://github.com/user-attachments/assets/ef09f969-73a3-4f63-baee-36144ac20f4c)
![Screenshot (39)](https://github.com/user-attachments/assets/de246ab8-f83b-47e2-8a27-7c49a40e21d9)
![Screenshot (40)](https://github.com/user-attachments/assets/4ad4298d-3568-49dc-a987-5e82fb3ae2af)
![Screenshot (41)](https://github.com/user-attachments/assets/890a0b48-2726-49e7-8adb-6aa2345fce1f)


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
