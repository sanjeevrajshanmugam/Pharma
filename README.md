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

https://private-user-images.githubusercontent.com/149035374/329764221-3abd0773-579d-4710-a5e6-9711dc966c39.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTU2MDMyNTksIm5iZiI6MTcxNTYwMjk1OSwicGF0aCI6Ii8xNDkwMzUzNzQvMzI5NzY0MjIxLTNhYmQwNzczLTU3OWQtNDcxMC1hNWU2LTk3MTFkYzk2NmMzOS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTEzJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUxM1QxMjIyMzlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00NGY5Zjg4ODllMDNlNTI0YzZhZDBjMDE1ODk0M2ZlODI2YjFhMDllODlkNzZlOGIwZDIwZGQ2MjhiMTlhYTBkJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.aDEAJj6P0MiuSmI9r6Q2zJw4EO7U_3S6Q9-BpjT3ezY

https://private-user-images.githubusercontent.com/149035374/329764476-6e79aecf-8d13-447c-ba48-8f1448e46d59.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTU2MDMyNTksIm5iZiI6MTcxNTYwMjk1OSwicGF0aCI6Ii8xNDkwMzUzNzQvMzI5NzY0NDc2LTZlNzlhZWNmLThkMTMtNDQ3Yy1iYTQ4LThmMTQ0OGU0NmQ1OS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTEzJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUxM1QxMjIyMzlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xZTUzNDk3ZDYzODIwNzA4N2E3NzNkMjcxMTIzNmFjYzE5YTNmZjRlNGE3MzcwYjIzN2JjMGQ3MTBhMjFiNDBhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.3c7LmT63dtAk-jWpOgjUejFiGzxJ7Vqpe1oL6HIBZUY

https://private-user-images.githubusercontent.com/149035374/329764515-1b44e83e-57b4-4809-a804-2bec282f3c1e.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTU2MDMyNTksIm5iZiI6MTcxNTYwMjk1OSwicGF0aCI6Ii8xNDkwMzUzNzQvMzI5NzY0NTE1LTFiNDRlODNlLTU3YjQtNDgwOS1hODA0LTJiZWMyODJmM2MxZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTEzJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUxM1QxMjIyMzlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT05ZWRlOWE0ODQ3OWRlZTg1ZWM0YzE2NmRkYmZkOTZmODdmNjQwYzY3NDQ0NTI1ZjhjYjViOGEwZmI0MmVhNGE1JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.p_0Psgpc_yDRVWjkhaZm5UQtocalVQBE-ReDTa1NUjI

https://private-user-images.githubusercontent.com/149035374/329764536-fd2df671-467e-444c-aba9-a7f41128e842.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTU2MDMyNTksIm5iZiI6MTcxNTYwMjk1OSwicGF0aCI6Ii8xNDkwMzUzNzQvMzI5NzY0NTM2LWZkMmRmNjcxLTQ2N2UtNDQ0Yy1hYmE5LWE3ZjQxMTI4ZTg0Mi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTEzJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUxM1QxMjIyMzlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00YWM5OTY5ODRiNzliZTVkZTE2ZTAwYmQzMDI5OGRlMGYyZTE4YWNmYjllOGMwNTlkNDRhYjI2ZGY4NzBlMTc4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.A_R5DbNlv-iXvNCuhmlIW8Oms_43MV5NX7rDxOyPD9I

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
