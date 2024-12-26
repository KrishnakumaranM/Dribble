# Project Responsive Web Design using Bootstrap
## Date:24/12/24

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
image.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Creative Portfolio</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-primary">
    <div class="container">
      <a class="navbar-brand text-white" href="#">CreativePortfolio</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav me-auto">
          <li class="nav-item"><a class="nav-link text-white" href="#projects">Projects</a></li>
          <li class="nav-item"><a class="nav-link text-white" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link text-white" href="#contact">Contact</a></li>
        </ul>
        <!-- Search Bar -->
        <form class="d-flex me-3" role="search">
          <input class="form-control me-2" type="search" placeholder="Search Projects" aria-label="Search">
          <button class="btn btn-outline-light" type="submit">Search</button>
        </form>
        <!-- Buttons in Header -->
        <a href="#login" class="btn btn-outline-light me-2">Login</a>
        <a href="#services" class="btn btn-outline-light me-2">Services</a>
        <a href="#signup" class="btn btn-light">Sign Up</a>
      </div>
    </div>
  </nav>

  <!-- Main Section -->
  <div class="container py-5">
    <h1 class="text-center mb-4">Explore Our Creative Projects</h1>
    <p class="text-center mb-5">Discover a collection of unique and innovative projects that showcase creativity and design excellence. From graphic design to UI/UX, we’ve got something to inspire you.</p>
    
    <!-- Project Grid Section -->
    <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 g-4">
      <!-- Card 1 -->
      <div class="col">
        <div class="card">
          <img src="Modern Web Design.jpeg" class="card-img-top" alt="Web Design">
          <div class="card-body">
            <h5 class="card-title">Modern Web Design</h5>
            <p class="card-text">A clean, responsive design for a professional website.</p>
          </div>
        </div>
      </div>
      <!-- Card 2 -->
      <div class="col">
        <div class="card">
          <img src="Mobile App UI.jpeg" class="card-img-top" alt="Mobile App">
          <div class="card-body">
            <h5 class="card-title">Mobile App UI</h5>
            <p class="card-text">A sleek and user-friendly interface for a mobile app.</p>
          </div>
        </div>
      </div>
      <!-- Card 3 -->
      <div class="col">
        <div class="card">
          <img src="Brand Identity.jpeg" class="card-img-top" alt="Branding">
          <div class="card-body">
            <h5 class="card-title">Brand Identity</h5>
            <p class="card-text">A unique logo and branding package for a startup.</p>
          </div>
        </div>
      </div>
      <!-- Card 4 -->
      <div class="col">
        <div class="card">
          <img src="Custom Illustrations.jpeg" class="card-img-top" alt="Illustrations">
          <div class="card-body">
            <h5 class="card-title">Custom Illustrations</h5>
            <p class="card-text">Creative artwork for digital and print media.</p>
          </div>
        </div>
      </div>
      <!-- Card 5 -->
      <div class="col">
        <div class="card">
          <img src="Social Media Graphics.jpeg" class="card-img-top" alt="Social Media">
          <div class="card-body">
            <h5 class="card-title">Social Media Graphics</h5>
            <p class="card-text">Engaging visuals for online campaigns and posts.</p>
          </div>
        </div>
      </div>
      <!-- Card 6 -->
      <div class="col">
        <div class="card">
          <img src="Motion Graphics.jpeg" class="card-img-top" alt="Animation">
          <div class="card-body">
            <h5 class="card-title">Motion Graphics</h5>
            <p class="card-text">Dynamic and captivating animations for videos.</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-primary text-white text-center py-3">
    <p class="mb-0">© 2024 CreativePortfolio. Designed and developed by M krihna kumaran</p>
    <p>Follow us on <a href="#" class="text-white">Twitter</a>, <a href="#" class="text-white">LinkedIn</a>, and <a href="#" class="text-white">Instagram</a>.</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
## OUTPUT:
![Screenshot (60)](https://github.com/user-attachments/assets/af2172e5-7849-4e13-a05b-47bcdd6c1bee)
![Screenshot (61)](https://github.com/user-attachments/assets/da269235-c737-4e7d-a461-5aa114951598)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
