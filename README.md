<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>ccc</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
    <script src="https://use.fontawesome.com/releases/v5.0.8/js/all.js"></script>
  
	<link href="boss.css" rel="stylesheet">
	

</head>
<body>
	
	
<!--Navigation -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#"><img src="logoo.png"></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">About</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Team</a>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#">Contact</a>
      </li>
    </ul>
  </div>
  <nav class="navbar navbar-light bg-light">
  <form class="form-inline">
    <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
    <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
  </form>
</nav>
</nav>
<!-- Image Slider -->
<div id="slides" class="carousel slide" data-ride="carousel">
<ul class="carousel-indicators">
   <li data-target="#slides" data-slide-to="0" class="active"></li>
   <li data-target="#slides" data-slide-to="1"></li>
   <li data-target="#slides" data-slide-to="2"></li>
</ul>
<div class="carousel-inner">
	<div class="carousel-item active">
		<img src="hhh.png">
		<div class="carousel-caption">
			<h1 class="display-2">Bootstrap</h1>
			<h3> Complete web site Layout</h3>
			<button type="button" class="btn btn-outline-light btn-lg"> View DEMO</button>
			<button tpye="button" class="btn btn-primary btn-lg">Get Started</button>
		</div>
	</div>
	<div class="carousel-item">
		<img src="15.jpg">
	</div>
	<div class="carousel-item">
		<img src="photo.jpg">
	</div>
</div>	
</div>
<br>
<br>
<br>
<!-- Jumbotron -->
<div class="container-fluid">
<div class="row jumbotron">
	<div class="col-xs-12 col-sm-12 col-md-9 col-lg-9 col-xl-10">
		<p class="lead"> A web hosting service allows individuals and organization to make website accessible vie the wold wide web.</p>
	</div>
	<div class="col-xs-12 col-sm-12 col-md-3 col-lg-3 col-xl-2">
		<a href="#"><button type="button" class="btn btn-outline-secondary btn-lg">web hosting</button></a>
	</div>

</div>
</div>
<!-- Welcome Section -->
<div class= "container-fluid padding">
<div class="row welcome text-center">
	<div class="col-12">
		<h1 class="display-4"> Built with ease.</h1>
	</div>
	<hr>
	<div class="col-12">
		<p class="lead"> Welcome to my bootstrap 4 website tutorial! boostraps is free and open-source font-end libray with html and css based designs.</p>
	</div>
</div>
</div>
<!-- Three Column Section -->
<div class= "container-fluid padding">
<div class="row text-center padding">
	<div class="col-xs-12 col-sm-6 col-md-4">
		<i class="fas fa-code"></i>
		<h3>HTML</h3>
		<p>built with the latest version of thml.HTML5.</p>
	</div>
	<div class="col-xs-12 col-sm-6 col-md-4">
		<i class="fas fa-bold"></i>
		<h3>BOOSTRAP</h3>
		<P>Built with the latest version of Bootstrap,Bootstrap</P>
	</div>
	<div class="col-ms-12 col-md-4">
		<i class="fab fa-css3"></i>
		<h3>CSS3</h3>
		<P>Built with the latest version of CSS3,CSS3</P>
	</div>

</div>
<hr class="my-4">
</div>
<!-- two Column Section -->
<div class="container-fluid padding">
	<div class="row padding">
		<div class="col-lg-6">
			<h2>If you build It ....</h2>
			<p>the columns will automaticalty stock on top of each other wides</p>
			<p> the columns will automaticalty stock on top of each other wides</p>
			<p>the columns will automaticalty stock on top of each other wides</p>
			<p>it can display the web page differenty depending on</p>
			<hr>
			<a href="https://www.ayoubshop123.xyz/heartbreaking-photo-series-captures-the-raw-grief-of-owners-as-their-pets-are-being-euthanized/2/" class="btn btn-primary btn-lg">Learn More</a>
			<br><br>
		</div>
		<div class="col-lg-6">
			<img src="10.jpg" class="img-fluid">
		</div>
