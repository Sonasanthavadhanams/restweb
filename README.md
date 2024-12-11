# Ex.07 Restaurant Website
## Date:11/12/2024

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
food.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Film Restaurant </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #6b3fa0;
            color: white;
            padding: 15px;
            text-align: center;
        }

        header h1 {
            font-weight: 400;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
        }

        header nav ul li a:hover {
            color: rgb(251, 150, 110);
            font-weight: bold;
        }

        .container {
            width: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-around;
        }

        h2 {
            color: #6b3fa0;
        }

        .menu-item {
            background-color: #fff;
            margin: 10px 0;
            padding: 15px;
            border-radius: 8px;
            display: flex;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .menu-item img {
            border-radius: 8px;
            margin-right: 15px;
            width: 100px;
            height: auto;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 5px 0;
        }

        ::-webkit-scrollbar {
            width: 0px;
        }
    </style>
</head>

<body>
    <header>
        <h1> FILM RESTAURANT </h1>
        <nav>
            <ul>
                <li><a href="food.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="container">
        <h2>Welcome to Our Restaurant</h2>
        <p>Experience the finest dining with us. Enjoy our delicious menu, excellent service, and a cozy atmosphere.</p>
        <img src="banner.jpg" alt="Restaurant Banner" style="width: 30%; border-radius: 10px;">
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 FLIM Restaurant | Designed by SONA.S (24900459)</p>
        </div>
    </footer>
</body>

</html>

menu.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - FLIM Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f6f1;
            color: #333;
        }

        header {
            background-color: #6b3fa0;
            color: white;
            padding: 15px;
            text-align: center;
        }

        header h1 {
            font-weight: 400;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
            padding: 3px;
        }

        header nav ul li a:hover {
            color: rgb(251, 150, 110);
            font-weight: bold;
        }

        .menu-container {
            width: 80%;
            margin: 20px auto 70px auto;
            display: flex;
            justify-content: space-around;
            flex-wrap:wrap;
            overflow: scroll;
        }

        .menu-item {
            width: 30%;
            display: flex;
            align-items: center;
            margin-bottom: 20px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 8px;
            background-color: #fff;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .menu-item img {
            width: 100px;
            height: 100px;
            border-radius: 8px;
            margin-right: 15px;
        }

        .menu-item h3 {
            margin: 0;
            font-size: 1.2em;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 5px 0;
        }

        ::-webkit-scrollbar {
            width: 0px;
        }
    </style>
</head>

<body>
    <header>
        <h1>OUR MENU</h1>
        <nav>
            <ul>
                <li><a href="food.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <div class="menu-container">
        <div class="menu-item">
            <img src="biryani.jpg" alt="biryani">
            <div>
                <h3>biryani</h3>
                <p>A vibrant rice dish with mixed vegetables, chicken or mutton, and an egg.</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="non-veg_Meals.jpg" alt="NON VEG MEALS">
            <div>
                <h3>NON VEG MEALS</h3>
                <p>Rice with chicken,mutton,fish gravy with rotti and chicken starters</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="naan.jpg" alt="Naan">
            <div>
                <h3>BUTTER NAAN</h3>
                <p>Soft and fluffy </p>
            </div>
        </div>
        <div class="menu-item">
            <img src="chicken 65.jpg" alt="chicken65">
            <div>
                <h3>CHICKEN 65</h3>
                <p>fresh chicken fried with indian masala </p>
            </div>
        </div>
        <div class="menu-item">
            <img src="chicken lollipop.jpg" alt="chickenlollipop">
            <div>
                <h3>CHICKEN LOLLIPOP</h3>
                <p>Fresh chicken mixed with korean sauce</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="butterchicken.jpg" alt="butterchicken">
            <div>
                <h3>BUTTER CHICKEN</h3>
                <p> Flavor full chicken rich in butter</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="mutton gravy.avif" alt="mutton">
            <div>
                <h3>MUTTON GRAVY</h3>
                <p>Mutton with brust of Indian masala</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="prawnthokku.webp" alt="prawnthokku">
            <div>
                <h3>PRAWNTHOKKU</h3>
                <p>Prawn mix of Flavor of India</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="crabsoup.avif" alt="crabsoup">
            <div>
                <h3>CARBSOUP</h3>
                <p>Start with Refreshing crabsoup</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="attukalsoup.webp" alt="attukalsoup">
            <div>
                <h3>ATTUKAL SOUP</h3>
                <p>Make your taste buds dance by having our attukal soup</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="Elaneer-Payasam.jpg" alt="">
            <div>
                <h3>ELANEER PAYASAM</h3>
                <p>After some heavy load taste our Elaneer-Payasam for satisfaction for complete meal</p>
            </div>
        </div>
        <div class="menu-item">
            <img src="jigarthanda.jpg" alt="jigarthanda">
            <div>
                <h3>JIGARTHANDA</h3>
                <p>After some heavy load taste our jigarthanda for satisfaction for complete meal</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Designed by SONA.S (24900459)</p>
    </footer>
