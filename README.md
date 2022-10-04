<!DOCTYPE html>
<html lang="en">
<head>
  <title>Portfolio Website-William</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- linking css file -->
  <link rel="stylesheet" href="style.css">
  <!-- bootstrap CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
  <!-- font awesome -->
  <script src="https://kit.fontawesome.com/31149d48b0.js" crossorigin="anonymous"></script>
</head>
<nav class="navbar navbar-expand-lg fixed-top navbarScroll">
    <div class="container">
        <a class="navbar-brand" href="#">William</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#home">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#about">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#projects">Projects</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#contact">Contact</a>
                </li>
            </ul>
            
        </div>
    </div>
</nav>
<!-- about section-->
<section id="about">
    <div class="container mt-4 pt-4">
        <h1 class="text-center">About Me</h1>
        <div class="row mt-4">
            <div class="col-lg-4">
                <img src="about.jpeg" class= "imageAboutPage" alt="">
            </div>

            <div class="col-lg-8">
                <p> I like the color purple
                    
                </p>
                <div class="row mt-3">
                    <div class="col-md-6">
                        <ul>
                            <li>Name: William Maung</li>
                            <li>Age: 21</li>
                            <li>Occupation: Ontario Tech University Student</li>

                        </ul>
                    </div>


                        </ul>
                    </div>
                </div>
                <div class="row mt-3">
                    <p> 
                    </p>
                </div>
            </div>
        </div>
</section>

<!-- Projects section-->
<section id="Projects">
    <div class="container mt-3">
        <h1 class="text-center">Projects</h1>
        <div class="row">
            <div class="col-lg-4 mt-4">
                <div class="card">
                    <img class="card-img-top" src="images/portfolioImage1.jpg" alt="Card image" style="width:100%">
                    <div class="card-body">
                        <h4 class="card-title">Intro to Computer Security</h4>
                        <p class="card-text">Lab 1 (9/23/2022) .</p>
                        <div class="text-center">
                            <a href="#" class="btn btn-success">Link</a>
                        </div>
                    </div>
                </div>
            </div>

            <div class="col-lg-4 mt-4">
                <div class="card portfolioContent">
                    <img class="card-img-top" src="images/portfolioImage4.jpg" alt="Card image" style="width:100%">
                    <div class="card-body">
                        <h4 class="card-title">Intro to Networking</h4>
                        <p class="card-text">Weekly lab #4 (30/9/2022)</p>
                        <div class="text-center">
                            <a href="#" class="btn btn-success">Link</a>
                        </div>
                    </div>
                </div>
            </div>

            <div class="col-lg-4 mt-4">
                <div class="card portfolioContent">
                    <img class="card-img-top" src="images/portfolioImage3.jpg" alt="Card image" style="width:100%">
                    <div class="card-body">
                        <h4 class="card-title">Intro to Entrepreneur</h4>
                        <p class="card-text">Module exam (29/9/2022)</p>
                        <div class="text-center">
                            <a href="#" class="btn btn-success">Link</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
 
</section>

<!-- contact section-->
<section id="contact">
    <div class="container mt-3 contactContent">
        <h1 class="text-center">Contact Me</h1>

        <div class="row mt-4">
            <div class="col-lg-6">
                <!-- to edit google map goto https://www.embed-map.com type your location, generate html code and copy the html  -->
                <div style="max-width:100%;overflow:hidden;color:red;width:500px;height:500px;">
                    <div id="embedmap-canvas" style="height:100%; width:100%;max-width:100%;">
                        <iframe style="height:100%;width:100%;border:0;" frameborder="0" src="https://www.google.com/maps/embed/v1/place?q=new+york&key=AIzaSyBFw0Qbyq9zTFTd-tUY6dZWTgaQzuU17R8">
                        </iframe>
                    </div>
                    <a class="googlemaps-html" href="https://www.embed-map.com" id="get-data-forembedmap">https://www.embed-map.com</a>
                    <style>#embedmap-canvas img{max-width:none!important;background:none!important;font-size: inherit;font-weight:inherit;}
                    </style>
                </div>
            </div>

            <div class="col-lg-6">
                <!-- form fields -->
                <form>
                    <input type="text" class="form-control form-control-lg" placeholder="Name">
                    <input type="email" class="form-control mt-3" placeholder="Email">
                    <input type="text" class="form-control mt-3" placeholder="Subject">
                    <div class="mb-3 mt-3">
                        <textarea class="form-control" rows="5" id="comment" name="text" placeholder="Project Details"></textarea>
                    </div>
                </form>
                <button type="button" class="btn btn-success mt-3">Contact Me</button>
                
            </div>

        </div>
    </div>
</section>

 <!-- footer section-->
 <footer id="footer">
    <div class="container-fluid">
        <!-- social media icons -->
        <div class="social-icons mt-4">
            <a href="https://www.facebook.com/" target="_blank"><i class="fab fa-facebook"></i></a>
            <a href="https://www.instagram.com/" target="_blank"><i class="fab fa-instagram"></i></a>
            <a href="https://www.twitter.com/" target="_blank"><i class="fab fa-twitter"></i></a>
            <a href="https://www.linkedin.com/" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a href="https://www.twitch.tv/" target="_blank"><i class="fab fa-twitch"></i></a>
        </div>
    </div>
</footer>
<body>
    <!-- load javascript after loading all html content -->
    <script src="script/script.js"></script>
</body>
</html>
