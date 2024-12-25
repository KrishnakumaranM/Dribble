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
  <title>Inspiration Hub</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body class="bg-dark text-white">

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand fw-bold" href="#">Inspiration Hub</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link text-light" href="#explore">Explore</a></li>
          <li class="nav-item"><a class="nav-link text-light" href="#creativity">Creativity</a></li>
          <li class="nav-item"><a class="nav-link text-light" href="#ideas">Ideas</a></li>
          <li class="nav-item"><a class="nav-link text-light" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Main Content -->
  <div class="container py-5">
    <h2 class="text-center text-light fw-bold mb-4" id="explore">Explore Your Next Inspiration</h2>
    <p class="text-center text-secondary">Discover amazing ideas and projects that combine technology and creativity to inspire you every day.</p>

    <div class="row gy-4">

      <!-- Card 1 -->
      <div class="col-md-4">
        <div class="card bg-secondary text-white shadow-sm">
          <img src="naturephotography.jpeg" class="card-img-top" alt="Nature Photography">
          <div class="card-body">
            <h5 class="card-title">Nature Photography</h5>
            <p class="card-text">Immerse yourself in breathtaking landscapes and wildlife captured beautifully.</p>
            <div class="d-flex justify-content-between small">
              <span>7,000 views</span>
              <span>500 likes</span>
            </div>
          </div>
        </div>
      </div>

      <!-- Card 2 -->
      <div class="col-md-4">
        <div class="card bg-secondary text-white shadow-sm">
          <img src="Harmony in Progress_ A Vision of an Eco-Friendly Future.jpeg" class="card-img-top" alt="Futuristic Architecture">
          <div class="card-body">
            <h5 class="card-title">Futuristic Architecture</h5>
            <p class="card-text">Explore bold designs and structures that define the future of living.</p>
            <div class="d-flex justify-content-between small">
              <span>6,200 views</span>
              <span>420 likes</span>
            </div>
          </div>
        </div>
      </div>

      <!-- Card 3 -->
      <div class="col-md-4">
        <div class="card bg-secondary text-white shadow-sm">
          <img src="Space Travel Phone Wallpaper - Digitally Created Art.jpeg" class="card-img-top" alt="Digital Art">
          <div class="card-body">
            <h5 class="card-title">Digital Art</h5>
            <p class="card-text">Dive into colorful and abstract creations crafted by digital artists worldwide.</p>
            <div class="d-flex justify-content-between small">
              <span>5,800 views</span>
              <span>380 likes</span>
            </div>
          </div>
        </div>
      </div>

      <!-- Card 4 -->
      <div class="col-md-4">
        <div class="card bg-secondary text-white shadow-sm">
          <img src="Artificial Gravity Experiment in Orbit _ Space Experiment in Orbit _ Fact Blizz.jpeg" class="card-img-top" alt="Space Exploration">
          <div class="card-body">
            <h5 class="card-title">Space Exploration</h5>
            <p class="card-text">Uncover new horizons with the latest advancements in space technology.</p>
            <div class="d-flex justify-content-between small">
              <span>5,200 views</span>
              <span>320 likes</span>
            </div>
          </div>
        </div>
      </div>

      <!-- Card 5 -->
      <div class="col-md-4">
        <div class="card bg-secondary text-white shadow-sm">
          <img src="17 Luxe Home Office Ideas That Exude Elegance.jpeg" class="card-img-top" alt="Creative Workspaces">
          <div class="card-body">
            <h5 class="card-title">Creative Workspaces</h5>
            <p class="card-text">Discover beautifully designed spaces that enhance productivity and creativity.</p>
            <div class="d-flex justify-content-between small">
              <span>4,900 views</span>
              <span>300 likes</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-center text-light py-4">
    <p>&copy; 2024 Inspiration Hub. All Rights Reserved.</p>
    <p>
      <a href="#" class="text-white text-decoration-none">Privacy Policy</a> | 
      <a href="#" class="text-white text-decoration-none">Terms of Service</a>
    </p>
    <p>Follow us on 
      <a href="#" class="text-white text-decoration-none">Twitter</a>, 
      <a href="#" class="text-white text-decoration-none">LinkedIn</a>, and 
      <a href="#" class="text-white text-decoration-none">Instagram</a>.
    </p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>

```


## OUTPUT:
![Screenshot (57)](https://github.com/user-attachments/assets/d93f1ce8-5714-46f8-8851-b73d651f8212)
![Screenshot (58)](https://github.com/user-attachments/assets/c6826472-22b6-4bc4-8ee6-84f5acdf64ee)
![Screenshot (59)](https://github.com/user-attachments/assets/9b66e297-d3dd-4a76-9b1a-0a630e03e779)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
