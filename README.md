# Travel-web
mini web project
<!Doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">

    <titlet>Travel Website</title>
    <!--link font-->
    
    <link rel="stylesheet" type="text/css" href="cssstyles.css">
    <!--Favicon-->
  </head>
  <body>
    
<!--Navigation bar-->
<div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
  <a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-dark text-decoration-none">
    <svg class="bi me-2" width="40" height="32" role="img" aria-label="Bootstrap"><use xlink:href="#bootstrap"></use></svg>
  </a>

  <ul class="nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
    <li><a href="#" class="nav-link px-2 link-secondary">Explore</a></li>
    <li><a href="#" class="nav-link px-2 link-dark"> Upcoming Events</a></li>
    <li><a href="#" class="nav-link px-2 link-dark">Shop </a></li>
  </ul>

  <form class="col-12 col-lg-auto mb-3 mb-lg-0 me-lg-3">
    <input type="search" class="form-control" placeholder="Search..." aria-label="Search">
  </form>

  <div class="dropdown text-end">
    <a href="#" class="d-block link-dark text-decoration-none dropdown-toggle" id="dropdownUser1" data-bs-toggle="dropdown" aria-expanded="false">
      <img src="pic1.jpg" alt="mdo" width="32" height="32" class="rounded-circle">
    </a>
    <ul class="dropdown-menu text-small" aria-labelledby="dropdownUser1">
      <li><a class="dropdown-item" href="#">New project...</a></li>
      <li><a class="dropdown-item" href="#">Settings</a></li>
      <li><a class="dropdown-item" href="#">Profile</a></li>
      <li><hr class="dropdown-divider"></li>
      <li><a class="dropdown-item" href="#">Sign out</a></li>
    </ul>
  </div>
</div>
        
          
    </div>
  </div>
</nav>
<!--carosel-->
<div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active" data-bs-interval="10000">
      <img src="lee-blanchflower-1dW1vEJLlCQ-unsplash.jpg" class="d-block w-100" style="height:400px;">
      <div class="carousel-caption d-none d-md-block">
        <h5>First slide label</h5>
        <p>Some representative placeholder content for the first slide.</p>
      </div>
    </div>
    <div class="carousel-item" data-bs-interval="2000">
      <img src="pablo-heimplatz-ZODcBkEohk8-unsplash.jpg"class="d-block w-100" style="height:400px;">
      <div class="carousel-caption d-none d-md-block">
        <h5>Second slide label</h5>
        <p>Some representative placeholder content for the second slide.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="samantha-gades-fIHozNWfcvs-unsplash.jpg" class="d-block w-100" style="height:400px;">
      <div class="carousel-caption d-none d-md-block">
        <h5>Third slide label</h5>
        <p>Some representative placeholder content for the third slide.</p>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
<!--services offered-->
<section id="services offered" class="container" ><!--gives a margin-->
    <br>
    <br>
    <hr>
    
    <div class="row" >
       <div class="col-sm-4">
        <img src="rolands-varsbergs-miKmVyq3qhE-unsplash.jpg"class="img-fluid img-responsive" >
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor porro, commodi maiores, architecto consectetur, esse molestiae est dolore quam 
        a nisi ratione qui laboriosam. Quis delectus exercitationem nisi odit cumque?</p></div>
        
        <div class="col-sm-4">
          <img src="ryan-spencer-XGKaRnWjv1c-unsplash.jpg"class="img-fluid img-responsive" >
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor porro, commodi maiores, architecto consectetur, esse molestiae est dolore quam 
          a nisi ratione qui laboriosam. Quis delectus exercitationem nisi odit cumque?</p></div>
          
          <div class="col-sm-4">
            <img src="s-migaj-Yui5vfKHuzs-unsplash.jpg"class="img-fluid img-responsive">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor porro, commodi maiores, architecto consectetur, esse molestiae est dolore quam 
            a nisi ratione qui laboriosam. Quis delectus exercitationem nisi odit cumque?</p></div>
      
    </div>

</section>
<!--Gallery and buy now-->
<section id="Gallery" class="container">
    <div class="row" >
        <div class="col-sm-4">
         <img src="rolands-varsbergs-miKmVyq3qhE-unsplash.jpg"class="img-fluid img-responsive" >
         <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor porro, commodi maiores, architecto consectetur, esse molestiae est dolore quam 
         a nisi ratione qui laboriosam. Quis delectus exercitationem nisi odit cumque?</p></div>
         
         <div class="col-sm-4">
           <img src="ryan-spencer-XGKaRnWjv1c-unsplash.jpg"class="img-fluid img-responsive" >
           <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor porro, commodi maiores, architecto consectetur, esse molestiae est dolore quam 
           a nisi ratione qui laboriosam. Quis delectus exercitationem nisi odit cumque?</p></div>
           
           <div class="col-sm-4">
             <img src="s-migaj-Yui5vfKHuzs-unsplash.jpg"class="img-fluid img-responsive">
             <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor porro, commodi maiores, architecto consectetur, esse molestiae est dolore quam 
             a nisi ratione qui laboriosam. Quis delectus exercitationem nisi odit cumque?</p></div>
       
     </div>
        
    
  </div>

</section>
<!--footer-->
<footer class="container">
<div class="row">
  <div class="col-sm-4">
    <img src="download.png" class="img-fluid img-responive">
  </div>
  <div class="col-sm-4">
    <ul type="none">
      <li><a href="#">About</a></li>
      <li><a href="#">Privacy policy</a></li>
      <li><a href="#">Terms and conditions</a></li>
    </ul>
  </div>
  <div class="col-sm-4">
    <p>Phone:9895968753</p>
    <p>Email:neharachel89@gmail.com</p>
  </div>
</div>
</footer>
    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.min.js" integrity="sha384-Atwg2Pkwv9vp0ygtn1JAojH0nYbwNJLPhwyoVbhoPwBhjQPR5VtM2+xf0Uwh9KtT" crossorigin="anonymous"></script>
    -->
  </body>
</html>

