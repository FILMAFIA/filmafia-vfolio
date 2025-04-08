---
layout: default
title: News
---

<head>
    <link rel="stylesheet" href="style/gallery.css">
    <script type="text/javascript" src="js/galeria.js"></script>
</head>


<body>
 <!----------------- GALERÍA --------------------->
            <!-- Slideshow container -->
    <div class="slideshow-container">
        <!-- Full-width images with number and caption text -->
        <div class="mySlides fade">
        <div class="numbertext">1 / 3</div>
        <img src="assets/images/the_best_1/DSC08502.jpg" style="width:50%">
        <div class="text">Caption Text</div>
        </div>
        <div class="mySlides fade">
        <div class="numbertext">2 / 3</div>
        <img src="assets/images/the_best_1/DSC08509.jpg" style="width:50%">
        <div class="text">Caption Two</div>
        </div>
        <div class="mySlides fade">
        <div class="numbertext">3 / 3</div>
        <img src="assets/images/the_best_1/DSC08745.jpg" style="width:50%">
        <div class="text">Caption Three</div>
        </div>
        <!-- Next and previous buttons -->
        <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1)">&#10095;</a>
    </div>
    <!-- The dots/circles -->
    <div style="text-align:center">
        <span class="dot" onclick="currentSlide(1)"></span>
        <span class="dot" onclick="currentSlide(2)"></span>
        <span class="dot" onclick="currentSlide(3)"></span>
    </div>
</body>
