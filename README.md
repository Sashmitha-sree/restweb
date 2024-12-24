# Ex.07 Restaurant Website
## Date:

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
HOME PAGE CSS

body {
    background-color: beige;
    font-family: Arial, sans-serif;
}

.navbar {
    background-color: darkred;
}

.navbar-brand {
    font-family: 'Liam', sans-serif;
    color: white;
}

.navbar-nav .nav-link {
    color: white;
}

.navbar-nav .nav-link:hover {
    color: #f8f9fa;
}

.text-danger {
    color: red;
}

.text-center {
    text-align: center;
}

/* Card Styles */
.card {
    margin-bottom: 20px;
}

.card-img-top {
    width: 100%;
    height: auto;
}

.card-body {
    text-align: center;
}

/* Footer Styles */
footer {
    background-color: #f8f9fa;
    text-align: center;
    padding: 10px;
}

/* Background Image for the Container */
.container-background {
    background-image: url('images/your-background.jpg');
    background-size: cover;
    background-position: center;
    padding: 50px;
    color: white;
}

/* Administration Section */
.admin-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    text-align: center;
}

.admin-item img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
}

.admin-item p {
    margin-top: 10px;
}

/* Section Titles */
h2 {
    font-family: 'Liam', sans-serif;
    font-size: 1.5rem;
    text-align: center;
    margin-bottom: 20px;
}

h1 {
    font-family: 'Liam', sans-serif;
    font-size: 2rem;
    color: #dc3545;
}

HOME PAGE

<!DOCTYPE html>
<html lang="en">
<head>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Whimsical Fork</title>
    <!-- Link to the external CSS file -->
    <link href="styles.css" rel="stylesheet">
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<div class="row text-center">
    <div class="col">
        <br><br>
        <img src="images/screenshot.png" height="300" width="700" alt="Restaurant Image">
    </div>
</div>

<nav class="navbar navbar-expand-lg navbar-light">
    <div class="container-fluid">
        <a class="navbar-brand" href="homeweb.html">THE WHIMSICAL FORK</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav d-flex">
                <li class="nav-item">
                    <a class="nav-link" href="pharhome.html">HOME</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="boot2.html">MENU</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="about.html">ABOUT</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="service.html">SERVICE</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<div class="container">
    <div class="row">
        <div class="col-12">
            <br><br>
            <h1>Welcome to our restaurant</h1>
            <h2>MENU</h2>

            <div class="row">
                <!-- Menu Items -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="images/chapati.jpg" class="card-img-top" alt="Chapati">
                        <div class="card-body">
                            <h5 class="card-title">CHAPATI</h5>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="images/dosa.jpg" class="card-img-top" alt="Dosa">
                        <div class="card-body">
                            <h5 class="card-title">DOSA</h5>
                        </div>
                    </div>
                </div>
                <!-- More menu items... -->
            </div>
        </div>
    </div>

    <div class="container-background">
        <div id="administration" class="content">
            <h2>Administration</h2>
            <div class="admin-grid">
                <div class="admin-item">
                    <img src="images/ceo.jpg" alt="Sashmitha Sree">
                    <p>Sashmitha Sree</p>
                    <p>Chief Executive Officer</p>
                </div>
                <div class="admin-item">
                    <img src="images/coo.jpg" alt="Miss Grey">
                    <p>MISS GREY</p>
                    <p>Chief Operating Officer</p>
                </div>
                <div class="admin-item">
                    <img src="images/cfo.jpg" alt="Miss Snow">
                    <p>MISS SNOW</p>
                    <p>Chief Financial Officer</p>
                </div>
            </div>
        </div>

        <div id="contact" class="content">
            <h2>Contact Us</h2>
            <p>Address: EA Road, 9K colony, Tamil Nadu, Chennai</p>
            <p>Phone: 6958452614</p>
            <p>Email: thewhimsicalfork@gmail.com</p>
        </div>
    </div>
</div>

<footer class="bg-light text-center py-3">
    <p>Designed and Developed by SASHMITHA SREE K V</p>
</footer>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot (70).png>)
![alt text](<Screenshot (71).png>)
![alt text](<Screenshot (72).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
