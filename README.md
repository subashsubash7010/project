# Project Responsive Web Design using Bootstrap
# Date:16/12/2024
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home - Pharmaceutical Company</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">Pharmaceutical Company</a>
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
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Welcome to Pharmaceutical Company</h1>
        <p>Welcome to Pharmaceutical Company, your one-stop destination for all your pharmaceutical needs! We provide a wide range of high-quality medications, medical supplies, and healthcare products to ensure you and your loved ones stay healthy and happy. Our knowledgeable staff is here to assist you with any questions or concerns you may have. At Pharma Medicals, your well-being is our top priority.</p>
        <p>At Pharmaceutical Company, With a relentless focus on innovation and quality, we are at the forefront of cutting-edge medical advancements, ensuring that every product we create is a testament to our unwavering commitment to excellence..</p>
        <p>In addition to medications,Pharmaceutical Company are pivotal in creating and distributing drugs, vaccines, and medical devices to enhance human health. </p>
        <p>Thank you for choosing Pharmaceutical Company for your healthcare needs. We look forward to serving you and helping you live a healthier life.</p>
      </div>
      <div class="col-md-4">
        <img src="https://t4.ftcdn.net/jpg/08/44/82/55/360_F_844825587_MEoU8odal1uKKTjNOoFa0A4yLyZzJ0gG.jpg" class="img-fluid" alt="Pharmacy Image">
      </div>
    </div>
  </div>
  <body background="https://img.freepik.com/free-photo/medicine-capsules-global-health-with-geometric-pattern-digital-remix_53876-126742.jpg"
  <br>
  <br>
  <br>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 Pharmaceutical Company. All rights reserved. SUBASH M (212224220109)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="C:\Users\ms701\Downloads\phar.webp"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

about.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Pharmaceutical Company</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">Pharmaceutical Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>About Pharmaceutical Company</h1>
        <div id="vision">
          <h2>Vision</h2>
          <p>A pharmaceutical company might envision creating innovative medicines that improve and save lives, prioritizing research, development, and ethical distribution to enhance global health outcomes. They may strive for sustainability, diversity, and collaboration, aiming to be a leader in addressing healthcare challenges and fostering a healthier world.</p>
        </div>
        <div id="mission">
          <h2>Mission</h2>
          <p>Our mission is to We will discover, develop and successfully market pharmaceutical products to prevent, diagnose, alleviate and cure diseases.</p>
        </div>
        <div id="values">
          <h2>Values</h2>
          <ul>
            <li>Quality:From the very beginning, Quality has been the core of our existence. Unimarckens are persistently putting efforts in manufacturing high-quality products for society.</li>
            
            <li>Commitment to Excellence:We believe commitment drives the force for achieving excellence for products to stand at par in the pharmaceutical industry. We pursue </li>
            <li>Customer-oriented: Being a customer-oriented pharma company, the prospect is to digitalize the business by serving quality pharma products online.</li>
            <li>Teamwork: “Teamwork makes the dream work.”</li>
          </ul>
        </div>
        <br>
        <!-- Add more subheadings as needed -->
      </div>
    </div>
  </div>
  <body background="background2.webp" style="background-repeat: no-repeat; background-size: cover;"></body>
  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-3">
    <p>&copy; 2024 PharmaCompany. All rights reserved.  BY SUBASH M (212224220109)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="C:\Users\ms701\Downloads\phar.webp.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

about.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Pharmaceutical Company</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">Pharmaceutical Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>About Pharmaceutical Company</h1>
        <div id="vision">
          <h2>Vision</h2>
          <p>A pharmaceutical company might envision creating innovative medicines that improve and save lives, prioritizing research, development, and ethical distribution to enhance global health outcomes. They may strive for sustainability, diversity, and collaboration, aiming to be a leader in addressing healthcare challenges and fostering a healthier world.</p>
        </div>
        <div id="mission">
          <h2>Mission</h2>
          <p>Our mission is to We will discover, develop and successfully market pharmaceutical products to prevent, diagnose, alleviate and cure diseases.</p>
        </div>
        <div id="values">
          <h2>Values</h2>
          <ul>
            <li>Quality:From the very beginning, Quality has been the core of our existence. Unimarckens are persistently putting efforts in manufacturing high-quality products for society.</li>
            
            <li>Commitment to Excellence:We believe commitment drives the force for achieving excellence for products to stand at par in the pharmaceutical industry. We pursue </li>
            <li>Customer-oriented: Being a customer-oriented pharma company, the prospect is to digitalize the business by serving quality pharma products online.</li>
            <li>Teamwork: “Teamwork makes the dream work.”</li>
          </ul>
        </div>
        <br>
        <!-- Add more subheadings as needed -->
      </div>
    </div>
  </div>
  <body background="https://www.sssutms.ac.in/static/media/FOP.cf2081b9c535f60cf1bc.jpg"
  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-3">
    <p>&copy; 2024 PharmaCompany. All rights reserved.  BY SUBASH M (212224220109)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

