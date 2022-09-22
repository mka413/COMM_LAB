
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" 
    content="width=device-width, initial-scale=1.0">
    <title>scroll website</title>
    <link rel="stylesheet" href="styles.css" />

</head>
<body>
    <!--navbar section-->
<nav class="navbar">
<div class="navbar__container">
    <a href="#home" id="navbar__logo">MAS</a>
    <div class="navbar__toggle" id="mobile-menu">
       <span class="bar"></span> 
       <span class="bar"></span> 
       <span class="bar"></span> 
    </div>
    <ul class="navbar__menu">
        <li class="navbar__item">
            <a href="#home" class="navbar__links" id="home-page">Home</a>
        </li>
        <li class="navbar__item">
            <a href="#about" class="navbar__links" id="about-page">About</a>
        </li>
        <li class="navbar__item">
            <a href="#gallery" class="navbar__links" id="gallery-page">Gallery</a>
        </li>
        <li class="navbar__btn">
            <a href="#contact" class="button" id="contactus">Contact</a>
        </li>
    </ul>
  
</div>
</nav>
<!-- Hero section -->
<div class="hero" id="home">
<div class="div__container">
  <h1 class="hero__heading">The Tribe   <span>   Maasai</span></h1>  
  <p class="hero__description">Supai (Hello!)</p>

</div>
</div>
<!-- About section -->
<div class="main" id="about">
   
      <div class="main__content">
        <h1> Who are they?<h1>
            <h2> The masaai</h2>
            <p> The Maasai are a Nilotic ethnic group inhabiting northern, central and southern Kenya and northern Tanzania.

            </p>
            
      </div>   
   </div> 
</div>
<!-- gallery section -->
<div class="Gallery" id="Gallery">
    <h1> MAASAI DANCE </h1>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/UB4aPU2yTSE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <div class="gallery__wrapper">
        <div class="Gallery__card">
                  <div class="Gallery__btn"><button>Click Here</button>
                </div>
 </div>
    </div>

</div>
<script src="app.js"></script>
</body>
</html>
