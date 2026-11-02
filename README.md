# Ex02 Commercial Website
## Date: 27.10.2026

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
```

<!DOCTYPE html>
<html>
<head>
    <title>ShopEase - Commercial Website</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- Header -->
    <header>
        <h1>ShopEase</h1>

        <nav>
            <a href="#home">Home</a>
            <a href="#products">Products</a>
            <a href="#about">About Us</a>
            <a href="#contact">Contact</a>
            <a href="#account">Account</a>
        </nav>
    </header>

    <!-- Homepage -->
    <section id="home" class="hero">
        <h2>Welcome to ShopEase</h2>
        <p>Discover amazing products at affordable prices!</p>
        <button>Shop Now</button>
    </section>

    <!-- Products -->
    <section id="products">
        <h2>Our Products</h2>

        <div class="product-container">

            <div class="product">
                <img src="https://placehold.co/250x180?text=Headphones"
                     alt="Headphones">
                <h3>Headphones</h3>
                <p>Price: ₹999</p>
                <button>Buy Now</button>
            </div>

            <div class="product">
                <img src="https://placehold.co/250x180?text=Smartphone"
                     alt="Smartphone">
                <h3>Smartphone</h3>
                <p>Price: ₹14,999</p>
                <button>Buy Now</button>
            </div>

            <div class="product">
                <img src="https://placehold.co/250x180?text=Watch"
                     alt="Smart Watch">
                <h3>Smart Watch</h3>
                <p>Price: ₹1,999</p>
                <button>Buy Now</button>
            </div>

        </div>
    </section>

    <!-- About Us -->
    <section id="about">
        <h2>About Us</h2>
        <p>
            ShopEase is an online shopping platform that provides
            quality products at affordable prices.
            Our aim is to make shopping easy and convenient.
        </p>
    </section>

    <!-- Contact -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: support@shopease.com</p>
        <p>Phone: +91 9876543210</p>
    </section>

    <!-- User Account -->
    <section id="account">
        <h2>User Account</h2>
        <p>Welcome! Create an account or login to continue shopping.</p>
        <button>Login</button>
        <button>Register</button>
    </section>

    <!-- Footer -->
    <footer>
        <p>Follow us:</p>
        <a href="https://www.instagram.com/">Instagram</a>
        <a href="https://www.facebook.com/">Facebook</a>
        <a href="https://www.linkedin.com/">LinkedIn</a>

        <p>&copy; 2026 ShopEase. All Rights Reserved.</p>
    </footer>

</body>
</html>
```
```

/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f4f4f4;
    color: #333;
}

/* Header */
header {
    background-color: #183b2b;
    color: white;
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

nav {
    display: flex;
    gap: 20px;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    color: #ffd700;
}

/* Homepage */
.hero {
    background-color: #dceee3;
    text-align: center;
    padding: 70px 20px;
}

.hero h2 {
    font-size: 32px;
    margin-bottom: 15px;
}

.hero p {
    margin-bottom: 20px;
}

/* Buttons */
button {
    background-color: #183b2b;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    transition: 0.3s;
}

button:hover {
    background-color: #28764d;
}

/* Sections */
section {
    padding: 40px 20px;
    text-align: center;
}

section h2 {
    margin-bottom: 25px;
}

/* Products using Flexbox */
.product-container {
    display: flex;
    justify-content: center;
    gap: 25px;
    flex-wrap: wrap;
}

.product {
    background-color: white;
    padding: 20px;
    width: 260px;
    border-radius: 10px;
    box-shadow: 0 2px 8px #ccc;
    transition: transform 0.3s;
}

.product:hover {
    transform: translateY(-5px);
}

.product img {
    width: 100%;
    height: 180px;
    object-fit: cover;
    border-radius: 5px;
}

.product h3 {
    margin: 15px 0;
}

.product p {
    margin-bottom: 15px;
}

/* About and Contact */
#about, #contact {
    background-color: white;
    margin-top: 10px;
}

/* User Account */
#account {
    background-color: #dceee3;
}

#account button {
    margin: 5px;
}

/* Footer */
footer {
    background-color: #183b2b;
    color: white;
    text-align: center;
    padding: 25px;
}

footer a {
    color: white;
    text-decoration: none;
    margin: 10px;
}

footer a:hover {
    color: #ffd700;
}

footer p {
    margin: 10px;
}

/* Responsive Design */
@media (max-width: 600px) {
    header {
        flex-direction: column;
        gap: 15px;
    }

    nav {
        flex-wrap: wrap;
        justify-content: center;
    }
}
```

## OUTPUT

<img width="1920" height="1080" alt="Screenshot (318)" src="https://github.com/user-attachments/assets/2455169b-69b4-466a-9421-7c06536bd849" />
<img width="1920" height="1080" alt="Screenshot (319)" src="https://github.com/user-attachments/assets/10f94dad-4873-45f1-aff7-3ffa365fea71" />
<img width="1920" height="1080" alt="Screenshot (320)" src="https://github.com/user-attachments/assets/e1dccf29-ec3b-4310-b58f-b139b7497583" />



## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
