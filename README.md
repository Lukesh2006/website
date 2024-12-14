# Ex.07 Restaurant Website
# Date:14.12.24
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
# HOME
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RESTAURANT LJ</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.1/css/all.min.css" integrity="sha512-5Hs3dF2AEPkpNAR7UiOHba+lRSJNeM2ECkwxUIxC1Q/FLycGTbNapWXB4tP889k5T5Ju8fs4b1P5z/iB4nMfSQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <div class="top">
        <div lang="logo">LJ</div>
        <div class="nav">
            <a href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="about.html">Administration</a>
            <a href="location.html">Location</a>
            <a href="contact.html">Contact</a>
        </div>
        <div class="search">
            <i class="fa-solid fa-search"></i>
            <i class="fa-solid fa-bars"></i>
        </div>
    </div>

<!--my code-->
    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Welcome to RESTO LJ</h1>
            <p>Experience the finest dining in the heart of Chennai</p>
            <a href="menu.html" class="btn">View Menu</a>
        
        </div>
    </section>

    <div class="heading">
        <div class="left">
            <p>ARE YOU HUNGRY?</p>
            <h1>Don't wait</h1>
            <p>Lets start to order the food now</p>
            <button>
            <a href="menu.html" class="btn">check out</a>
            </button>
        </div>

        <div class="right" id="food"></div>

        <div class="socialmedia">
            <i class="fa-brands fa-facebook-f"></i>
            <i class="fa-brands fa-twitter"></i>
            <i class="fa-brands fa-instagram"></i>
            <i class="fa-brands fa-whatsapp"></i>
        </div>
    </div>

    <div class="bottom">
        <div class="menu">
            <div id="egg_rice"></div>
            <div id="fish_fry"></div>
            <div id="pasta"></div>
            <div id="veg_paneer"></div>
            <div id="veg_soup"></div>
            <div id="salad"></div>


        </div>
    </div>

    <script src="javascript.js"></script>
