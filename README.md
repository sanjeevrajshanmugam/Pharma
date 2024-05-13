# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


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
home.html

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HOME</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      background-image: url("back.webp");
      background-size: cover;
      background-repeat: no-repeat;
      font-size: 19px;
    }
    footer{
      position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: hsl(176, 70%, 44%); 
      color: white;
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <a class="navbar-brand" href="#">AI PHARMACEUTICALS</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="home.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>WELCOME TO AI PHARMACEUTICAL</h1>
        <p>Welcome to AI Pharmaceuticals.We provide you the best quality of Medicines.Customers well being is what we wish always.</p>
        <p>At Our Pharmaceuticals, we provide you all kind of medicines.</p>
        <p>Thank you for choosing and trusting AI Pharmaceuticals.</p>
      </div>
      <div class="col-md-5">
        <img src="tb.jpg" class="img-fluid" alt="Pharmacy Image" width="2000" height="2000">
      </div>
      <div class="col-md-4">
        <img src="tt.avif" class="img-fluid" alt="Pharmacy Image" width="2000" height="2000">
      </div>
       
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 PharmaCompany - VARSHA A(212223220121). All rights reserved.</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```


## OUTPUT:

![image](https://github.com/sanjeevrajshanmugam/Pharma/assets/151383137/2380adac-db38-4d0e-93d1-4596dbebc6bd)

![image](https://github.com/sanjeevrajshanmugam/Pharma/assets/151383137/460ee007-49cd-446f-8c9a-2700176b5160)

![image](https://github.com/sanjeevrajshanmugam/Pharma/assets/151383137/1b50263a-6e2a-429d-b53e-bb74339dad84)

![image](https://github.com/sanjeevrajshanmugam/Pharma/assets/151383137/e2aeefa4-f232-4d01-8fcb-ce3f493d2a60)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
