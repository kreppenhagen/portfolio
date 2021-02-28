---
layout: page
title: Photography
order: 9
icon: fa-camera
permalink: /photography/
---
<style>
.mySlides {display:block;margin-left: auto;margin-right:auto}
</style>
<body>

<div class="w3-content w3-display-container">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/mirror.JPG" style="width:100%" alt="Mirror">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/bricks.JPG" style="width:100%" alt="Bricks">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/pipe-sculpture.JPG" style="width:100%" alt="Pipe Sculpture">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/guitar.JPG" style="width:100%" alt="Guitar">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/bird.JPG" style="width:100%" alt="Bird">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/flower.JPG" style="width:100%" alt="Flower">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/cactus.JPG" style="width:100%" alt="Cactus">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/poinsettia.JPG" style="width:100%" alt="Poinsettia">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/lighthouse.JPG" style="width:100%" alt="Lighthouse">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/milkyway.JPG" style="width:100%" alt="Milkyway">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/moon.JPG" style="width:100%" alt="Moon">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/footprint.JPG" style="width:100%" alt="Footprint">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/rowboat.JPG" style="width:100%" alt="Rowboat Sunrise">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/bunker-hill.JPG" style="width:50%;float:center" alt="Bunker Hill">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/climber.JPG" style="width:44.44%" alt="Rock Climber">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/mountain-look.JPG" style="width:100%" alt="Mountain Look">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/train-tracks.JPG" style="width:100%" alt="Train Tracks">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/washington-train.JPG" style="width:100%" alt="Mount Washington Railcar">

  <button class="w3-button w3-black w3-display-left" onclick="plusDivs(-1)">&#10094;</button>
  <button class="w3-button w3-black w3-display-right" onclick="plusDivs(1)">&#10095;</button>
</div>

<script>
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  if (n > x.length) {slideIndex = 1}
  if (n < 1) {slideIndex = x.length}
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  x[slideIndex-1].style.display = "block";  
}
</script>

</body>