product.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products - PharmaCompany</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">Pharmaceutical Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Products
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="#">Over-the-counter (OTC) Medications</a>
            <a class="dropdown-item" href="#">Prescription Drugs</a>
            <a class="dropdown-item" href="#">Vaccines</a>
            <a class="dropdown-item" href="#">Supplements</a>
          </div>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-3">
    <div class="row">
      <div class="col-md-12">
        <h1>Our Product categories</h1>
        <div class="card-deck">
          <div class="card">
            <img src="https://cloudinary.images-iherb.com/image/upload/f_auto,q_auto:eco/images/loc/loc35907/y/10.jpg" class="card-img-top" alt="Product 1" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Over-the-counter (OTC)</h5>
              <p class="card-text">These drugs you can buy without a prescription. Some OTC medicines relieve aches, pains, and itches.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="https://cdn.britannica.com/50/123550-050-885369B3/Prozac-pills.jpg" class="card-img-top" alt="Product 2" width="200" height="200">
            
            <div class="card-body">
              <h5 class="card-title">Drug therapy</h5>
              <p class="card-text">Drug therapy refers to the use of medication to treat or manage various medical conditions. </p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="https://vims.ac.in/vims-hospital/wp-content/uploads/2022/01/covid-still-life-with-vaccine.png" class="card-img-top" alt="Product 2" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Vaccine</h5>
              <p class="card-text">A vaccine is a biological preparation that provides active acquired immunity to a particular infectious or malignant disease.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="https://rukminim2.flixcart.com/image/850/1000/xif0q/ayurvedic/d/f/f/muscle-gain-capsule-bodybuilding-supplements-weight-gain-muscle-original-imagnthc5ygayvbs.jpeg?q=20&crop=false" class="card-img-top" alt="Product 3" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Supplements</h5>
              <p class="card-text">These include vitamins, minerals, herbs and botanicals, probiotics, and more.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 PharmaCompany. All rights reserved. BY SUBASH M (212224220109)</p>
  </footer>
  <body background="https://t4.ftcdn.net/jpg/08/44/82/55/360_F_844825587_MEoU8odal1uKKTjNOoFa0A4yLyZzJ0gG.jpg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - PharmaCompany</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">PharmaCompany</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="contact.html">Contact <span class="sr-only">(current)</span></a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Contact Us</h1>
        <p>For any inquiries or feedback, please fill out the form below and we will get back to you as soon as possible.</p>
        <form>
          <div class="form-group">
            <label for="name">Your Name</label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name">
          </div>
          <div class="form-group">
            <label for="email">Your Email</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email">
          </div>
          <div class="form-group">
            <label for="message">Message</label>
            <textarea class="form-control" id="message" rows=3" placeholder="Enter your message"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      <div class="col-md-4">
        <h2>Pharmaceutical Company</h2>
        <address>
          <strong>Address:</strong><br>
          Raj steel Factories,Nellore Highway<br>
          India, 524001<br><br>
          <strong>Email:</strong><br>
          mithun@pharmaceuticalcompany.com<br><br>
          <strong>Phone:</strong><br>
          +91 9703050305
        </address>
      </div>
    </div>
  </div>
 
  <body background="back4.jpeg" style="background-repeat: no-repeat; background-size: cover;">

    <br>
    <br>
  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-2 ">
    <p>&copy; 2024 PharmaCompany. All rights reserved.BY SUBASH M (212224220109)</p>

  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
# OUTPUT:
![Screenshot 2024-12-23 002759](https://github.com/user-attachments/assets/bef33e3f-7631-4577-bc65-43e96e7840c9)
![Screenshot 2024-12-23 002946](https://github.com/user-attachments/assets/111fe336-b5d4-488a-8800-10f802812596)
![Screenshot 2024-12-23 003033](https://github.com/user-attachments/assets/08d375c7-8b60-4a76-a5bb-cd90dcd58cce)
![Screenshot 2024-12-23 014919](https://github.com/user-attachments/assets/ad7f7ae8-581f-43cd-bde2-d0e9cc264dc9)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
