<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Bootstrap Example with Background Image and Responsive Table/Mobile View</title>

<link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" 

rel="stylesheet">

<style> 

body {

/* Adding background image */ 

background-image:

url('https://content.jdmagicbox.com/comp/chennai/62/044p7001762/catalogue/dr-mgr-educational-

and-research-institute-deemed-to-be-university-faculty-of-hotel-management-and-catering-

technology-adayalampattu-chennai-institutes-for-hotel-management-

mc8bo.jpg?clr=#3a2c3a?w=3840&q=75'); /* Replace this with a direct image URL */

background-size: cover; /* This will make the image cover the entire background */ 

background-position: center; /* Centers the background image */

background-repeat: no-repeat; /* Prevents image from repeating */ 

height: 100vh; /* Ensures the background covers the whole page */

}

.jumbotron {

background-color: rgba(255, 255, 255, 0.8); /* Adding slight opacity to jumbotron */

}

/* Adding custom colors to each column */

.cse {

background-color: #ff9999; /* Light red for CSE */ 

padding: 20px;

}

.cse-ai {
background-color: #99ccff; /* Light blue for CSE-AI */ 

padding: 20px;

}

.cse-dsai {

background-color: #99ff99; /* Light green for CSE-DS&AI */ 

padding: 20px;

}

.cse-cfis {

background-color: #ffcc99; /* Light orange for CSE-CFIS */ 

padding: 20px;

}

</style>

</head>

<body>

<nav class="navbar navbar-expand-lg navbar-light bg-light">

<a class="navbar-brand" href="#">Navbar</a>

<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" 

aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">

<span class="navbar-toggler-icon"></span>

</button>

<div class="collapse navbar-collapse" id="navbarNav">

<ul class="navbar-nav">

<li class="nav-item active">

<a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>

</li>

<li class="nav-item">

<a class="nav-link" href="#">Events</a>

</li>

<li class="nav-item">

<a class="nav-link" href="#">Contact</a>

</li>

<li class="nav-item">

<a class="nav-link" href="#">Help</a>
</li>

</ul>

</div>

</nav>

<div class="container mt-3">

<div class="jumbotron">

<h1>Welcome to Dr MGR Educational and Research Institute</h1>

</div>

<div class="row text-center">

<div class="col-12 col-md-3 cse">CSE</div>

<div class="col-12 col-md-3 cse-ai">CSE-AI</div>

<div class="col-12 col-md-3 cse-dsai">CSE-DS&AI</div>

<div class="col-12 col-md-3 cse-cfis">CSE-CFIS</div>

</div>

</div>

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>

<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.2/dist/umd/popper.min.js"></script>

<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>

</html>
