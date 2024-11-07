---
header_type: splash
layout: minimal
title: Hidalgo Lab
subtitle: Washington State University
header_img : ""
---
<link href="/assets/css/main.css" rel="stylesheet" />

<style>
.video-banner video {
       position: relative; 
       left: 0; 
       top: 0; 
       width: 100%; 
       height: 100%; 
       object-fit: cover; }
    
.video-banner .text-overlay { 
    position: absolute; 
    left: 0; 
    top: 50%; 
    transform: translateY(-50%); 
    text-align: center; 
    width: 100%; 
    opacity: 0.8; }
      
.jumbotron {
  font-size: 25px;
  text-align:justify; 
  overflow:hidden; 
}
.lead {
  font-size: 30px;
}
.card-deck{
  padding:10px;
}
.jumbotron-image {
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;    
  opacity:0.8;
  
}
.jumbotron-image:hover {
  opacity:1;
}    
.card {
  opacity: 0.8;
}
.card:hover {
  opacity: 1;
}
</style>


<div class="video-banner" style="height: 750px;">
   <video src="./assets/images/video.mp4"  autoplay="" preload="auto" loop="" playsinline="" disablepictureinpicture="" disableremoteplayback="" webkit-playsinline="" muted=""></video>
  <div class="d-flex align-items-center hero-chulapa">
      <div class="text-overlay">
    <h1 class="p-name" >{{- page.title | default: "Where's your title?" -}}</h1>
    <hr class="my-3">
    <p class="chulapa-subtitle p-summary">{{- page.subtitle -}}</p></div></div>
  </div>

<div class="jumbotron text-white jumbotron-image shadow" style="background-image: url(/assets/images/banner1.tif);">
<h1>Our question</h1>   
<p style="float:left; width:70%;">The human brain changes structurally and functionally across seasons. Many aspect of our physiology are seasonally regulated, and many disorders, like Parkinson’s, Alzheimer’s, and depression, show seasonal variations in their symptoms. The mechanisms orchestrating these changes and how they affect these disorders are not well understood. 
</p>
</div>

<div class="jumbotron text-white jumbotron-image shadow" style="background-image: url(/assets/images/banner2.tif);">
<h1>Our goal</h1>      
<p style="float:left; width:70%;">
We seek to understand the mechanisms driving seasonal physiology and diseases. Particularly, we focus in the role of the circadian clock, the mechanism that allows organisms to adjust to the day/night cycles in the changing seasonal brain, in this process.
<br>
<br>
<a type="button" href="/Science/Research" class="btn btn-outline-light">Current Projects</a>    
</p>
<br>
</div>

<div class="jumbotron text-white jumbotron-image shadow" style="background-image: url(/assets/images/banner3.tif); ">
<h1>Learn more...</h1>     
<div class="card-deck">
  <div class="card">
      <h3 class="card-title">Research</h3>
      <p class="card-text">Check out our current projects!</p>
      <img class="card-img-bottom" src="/assets/images/cards/Research.png" alt="Brain Seasonal">
      <a href="/Science/Research" class="stretched-link"></a>
  </div>
  <div class="card">
      <h3 class="card-title">Publications</h3>
      <p class="card-text">Check out our latest publications!</p>
      <img class="card-img-bottom" src="/assets/images/cards/Publications.jpeg" alt="Publications">
      <a href="/Science/Publications" class="stretched-link"></a>
  </div>
  <div class="card">
      <h3 class="card-title">Our approach</h3>
      <p class="card-text">Looking for a protocol?</p><br>
      <video class="card-img-bottom" src="/assets/images/cards/video.mp4" autoplay="" preload="auto" loop="" playsinline="" disablepictureinpicture="" disableremoteplayback="" webkit-playsinline="" muted=""></video>
      <a href="/Science/Techniques" class="stretched-link"></a>
  </div>
  <div class="card">
      <h3 class="card-title">Contact</h3>
      <p class="card-text">Get in touch!</p> <br>
      <img class="card-img-bottom" src="/assets/images/cards/Contact.jpeg" alt="Contact">
      <a href="/Contact" class="stretched-link"></a>
  </div>
</div>
</div>
<br>
<br>
<div class="row" style="justify-content: center; overflow:hidden;">
  <div class="column">
      <br>
    <img src="/assets/images/logos/logo2.png" alt="WSU" style="width:250px;">
  </div>
<br>
  <div class="column">
    <img src="/assets/images/logos/lablogo.png" alt="Lab logo" style="width:250px;">
  </div>
</div>
<br>

  