</div>
</div>
<hr class="my-4">
<!--Fixed background-->
<figure>
	<div class="Fixed-wrap">
		<div id="fixed">
		</div>
	</div>
</figure>

<!--Emoji section-->


<!--Meet the team-->
<div class="container-fluid padding">
<div class="row welcome text-center">
	<div class="col-12">
		<h1 class="display-4">Meet the Team</h1>
    </div>
    <hr>
</div>
</div>
<!--cards-->
<div class="container-fluid padding">
<div class="row padding">
	<div class="col-md-4">
		<div class="card">
			<img class="card-img-top" src="14.jpg">
			<div class="card-body">
				<h1 class="card-title">John Doe</h1>
				<p class="card-text">John is an Internet entrepreneur with almost 20 years of experience.</p>
				<a href="#" class="btn btn-outline-secondary">See Profile</a>
			</div>

		</div>
	</div>
	<div class="col-md-4">
	    <div class="card">
		     <img class="card-img-top" src="wix11.png">
		     <div class="card-body">
			      <h1 class="card-title">Doha</h1>
			      <p class="card-text">Doha is a designer with almost 20 years of digital design experience.</p>
			      <a href="#" class="btn btn-outline-secondary">See Profile</a>
		    </div>
		</div>
	</div>


    <div class="col-md-4">
	     <div class="card">
		      <img class="card-img-top" src="13.jpg">
		       <div class="card-body">
		       	   <h1 class="card-title">ayoub</h1>
			       <p class="card-text">ayoub is a developer with almost 5 years of web developer experience.</p>
		           <a href="#" class="btn btn-outline-secondary">See Profile</a>
	           </div>      
	     </div>
    </div>




</div>	
</div>


<!-- two Column section-->
<div class="container-fluid padding">
<div class="row padding">
	<div class="col-lg-6">
		<h2>If you it...</h2>
		<p>the columns will automaticalty stock on top of each other wides</p>
		<p> the columns will automaticalty stock on top of each other wides</p>
		<p>the columns will automaticalty stock on top of each other wides</p>
		<p>it can display the web page differenty depending on. and we have got it down to a science.</p>
	
	</div>	
	<div class="col-lg-6">
		<img src="fiverr.jpg" class="img-fluid">
	</div>
</div>
</div>
<!-- Connect-->

<div class="container-fluid padding">
<div class="row text-center padding">
	<div class="col-12">
		<h2>Commect</h2>
	</div>
    <div class="col-12 social padding">
		<a href="#"><i class="fab fa-facebook"></i></a>
        <a href="#"><i class="fab fa-twitter"></i></a>
        <a href="#"><i class="fab fa-google"></i></a>
        <a href="#"><i class="fab fa-linkedin"></i></a>
        <a href="#"><i class="fab fa-youtube"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
        <a href="#"><i class="fab fa-pinterest"></i></a>
	</div>
</div>
</div>


<!--footer-->

<footer>
<div class="container-fluid padding">
<div class="row text-center">
	<div class="col-md-4">
		<img src="logoo.png"> 
		<hr class="light">
		<p>555-668-578</p>
		<p>100 street name</p>
		<p>ayoub@gmail.com</p>
		<p>City, state. 0000</p>
	</div>
	<div class="col-md-4">
		<hr class="Light">
		<h5> our hours</h5>
		<hr class="Light">
		<p>Monday: 9am- 4pm</p>
		<p>Saturday 10 pm- 4pm</p>
	</div>
	<div class="col-md-4">
		<hr class="Light">
		<h5> Service Area </h5>
		<hr class="Light">
		<p>Monday: 9am- 4pm</p>
		<p>Saturday 10 pm- 4pm</p>
		<p>City, state, 00000</p>
		<p>City, state, 00000</p>
		<p>City, state, 00000</p>
	</div>
	<div class="col-md-4">
		<hr class="Light-100">
		<h5 class="copyright">Copyright© 2020 | A Better Resume Service </h5>
    </div>

</div>
	</div>
	
</footer>





</body>
</html>
