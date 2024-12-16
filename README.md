# Ex.07 Restaurant Website
## Date:13.12.2024

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
menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="res.jpeg" alt="Restaurant Logo">
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="menu">
        <h1>Our Menu</h1>

        <!-- Dessert Section -->
        <div class="menu-category">
            <h2>Desserts</h2>
            <div class="dessert-item">
                <img src="ca.jpeg" alt="Chocolate Cake" class="dessert-image">
                <div class="dessert-details">
                    <h3>Chocolate Cake</h3>
                    <p>A rich and moist chocolate cake topped with creamy chocolate ganache.</p>
                </div>
            </div>
            <div class="dessert-item">
                <img src="d1.jpeg" alt="Cheesecake" class="dessert-image">
                <div class="dessert-details">
                    <h3>Cheesecake</h3>
                    <p>A creamy, tangy cheesecake with a buttery graham cracker crust.</p>
                </div>
            </div>
            <div class="dessert-item">
                <img src="d3.jpeg" alt="Apple Pie" class="dessert-image">
                <div class="dessert-details">
                    <h3>Apple Pie</h3>
                    <p>A classic dessert made with sweet apples and a flaky pie crust.</p>
                </div>
            </div>
            <div class="dessert-item">
                <img src="d4.jpeg" alt="Tiramisu" class="dessert-image">
                <div class="dessert-details">
                    <h3>Tiramisu</h3>
                    <p>An Italian dessert made of layered coffee-soaked ladyfingers and mascarpone cheese.</p>
                </div>
            </div>
        </div>

    </section>

    <footer>
        <p>&copy; Harshitha</p>
    </footer>
</body>
</html>

about.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="about.jpeg" alt="Restaurant Logo">
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="about">
        <h1>About Our Restaurant</h1>
        <p>We are a family-owned restaurant serving the finest dishes from around the world. We strive to provide our customers with a memorable dining experience.</p>
    </section>

    <footer>
        <p>&copy; 2024 Harshitha</p>
    </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="contact.jpeg" alt="Restaurant Logo">
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h1>Contact Us</h1>
        <p>Address: 123 Restaurant Street, Food City, FC 12345</p>
        <p>Phone: (123) 456-7890</p>
        <p>Email: contact@restaurant.com</p>
    </section>

    <footer>
        <p>&copy; 2024 Harshitha</p>
    </footer>
</body>
</html>

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="ad.jpeg" alt="Restaurant Logo">
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="administration">
        <h1>Our Team</h1>
        <div class="team-member">
            <img src="harshu.jpeg" alt="Person 1">
            <p>Harshitha - Manager</p>
        </div>
        <div class="team-member">
            <img src="s1.jpeg" alt="Person 2">
            <p>Jane Smith - Manager</p>
        </div>
        <div class="team-member">
            <img src="s2.jpeg" alt="Person 3">
            <p>Mark Johnson - Chef</p>
        </div>
        <div class="team-member">
            <img src="s3.jpeg" alt="Person 4">
            <p>Lucy Brown - Sous Chef</p>
        </div>
        <div class="team-member">
            <img src="s4.jpeg" alt="Person 5">
            <p>Tom Harris - Waiter</p>
        </div>
        <div class="team-member">
            <img src="s5.jpeg" alt="Person 6">
            <p>Emma White - Accountant</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Harshitha</p>
    </footer>
</body>
</html>

index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.jpeg" alt="Restaurant Logo">
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <img src="ban.jpeg" alt="Restaurant Banner">
    </section>

    <section class="intro">
        <h1>Welcome to Our Restaurant</h1>
        <p>Enjoy the finest food and drinks in a cozy environment!</p>
    </section>

    <footer>
        <p>&copy; 2024 Harshitha</p>
    </footer>
</body>
</html>

style.css

/* Dessert Section Styles */
.menu-category {
    margin-top: 40px;
}

.menu-category h2 {
    font-size: 28px;
    text-align: center;
    margin-bottom: 20px;
    color: #333;
}

.dessert-item {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 20px 0;
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.dessert-image {
    width: 150px;
    height: 150px;
    border-radius: 10px;
    object-fit: cover;
    margin-right: 20px;
}

.dessert-details h3 {
    font-size: 24px;
    margin-bottom: 10px;
    color: #333;
}

.dessert-details p {
    font-size: 16px;
    color: #555;
    max-width: 300px;
    margin: 0;
}

.dessert-item:hover {
    background-color: #f8f8f8;
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.15);
}

## OUTPUT:
![alt text](<harshu/resapp/static/Screenshot (93).png>)
![alt text](<harshu/resapp/static/Screenshot (94).png>)
![alt text](<harshu/resapp/static/Screenshot (95).png>)
![alt text](<harshu/resapp/static/Screenshot (96).png>)
![alt text](<harshu/resapp/static/Screenshot (97).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
