# Ex.06 Restaurant Website
## Date: 6/1/2026

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Spice Symphony Restaurant</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #fff8f0;
        }

        header {
            background-color: #8b0000;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #333;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: orange;
        }

        .banner img {
            width: 100%;
            height: 350px;
            object-fit: cover;
        }

        section {
            padding: 30px;
            text-align: center;
        }

        h2 {
            color: #8b0000;
        }

        .menu {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .menu-item {
            background-color: white;
            width: 250px;
            margin: 15px;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 0 10px #ccc;
        }

        .menu-item img {
            width: 100%;
            height: 160px;
            border-radius: 10px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>
<body>

<header>
    <h1>Spice Symphony</h1>
    <p>Where Every Flavor Finds Its Rhythm</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
</nav>

<div class="banner" id="home">
    <img src="https://images.unsplash.com/photo-1552566626-52f8b828add9" alt="Restaurant Banner">
</div>

<section id="menu">
    <h2>Our Menu</h2>

    <div class="menu">
        <div class="menu-item">
            <img src="https://upload.wikimedia.org/wikipedia/commons/d/d3/Supreme_pizza.jpg" alt="Pizza">
            <h3>Cheese Pizza</h3>
            <p>₹250</p>
        </div>

        <div class="menu-item">
            <img src="https://images.unsplash.com/photo-1550547660-d9450f859349" alt="Burger">
            <h3>Veg Burger</h3>
            <p>₹150</p>
        </div>

        <div class="menu-item">
            <img src="https://images.unsplash.com/photo-1589302168068-964664d93dc0" alt="Biryani">
            <h3>Veg Biryani</h3>
            <p>₹200</p>
        </div>

        <div class="menu-item">
            <img src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c" alt="Salad">
            <h3>Healthy Salad</h3>
            <p>₹120</p>
        </div>
    </div>
</section>

<section id="services">
    <h2>Our Services</h2>
    <p>Dine-in | Takeaway | Online Delivery | Catering Services</p>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>📍 Chennai, Tamil Nadu</p>
    <p>📞 +91 98765 43210</p>
    <p>✉️ spicesymphony@gmail.com</p>
</section>

<footer>
    <p>© 2026 Spice Symphony Restaurant. All Rights Reserved.</p>
</footer>

</body>
</html>
```

## OUTPUT:
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/6ce3b039-0b88-4fcb-bbdb-4ba83e73bcdc" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/b1cf0a81-ddc0-4b39-9911-e2505a739602" />

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