</body>
</html>
```
# MENU
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>RESTAURANT MENU</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f7f7f7;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        section h2 {
            color: #2c3e50;
            font-size: 2em;
            margin-bottom: 10px;
        }
        .menu-item {
            display: flex;
            justify-content: space-between;
            padding: 10px 0;
            border-bottom: 1px solid #ddd;
        }
        .menu-item:last-child {
            border-bottom: none;
        }
        .menu-item .name {
            font-size: 1.2em;
        }
        .menu-item .price {
            font-size: 1.2em;
            color: #27ae60;
        }
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>Restaurant LJ</h1>
        <p>Delicious Food, Great Atmosphere</p>
    </header>

    <section id="appetizers">
        <h2>Appetizers</h2>
        <div class="menu-item">
            <img src="m1.jpg" width="300" height="200" alt="Dish 1">
            <span class="name">Bruschetta</span>
            <span class="price">$8.99</span>
        </div>
        <div class="menu-item">
            <img src="m2.jpg" width="300" height="200" alt="Dish 2">
            <span class="name">Stuffed Mushrooms</span>
            <span class="price">$9.99</span>
        </div>
        <div class="menu-item">
            <img src="m3.jpg" width="300" height="200" alt="Dish 3">
            <span class="name">Fried Calamari</span>
            <span class="price">$12.99</span>
        </div>
    </section>

    <section id="main-courses">
        <h2>Main Courses</h2>
        <div class="menu-item">
            <img src="grilled chick.jpg" width="300" height="200" alt="Dish 4">
            <span class="name">Grilled Chicken Alfredo</span>
            <span class="price">$15.99</span>
        </div>
        <div class="menu-item">
            <img src="veg stir.avif" width="300" height="200" alt="Dish 5">
            <span class="name">Vegetable Stir Fry</span>
            <span class="price">$13.99</span>
        </div>
        <div class="menu-item">
            <img src="m6.jpeg" width="300" height="200" alt="Dish 6">
            <span class="name">Beef Steak</span>
            <span class="price">$22.99</span>
        </div>
    </section>

    <section id="desserts">
        <h2>Desserts</h2>
        <div class="menu-item">
            <img src="m7.jpg" width="300" height="200" alt="Dish 7">
            <span class="name">Tiramisu</span>
            <span class="price">$7.99</span>
        </div>
        <div class="menu-item">
            <img src="m8.jpg" width="300" height="200" alt="Dish 8">
            <span class="name">Cheesecake</span>
            <span class="price">$6.99</span>
        </div>
        <div class="menu-item">
            <img src="coco cake.webp" width="300" height="200" alt="Dish 9">
            <span class="name">Chocolate Lava Cake</span>
            <span class="price">$8.49</span>
        </div>
    </section>

    <section id="drinks">
        <h2>Drinks</h2>
        <div class="menu-item">
            <img src="m10.jpg" width="300" height="200" alt="Dish 10">
            <span class="name">Lemonade</span>
            <span class="price">$3.99</span>
        </div>
        <div class="menu-item">
            <img src="m11.jpg" width="300" height="200" alt="Dish 11">
            <span class="name">Iced Tea</span>
            <span class="price">$2.99</span>
        </div>
        <div class="menu-item">
            <img src="rose milk.jpg" width="300" height="200" alt="Dish 12">
            <span class="name">Rose milk</span>
            <span class="price">$1.99</span>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Restaurant LJ - All Rights Reserved</p>
        <section> 
            <!-- Back button --> 
             <button onclick="goBack()">Back</button> 
            <script> 
                function goBack() { window.history.back(); }
            </script>
         </section>
    </footer>

</body>
</html>
```
# ADMINISTRATION
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>About Us - RESTAURANT LJ</title>
    <style>
        /* Reset default margin and padding */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: #f7f7f7;
            color: #333;
        }

        /* Header Styling */
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            font-size: 3em;
            margin: 0;
        }

        header nav {
            margin-top: 20px;
        }

        header nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.1em;
        }

        header nav a:hover {
            text-decoration: underline;
        }

        /* About Us Section */
        .about-us {
            padding: 50px;
            text-align: center;
            background-color: white;
            margin: 20px auto;
            max-width: 1000px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
        }

        .about-us h2 {
            font-size: 2.5em;
            color: #2c3e50;
            margin-bottom: 20px;
        }

        .about-us p {
            font-size: 1.2em;
            line-height: 1.6;
            color: #7f8c8d;
            margin-bottom: 30px;
        }

        /* Mission and Values Section */
        .mission-values {
            display: flex;
            justify-content: space-around;
            padding: 50px 0;
            background-color: #ecf0f1;
        }

        .mission-values div {
            width: 45%;
            text-align: center;
            padding: 20px;
        }

        .mission-values h3 {
            font-size: 2em;
            margin-bottom: 15px;
            color: #27ae60;
        }

        .mission-values p {
            font-size: 1.2em;
            color: #7f8c8d;
        }

        /* Team Section */
        .team {
            padding: 50px 20px;
            text-align: center;
        }

        .team h2 {
            font-size: 2.5em;
            margin-bottom: 40px;
            color: #2c3e50;
        }

        .team .team-members {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .team-member {
            width: 30%;
            text-align: center;
            margin-bottom: 30px;
        }

        .team-member img {
            width: 100%;
            height: auto;
            border-radius: 50%;
            border: 4px solid #fff;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .team-member h3 {
            font-size: 1.5em;
            color: #2c3e50;
            margin-top: 15px;
        }

        .team-member p {
            color: #7f8c8d;
            font-size: 1.1em;
        }

        /* Footer Styling */
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px;
            position: relative;
            bottom: 0;
            width: 100%;
        }

    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Restaurant LJ</h1>
        <nav>
            <a href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="about.html">About Us</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <!-- About Us Section -->
    <section class="about-us">
        <h2>Our Story</h2>
        <p>Welcome to Restaurant Name, where we bring together the finest ingredients and a passion for great food. Our journey began with the dream of providing a cozy yet sophisticated dining experience where guests can enjoy delicious meals, made with love, in a warm, inviting atmosphere. Whether you're here for a special occasion or just a casual meal, we aim to provide an unforgettable experience.</p>
    </section>

    <!-- Mission and Values Section -->
    <section class="mission-values">
        <div>
            <h3>Our Mission</h3>
            <p>Our mission is to offer an exceptional dining experience with high-quality, locally-sourced ingredients, expert culinary techniques, and a focus on sustainability.</p>
        </div>
        <div>
            <h3>Our Values</h3>
            <p>We believe in creating a positive impact through the food we serve and the way we serve it. Our values are centered around quality, hospitality, and community.</p>
        </div>
    </section>

    <!-- Team Section -->
    <section class="team">
        <h2>Meet Our Team</h2>
        <div class="team-members">
            <div class="team-member">
                <img src="c1.webp" height="200" width="200" alt="Team Member 1">
                <h3>John Doe</h3>
                <p>Head Chef</p>
            </div>
            <div class="team-member">
                <img src="c2.jpg" height="200" width="200"alt="Team Member 2">
                <h3>Jane smith</h3>
                <p>Restaurant Manager</p>
            </div>
            <div class="team-member">
                <img src="c3.jpg" height="200" width="200"alt="Team Member 3">
                <h3>Michael Lee</h3>
                <p>Sous chef</p>
            </div>
            <div class="team-member">
                <img src="c4.webp" height="200" width="200"alt="Team Member 4">
                <h3>David</h3>
                <p>Baker</p>
            </div>
            <div class="team-member">
                <img src="c5.jpg" height="200" width="200"alt="Team Member 5">
                <h3>William Turner</h3>
                <p>Helper</p>
            </div>
            <div class="team-member">
                <img src="c6.png" height="200" width="200"alt="Team Member 6">
                <h3>Jack</h3>
                <p>Helper</p>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Restaurant Name. All rights reserved.</p>
    </footer>

