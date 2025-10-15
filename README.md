# Project Responsive Web Design using Bootstrap
## Date:15.10.2025

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
~~~
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dribbble Clone</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navigation -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light shadow-sm">
    <div class="container">
      <a class="navbar-brand fw-bold text-danger" href="#">Dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#">Inspiration</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Find Work</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Learn Design</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Go Pro</a></li>
          <li class="nav-item"><a class="btn btn-outline-danger ms-2" href="#">Sign Up</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="bg-danger text-white text-center py-5">
    <div class="container">
      <h1 class="display-4 fw-bold">Discover the world’s top designers & creatives</h1>
      <p class="lead mt-3">
        Dribbble is the leading destination to find & showcase creative work and home to the world’s best design professionals.
      </p>
      <a href="#" class="btn btn-light btn-lg mt-4">Get Started</a>
    </div>
  </section>

  <!-- Featured Shots -->
<section class="py-5">
  <div class="container">
    <h2 class="text-center mb-5">Explore Shots</h2>
    <div class="row g-4">
      <div class="col-md-4 col-sm-6">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1581091215360-32d0f13f3b39?auto=format&fit=crop&w=400&h=300&q=80" class="card-img-top" alt="Shot 1">
          <div class="card-body">
            <h5 class="card-title">Creative UI Design</h5>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1581091215370-24c1e7db6f4f?auto=format&fit=crop&w=400&h=300&q=80" class="card-img-top" alt="Shot 2">
          <div class="card-body">
            <h5 class="card-title">Mobile App Concept</h5>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1581091215380-32a0d1b0f2f0?auto=format&fit=crop&w=400&h=300&q=80" class="card-img-top" alt="Shot 3">
          <div class="card-body">
            <h5 class="card-title">E-commerce Landing Page</h5>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
  <!-- Footer -->
  <footer class="bg-light text-center py-3">
    <div class="container">
      <p class="mb-0">© 2025 Dribbble Clone. Made with ❤ using Bootstrap.</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
~~~

## OUTPUT:
![alt text](<Screenshot 2025-10-08 161717.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
