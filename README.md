# Project Responsive Web Design using Bootstrap
## Date:21-05-25

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
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons/font/bootstrap-icons.css" rel="stylesheet">
  <style>
    body {
      background-color: #f8f9fa;
    }
    .card {
      transition: all 0.3s ease;
      border: none;
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
    }
    .card-img-top {
      height: 200px;
      object-fit: cover;
    }
    .meta {
      font-size: 0.9rem;
      color: #6c757d;
    }
    .card-title {
      font-weight: 600;
    }
  </style>
</head>
<body>
<nav class="navbar navbar-expand-lg navbar-light bg-white border-bottom shadow-sm">
  <div class="container">
    <a class="navbar-brand fw-bold text-dark" href="#">dribbble</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item"><a class="nav-link active" href="#">Shots</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Teams</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Community</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
      </ul>
      <form class="d-flex me-3" role="search">
        <input class="form-control me-2" type="search" placeholder="Search">
      </form>
      <a href="#" class="btn btn-outline-dark me-2">Sign In</a>
      <a href="#" class="btn btn-primary">Sign Up</a>
    </div>
  </div>
</nav>
<div class="container py-5">
  <div class="row g-4">
<div class="container py-5">
  <div class="row g-4">
    <div class="col-sm-6 col-md-4 col-lg-3">
      <div class="card">
        <img src="4.webp" class="card-img-top" alt="Design Shot">
        <div class="card-body">
          <h6 class="card-title">Famous</h6>
          <p class="meta">
            <i class="bi bi-eye"></i> 4044 &nbsp;
            <i class="bi bi-chat-dots"></i> 14 &nbsp;
            <i class="bi bi-heart-fill text-danger"></i> 290
          </p>
        </div>
      </div>
    </div>

    <div class="col-sm-6 col-md-4 col-lg-3">
      <div class="card">
        <img src="images.jpg" class="card-img-top" alt="Design Shot">
        <div class="card-body">
          <h6 class="card-title">Jan Losert</h6>
          <p class="meta">
            <i class="bi bi-eye"></i> 3985 &nbsp;
            <i class="bi bi-chat-dots"></i> 17 &nbsp;
            <i class="bi bi-heart-fill text-danger"></i> 264
          </p>
        </div>
      </div>
    </div>
    <div class="col-sm-6 col-md-4 col-lg-3">
      <div class="card">
        <img src="images (1).jpg" class="card-img-top" alt="Design Shot">
        <div class="card-body">
          <h6 class="card-title">Mattias Johansson</h6>
          <p class="meta">
            <i class="bi bi-eye"></i> 2602 &nbsp;
            <i class="bi bi-chat-dots"></i> 23 &nbsp;
            <i class="bi bi-heart-fill text-danger"></i> 186
          </p>
        </div>
      </div>
    </div>
    <div class="col-sm-6 col-md-4 col-lg-3">
      <div class="card">
        <img src="images (2).jpg" class="card-img-top" alt="Design Shot">
        <div class="card-body">
          <h6 class="card-title">Ruslan Siiz</h6>
          <p class="meta">
            <i class="bi bi-eye"></i> 2369 &nbsp;
            <i class="bi bi-chat-dots"></i> 8 &nbsp;
            <i class="bi bi-heart-fill text-danger"></i> 178
          </p>
        </div>
      </div>
    </div>
    <div class="col-sm-6 col-md-4 col-lg-3">
      <div class="card">
        <img src="hero-guy-3.png" class="card-img-top" alt="Design Shot">
        <div class="card-body">
          <h6 class="card-title">Paperpillar</h6>
          <p class="meta">
            <i class="bi bi-eye"></i> 2025 &nbsp;
            <i class="bi bi-chat-dots"></i> 6 &nbsp;
            <i class="bi bi-heart-fill text-danger"></i> 160
          </p>
        </div>
      </div>
    </div>
    <div class="col-sm-6 col-md-4 col-lg-3">
      <div class="card">
        <img src="design-studio-jq-feature.jpg" class="card-img-top" alt="Design Shot">
        <div class="card-body">
          <h6 class="card-title">Studio JQ</h6>
          <p class="meta">
            <i class="bi bi-eye"></i> 2179 &nbsp;
            <i class="bi bi-chat-dots"></i> 4 &nbsp;
            <i class="bi bi-heart-fill text-danger"></i> 158
          </p>
        </div>
      </div>
    </div>
    <div class="col-sm-6 col-md-4 col-lg-3">
      <div class="card">
        <img src="images (3).jpg" class="card-img-top" alt="Design Shot">
        <div class="card-body">
          <h6 class="card-title">Romain Trystram</h6>
          <p class="meta">
            <i class="bi bi-eye"></i> 1872 &nbsp;
            <i class="bi bi-chat-dots"></i> 8 &nbsp;
            <i class="bi bi-heart-fill text-danger"></i> 148
          </p>
        </div>
      </div>
    </div>
    <div class="col-sm-6 col-md-4 col-lg-3">
      <div class="card">
        <img src="cd8bc81847e77dd8756693d9702159a9.jpg"card-body">
          <h6 class="card-title">rainbow</h6>
          <p class="meta">
            <i class="bi bi-eye"></i> 2167 &nbsp;
            <i class="bi bi-chat-dots"></i> 9 &nbsp;
            <i class="bi bi-heart-fill text-danger"></i> 134
          </p>
        </div>
      </div>
    </div>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

  </div>
</div>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:
![alt text](image.png)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
