<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gold and Diamond Jewelry</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Gold and Diamond Jewelry</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#shop">Shop</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home">
        <div class="container">
            <h2>Welcome to Our Jewelry Store</h2>
            <p>Discover the finest gold and diamond jewelry.</p>
        </div>
    </section>

    <section id="shop">
        <div class="container">
            <h2>Our Collection</h2>
            <div class="products">
                <!-- Product Item -->
                <div class="product">
                    <img src="images/ring.jpg" alt="Diamond Ring">
                    <h3>Diamond Ring</h3>
                    <p>$500</p>
                    <button class="add-to-cart">Add to Cart</button>
                </div>
                <!-- Add more products as needed -->
            </div>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>We offer the best gold and diamond jewelry crafted with precision and care.</p>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form id="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Gold and Diamond Jewelry. All rights reserved.</p>
        </div>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
