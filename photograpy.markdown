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
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/pika.JPG" style="width:100%" alt="Pika">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/stream.JPG" style="width:100%" alt="Alpine Stream">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/flower.JPG" style="width:100%" alt="Flower">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/skis.JPG" style="width:100%" alt="Backcountry Skiing">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/bass.JPG" style="width:44.44%" alt="Bass Guitar">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/pond_house.JPG" style="width:100%" alt="Pond Reflecting House">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/tent.JPG" style="width:44.44%" alt="Tent at Night">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/fourth_of_july.JPG" style="width:100%" alt="Fourth of July in Denver">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/pipe-sculpture.JPG" style="width:100%" alt="Pipe Sculpture">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/guitar.JPG" style="width:100%" alt="Guitar">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/washington-train.JPG" style="width:100%" alt="Mount Washington Railcar">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/bird.JPG" style="width:100%" alt="Bird">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/Storkyrkan.JPG" style="width:44.44%" alt="Storkyrkan">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/cactus.JPG" style="width:100%" alt="Cactus">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/lighthouse.JPG" style="width:100%" alt="Lighthouse">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/poinsettia.JPG" style="width:100%" alt="Poinsettia">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/moon.JPG" style="width:100%" alt="Moon">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/stockholm_city_hall.JPG" style="width:100%" alt="Stockholm City Hall">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/footprint.JPG" style="width:100%" alt="Footprint">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/rowboat.JPG" style="width:100%" alt="Rowboat Sunrise">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/bricks.JPG" style="width:100%" alt="Bricks">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/double_arch_startrail.PNG" style="width:100%" alt="Star Trail at Arches">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/climber.JPG" style="width:44.44%" alt="Rock Climber">
  <img class="mySlides" src="{{ site.baseurl }}/assets/photos/mountain-look.JPG" style="width:100%" alt="Mountain Look">

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