</body>
</html>
```
# LOCATION
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RESTAURANT LJ</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        .container {
            padding: 2rem;
            text-align: center;
        }
        .map {
            margin: 2rem 0;
            border: 1px solid #ccc;
            width: 100%;
            height: 400px;
        }
        .address {
            margin: 1rem 0;
            font-size: 1.2rem;
        }
        .hours {
            margin-top: 1.5rem;
            font-size: 1rem;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Visit Us at Restaurant LJ</h1>
    </div>

    <div class="container">
        <p class="address">
            <strong>Address:</strong><br>
            123 Foodie Lane,<br>
            Flavor Town, FT 56789
        </p>

        <p class="hours">
            <strong>Opening Hours:</strong><br>
            Monday - Friday: 11:00 AM - 10:00 PM<br>
            Saturday - Sunday: 9:00 AM - 11:00 PM
        </p>

        <div>
            <iframe 
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3153.835434509797!2d-122.41941508468177!3d37.774929279759714!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80858064d733b13f%3A0xe816e6b4b1bbabe3!2s123%20Foodie%20Ln%2C%20Flavor%20Town%2C%20FT%2056789!5e0!3m2!1sen!2sus!4v1617044383172!5m2!1sen!2sus" 
                class="map" 
                allowfullscreen="" 
                loading="lazy">
            </iframe>
        </div>

        <p>Need help finding us? Call us at <strong>(123) 456-7890</strong></p>
    </div>
</body>
</html>
```
# CONTACT
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Contact Us - RESTAURANT LJ</title>
    <style>
        /* Reset default margin and padding */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: #f7f7f7;
            color: #333;
        }

        /* Header Styling */
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            font-size: 3em;
            margin: 0;
        }

        header nav {
            margin-top: 20px;
        }

        header nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.1em;
        }

        header nav a:hover {
            text-decoration: underline;
        }

        /* Contact Info Section */
        .contact-info {
            padding: 50px;
            text-align: center;
            background-color: white;
            margin: 20px auto;
            max-width: 1000px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
        }

        .contact-info h2 {
            font-size: 2.5em;
            color: #2c3e50;
            margin-bottom: 20px;
        }

        .contact-info p {
            font-size: 1.2em;
            color: #7f8c8d;
            margin-bottom: 30px;
        }

        .contact-info div {
            margin-bottom: 20px;
        }

        .contact-info div i {
            font-size: 1.5em;
            color: #27ae60;
            margin-right: 10px;
        }

        /* Contact Form Section */
        .contact-form {
            display: flex;
            justify-content: space-around;
            padding: 50px 0;
        }

        .contact-form form {
            width: 45%;
            background-color: white;
            padding: 30px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 15px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1em;
        }

        .contact-form button {
            width: 100%;
            padding: 15px;
            background-color: #27ae60;
            color: white;
            font-size: 1.2em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .contact-form button:hover {
            background-color: #2ecc71;
        }

        /* Google Map Section */
        .google-map {
            margin-top: 50px;
            width: 100%;
            height: 400px;
        }

        /* Footer Styling */
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Restaurant LJ</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="about.html">About Us</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <!-- Contact Info Section -->
    <section class="contact-info">
        <h2>Contact Us</h2>
        <p>We’d love to hear from you! Whether you have a question or want to make a reservation, feel free to get in touch.</p>

        <div>
            <i class="fa fa-phone"></i>
            <strong>Phone:</strong> (123) 456-7890
        </div>
        <div>
            <i class="fa fa-envelope"></i>
            <strong>Email:</strong> contact@restaurant.com
        </div>
        <div>
            <i class="fa fa-map-marker"></i>
            <strong>Address:</strong> 123 Main Street, City, Country
        </div>
    </section>

    <!-- Contact Form Section -->
    <section class="contact-form">
        <form action="mailto:contact@restaurant.com" method="POST" enctype="text/plain">
            <h3>Send Us a Message</h3>
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="6" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Google Map Section -->
    <section class="google-map">
        <h2>Find Us Here</h2>
        <iframe src="https://www.google.com/maps/embed/v1/place?q=Restaurant%20Location&key=YOUR_API_KEY"
            frameborder="0" style="border:0;width:100%;height:100%;" allowfullscreen>
        </iframe>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Restaurant Name. All rights reserved.</p>
    </footer>

</body>
</html>
```
# OUTPUT:
![home](https://github.com/user-attachments/assets/0348d4ff-5679-46f8-bdfc-9d5f3473e55f)
![MENU SA](https://github.com/user-attachments/assets/434de773-f3dc-4c77-b08a-a525e4e0497d)
![administration](https://github.com/user-attachments/assets/f88eeeec-240d-4940-9683-e6bda4757909)
![contact us](https://github.com/user-attachments/assets/aaaef6c9-d545-43ed-853c-ca6be63fb760)
![contact](https://github.com/user-attachments/assets/78dbb492-403a-4229-aa6b-2038013f9172)





# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