</body>

</html>

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - FLIM Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }

        header {
            background-color: #3f51b5;
            color: white;
            padding: 15px;
            text-align: center;
        }

        header h1 {
            font-weight: 400;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
        }

        header nav ul li a:hover {
            color: rgb(251, 150, 110);
            font-weight: bold;
        }

        .admin-container {
            width: 80%;
            margin: 20px auto;
            text-align: center;
        }

        .admin-card {
            display: inline-block;
            width: 200px;
            margin: 15px;
            padding: 15px;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .admin-card img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 5px 0;
        }

        ::-webkit-scrollbar {
            width: 0px;
        }
    </style>
</head>
<body>
<header>
    <h1>ADMINISTRATION TEAM</h1>
    <nav>
        <ul>
            <li><a href="food.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="administration.html">Administration</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
    </nav>
</header>

<div class="admin-container">
    <div class="admin-card">
        <img src="director.jpg" alt="Dirtector">
        <h3>DR.KAMAL HAASAN</h3>
        <p>Restaurant Dirtector</p>
    </div>
    <div class="admin-card">
        <img src="chef.jpg" alt="Chef">
        <h3> JOESPH VIJAY </h3>
        <p>Head Chef</p>
    </div>
    <div class="admin-card">
        <img src="souschef.jpg" alt="Sous Chef">
        <h3>SHAH RUKH KHAN </h3>
        <p>Sous Chef</p>
    </div>
    <div class="admin-card">
        <img src="waiter.jpg" alt="Waiter">
        <h3>VIJAY SETHUPATHI</h3>
        <p>Senior Waiter</p>
    </div>
    <div class="admin-card">
        <img src="bartender.jpg" alt="Bartender">
        <h3>VIJAY DEVERAKONDA</h3>
        <p>Bartender</p>
    </div>
    <div class="admin-card">
        <img src="receptionist.jpg" alt="Receptionist">
        <h3>SAMANTHA</h3>
        <p>Receptionist</p>
    </div>
</div>

<footer>
    <p>&copy; 2024 Designed by SONA.S (24900459)</p>
</footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - FLIM Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #eaeaea;
            color: #333;
        }

        header {
            background-color: #6b3fa0;
            color: white;
            padding: 15px;
            text-align: center;
        }

        header h1 {
            font-weight: 400;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
        }

        header nav ul li a:hover {
            color: rgb(251, 150, 110);
            font-weight: bold;
        }

        .contact-container {
            width: 60%;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .contact-container h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        .contact-item {
            margin-bottom: 15px;
        }

        .contact-item label {
            font-weight: bold;
        }

        .contact-item p {
            margin: 5px 0;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 5px 0;
        }

        ::-webkit-scrollbar {
            width: 0px;
        }
    </style>
</head>
<body>
<header>
    <h1>CONTACT US</h1>
    <nav>
        <ul>
            <li><a href="food.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="administration.html">Administration</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
    </nav>
</header>

<div class="contact-container">
    <h2>Get in Touch</h2>
    <div class="contact-item">
        <label>Email:</label>
        <p>info@flimnrestaurant.com</p>
    </div>
    <div class="contact-item">
        <label>Phone:</label>
        <p>+9542638712</p>
    </div>
    <div class="contact-item">
        <label>Address:</label>
        <p>123 Main Street,flim City, Chennai, Tamilnadu</p>
    </div>
</div>

<footer>
    <p>&copy; 2024 Designed by SONA .S (24900459)</p>
</footer>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot (63)-1.png>)
![alt text](<Screenshot (64)-1.png>)
![alt text](<Screenshot (65).png>)
![alt text](<Screenshot (66).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
