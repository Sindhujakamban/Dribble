# Project Responsive Web Design using Bootstrap
## Date: 04/01/2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">Dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#gallery">Gallery</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">login</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <header class="bg-secondary text-white text-center py-5">
    <div class="container">
      <h1>Welcome to Dribble </h1>
      <p class="lead">WHAT ARE YOU GOING TO CHOOSE!!!</p>
      <a href="#gallery" class="btn btn-light btn-lg">Explore Now</a>
    </div>
  </header>

  <section id="gallery" class="bg-light py-5">
    <div class="container text-center">
      <div class="row g-4">
        <div class="col-md-4 col-sm-6">
          <div class="card">
            <img src="project img 2.jpg" class="card-img-top" alt="Freedom Rider" height="200">
            <div class="card-body">
              <h6 class="card-title"><b>AIRPODS</b></h6>
            </div>
          </div>
        </div>
        <div class="col-md-4 col-sm-6">
          <div class="card">
            <img src="project img 3.png" class="card-img-top" alt="Pathway to Connection" height="200">
            <div class="card-body">
              <h6 class="card-title"><b>PERFUMES</b></h6>
            </div>
          </div>
        </div> 
        <div class="col-md-4 col-sm-6">
          <div class="card">
            <img src="project img 4.jpg" class="card-img-top" alt="Timeless Grooves" height="200">
            <div class="card-body">
              <h6 class="card-title"><b>TENNIS BATS</b></h6>
            </div>
          </div>
        </div>

        <!-- Second Row -->
        <div class="col-md-4 col-sm-6">
          <div class="card">
            <img src="project img 7.jpg" class="card-img-top" alt="Cityscape"  height="200">
            <div class="card-body">
              <h6 class="card-title"><b>NECKLACE</b></h6>
            </div>
          </div>
        </div>
        <div class="col-md-4 col-sm-6">
          <div class="card">
            <img src="project img 8.jpg" class="card-img-top" alt="Nature Bliss" height="200">
            <div class="card-body">
              <h6 class="card-title"><b>BANGLES</b></h6>
            </div>
          </div>
        </div>
        <div class="col-md-4 col-sm-6">
          <div class="card">
            <img src="project img 1.jpg" class="card-img-top" alt="Mountain Adventure"height="200">
            <div class="card-body">
              <h6 class="card-title"><b>SHOES</b></h6>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <div class="container">
      <p>&copy; 2024 Designed by SINDUJA K</p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
```


## OUTPUT:
![alt text](<Screenshot (79).png>) 
![alt text](<Screenshot (78).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
