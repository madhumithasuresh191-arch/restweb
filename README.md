# Ex.07 Restaurant Website
## Date:19-12-2025
## Ref no: 25014660

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
~~~
home.html

<!DOCTYPE html>
<html>
<head>
    <title>Leafora</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
<header>
    <h1>Royal Rasoi Restaurant</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Welcome to Royal Rasoi Restaurant</h2>
    <p>Fresh vegetarian flavors, modern dining experience, and cozy vibes.</p>
</section>

</body>
</html>

menu.html

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Leafora Veg - Menu</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
<header>
    <h1>Royal Rasoi Restaurant</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Our Vegetarian Menu</h2>
    <div class="menu-grid">
        <div class="card"><img src="paneer.jpg"><p>Paneer Butter Masala - ₹250</p></div>
        <div class="card"><img src="naan.jpg"><p>Naan - ₹15</p></div>
        <div class="card"><img src="friedrice.jpg"><p>Veg Friedrice - ₹180</p></div>
        <div class="card"><img src="noodles.jpg"><p>Mushroom Noodles - ₹150</p></div>
        <div class="card"><img src="tandoori.jpg"><p>Chicken tandoori - ₹200</p></div>
        <div class="card"><img src="biriyani.jpg"><p>Biryani - ₹170</p></div>
    </div>
</section>

</body>
</html>

index.css

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    background-color: #F2F8FF; /* light blue background */
    color: #0A2540; /* deep navy text */
}

/* Header */
header {
    background: linear-gradient(
        90deg,
        #cc059a,   /* dark pink */
        #eb63b2,   /* medium pink*/
        #e977ce    /* light pink */
    ); 
    color: #1a0101;
    padding: 22px;
    text-align: center;
    letter-spacing: 1px;
}

/* Navigation */
nav {
    background-color: #020b21; 
    text-align: center;
}

nav a {
    color: #ffffff;
    text-decoration: none;
    margin: 0 18px;
    padding: 10px;
    display: inline-block;
    font-weight: 600;
    transition: 0.3s ease;
}

nav a:hover {
    background-color: #4DA3FF; /* sky blue hover */
    color: #0A2540;
    border-radius: 6px;
}

/* Section */
section {
    padding: 40px;
    text-align: center;
}

/* Headings */
h2 {
    font-family: 'Courgette', cursive;
    color: #163A5F; /* rich blue */
    font-weight: 700;
    letter-spacing: 0.5px;
}

/* Grid Layout */
.menu-grid, .team-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
    max-width: 1000px;
    margin: 30px auto;
    text-align: center;
}

/* Cards */
.card {
    background-color: #f1f6f8;
    padding: 18px;
    border-radius: 14px;
    box-shadow: 0 9px 17px rgba(173, 5, 228, 0.12);
    color: #030357;
    font-weight: 600;
    border: 4px solid #1a32c7fc; 
    transition: transform 0.3s ease;
}

.card:hover {
    transform: translateY(-6px);
}

/* Images */
.card img {
    width: 90px;
    height: 110px;
    object-fit: cover;
    border-radius: 18px;
}

/* Footer */
footer {
    background-color: #0A2540;
    color: #ffffff;
    text-align: center;
    padding: 18px;
    font-size: 14px;
    letter-spacing: 0.5px;
}

/* Contact Section */
.contact-container {
    max-width: 800px;
    margin: 0 auto;
    text-align: left;
    padding: 25px;
    background-color: #ffffff;
    border-radius: 14px;
    box-shadow: 0 8px 18px rgba(0,0,0,0.12);
    border: 6px dashed #a50bd8; 
}


.contact-container h2 {
    text-align: center;
    color: #0A2540;
}

.contact-container p {
    font-size: 18px;
    margin: 12px 0;
    color: #163A5F;
}

.contact-container b {
    color: #0A2540;
}
.logo {
  border: 3px solid #0a0a0a00;
  padding: 15px;
  border-radius: 15px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.2);
}
~~~


## OUTPUT:
<img width="1916" height="1010" alt="Screenshot 2025-12-19 100336" src="https://github.com/user-attachments/assets/ba5a43ca-834b-4af3-ba02-cbbb93341516" />
<img width="1920" height="1080" alt="Screenshot 2025-12-19 110728" src="https://github.com/user-attachments/assets/d99ac06d-544f-4196-aa39-376b8697cc55" />
<img width="1918" height="1024" alt="Screenshot 2025-12-19 100418" src="https://github.com/user-attachments/assets/7bde3b64-2056-49ed-af21-25d511444fe5" />
<img width="1920" height="1080" alt="Screenshot 2025-12-19 100253" src="https://github.com/user-attachments/assets/296f6904-31dd-4847-a4cf-7d9872468fa0" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
