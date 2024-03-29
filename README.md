# EX01 Developing a Simple Webserver
## Date:

## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<div style="display: flex;margin: tempx;"> <div class="card" style="width: 18rem;">
    <img src="gt 1.jpg">
    <div class="card-body">
      <h5 class="card-title">Royal Enfield GT</h5>
      <p class="card-text">Royal enfield prices are on high road market.</p>
      <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
  </div>
  <div class="card" style="width: 18rem;margin: tempx;">
    <img src="nayantra.jpg">
    <div class="card-body">
      <h5 class="card-title">Nayantra's Divorce</h5>
      <p class="card-text">Rumors about that nayantra is going to divorce vighnesh shivan.</p>
      <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
  </div></div>
  

<body>
    <div id="carouselExampleIndicators" class="carousel slide">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
          <img src="Porshe1.jpg"class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item active">
          <img src="Porshe2.jpg"class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item active">
          <img src="porsche3.jpg"class="d-block w-100" alt="...">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
      </div>
</body>
</html>


## OUTPUT:![Screenshot 1](https://github.com/JayaAbirami/simplewebserver/assets/151487010/efa66cc8-2225-4c53-bba4-4235044fe94d)



## RESULT:
The program for implementing simple webserver is executed successfully.
