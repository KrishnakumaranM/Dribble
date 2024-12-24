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
  <title>Marvel Movies Homepage</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Arial', sans-serif;
      line-height: 1.6;
    }
    .navbar {
      background-color: #202020;
    }
    .hero {
      background: linear-gradient(135deg, #ff0000, #800000);
      padding: 7rem 1rem;
      color: white;
    }
    footer {
      background: linear-gradient(135deg, #101010, #202020);
      padding: 3rem 1rem;
      color: #ccc;
    }
    footer a {
      color: #ff0000;
      text-decoration: none;
    }
    footer a:hover {
      text-decoration: underline;
    }
    .section {
      padding: 4rem 1rem;
    }
    .movie-card img {
      border-radius: 0.5rem;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }
    .movie-card img:hover {
      transform: scale(1.05);
    }
    .movie-card p {
      font-weight: bold;
      margin-top: 0.5rem;
    }
    .hero-card {
      background-color: #101010;
      color: white;
      padding: 2rem;
      border-radius: 0.5rem;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }
    .hero-card:hover {
      background-color: #202020;
    }
    .join-form input, .join-form textarea {
      margin-bottom: 1rem;
    }
    .join-form button {
      background-color: #ff0000;
      color: white;
      border: none;
    }
    .join-form button:hover {
      background-color: #cc0000;
    }
  </style>
</head>
<body class="bg-light">

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark fixed-top">
    <div class="container-fluid">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#movies">Movies</a></li>
          <li class="nav-item"><a class="nav-link" href="#heroes">Heroes</a></li>
          <li class="nav-item"><a class="nav-link" href="#villains">Villains</a></li>
          <li class="nav-item"><a class="nav-link" href="#fan-club">Join the Fan Club</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <header id="home" class="text-center text-white hero">
    <h1>Step Into a Universe of Endless Adventures</h1>
    <p>Discover the legends, unravel the mysteries, and relive the battles that define Marvel’s legacy.</p>
  </header>

  <!-- Movies Section -->
  <section id="movies" class="section bg-white">
    <div class="container">
      <h2 class="text-danger text-center mb-4">Marvel's Greatest Movies</h2>
      <div class="row text-center">
        <div class="col-md-4 movie-card">
          <img src="ironman.jpeg" class="img-fluid" alt="Iron Man Movie Poster">
          <p>Iron Man</p>
        </div>
        <div class="col-md-4 movie-card">
          <img src="endgame.jpeg" class="img-fluid" alt="The Avengers Movie Poster">
          <p>The Avengers</p>
        </div>
        <div class="col-md-4 movie-card">
          <img src="blackpanter copy.jpeg" class="img-fluid" alt="Black Panther Movie Poster">
          <p>Black Panther</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Heroes Section -->
  <section id="heroes" class="section bg-light">
    <div class="container">
      <h2 class="text-danger text-center mb-4">Meet the Heroes</h2>
      <div class="row">
        <div class="col-md-4">
          <div class="hero-card text-center">
            <h3>Iron Man</h3>
            <p>Genius. Billionaire. Philanthropist.</p>
          </div>
        </div>
        <div class="col-md-4">
          <div class="hero-card text-center">
            <h3>Black Panther</h3>
            <p>Wakanda Forever!</p>
          </div>
        </div>
        <div class="col-md-4">
          <div class="hero-card text-center">
            <h3>Spider-Man</h3>
            <p>Friendly Neighborhood Hero.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Villains Section -->
  <section id="villains" class="section bg-dark text-white">
    <div class="container">
      <h2 class="text-danger text-center mb-4">Infamous Villains</h2>
      <div class="row">
        <div class="col-md-4">
          <div class="hero-card text-center">
            <h3>Thanos</h3>
            <p>The Mad Titan.</p>
          </div>
        </div>
        <div class="col-md-4">
          <div class="hero-card text-center">
            <h3>Loki</h3>
            <p>The God of Mischief.</p>
          </div>
        </div>
        <div class="col-md-4">
          <div class="hero-card text-center">
            <h3>Green Goblin</h3>
            <p>Spider-Man's Nemesis.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Join the Fan Club Section -->
  <section id="fan-club" class="section bg-white">
    <div class="container">
      <h2 class="text-danger text-center mb-4">Join the Fan Club</h2>
      <form class="join-form">
        <div class="mb-3">
          <label for="name" class="form-label">Name</label>
          <input type="text" class="form-control" id="name" placeholder="Enter your name">
        </div>
        <div class="mb-3">
          <label for="email" class="form-label">Email</label>
          <input type="email" class="form-control" id="email" placeholder="Enter your email">
        </div>
        <div class="mb-3">
          <label for="message" class="form-label">Message</label>
          <textarea class="form-control" id="message" rows="3" placeholder="Why do you love Marvel?"></textarea>
        </div>
        <button type="submit" class="btn">Join Now</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="text-white text-center">
    <p>&copy; 2024 Designed and Developed by M Krishna Kumaran</p>
    <p><a href="#" class="text-decoration-none">Privacy Policy</a> | <a href="#" class="text-decoration-none">Terms of Service</a></p>
    <p>Follow us on <a href="#">Twitter</a>, <a href="#">Facebook</a>, and <a href="#">Instagram</a></p>
  </footer>

  <!-- Back to Top Button -->
  <button id="backToTop" onclick="scrollToTop()">&uarr;</button>

  <script>
    // Smooth Scrolling
    document.querySelectorAll('.nav-link').forEach(anchor => {
      anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
          behavior: 'smooth'
        });
      });
    });

    // Show Back to Top Button
    const backToTop = document.getElementById('backToTop');
    window.addEventListener('scroll', () => {
      if (window.scrollY > 200) {
        backToTop.style.display = 'flex';
      } else {
        backToTop.style.display = 'none';
      }
    });

    // Scroll to Top Function
    function scrollToTop() {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    }
  </script>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```


## OUTPUT:
![Screenshot (53)](https://github.com/user-attachments/assets/63100416-d2ff-41c1-a69b-3ceacab9207a)
![Screenshot (54)](https://github.com/user-attachments/assets/4393e3ba-202e-43c4-96c5-94350542a419)
![Screenshot (55)](https://github.com/user-attachments/assets/1b598b27-0f86-4b57-90c7-426db104a714)





## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
