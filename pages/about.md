---
layout: page
menu: true
date: '2020-02-27 01:53:59'
title: About Abarel
description: Abarel video production studio creates engaging commercials, brand content, animated explainers, food video, and TV ads, including commercials created by AI.
permalink: /about/
---

<img class="img-rounded" src="../assets/img/uploads/abarel-studio.png" alt="Abarel Studio Logo" width="200"> 

# About Abarel Studio

Abarel is a cutting-edge video production and online B2B marketing agency that unleashes boundless creativity. Our expertise spans across crafting captivating brand content, dynamic animated explainers, awesome TV ads, tantalizing food commercials, captivating event coverage, and an array of other exciting offerings. 
From masterpieces born of human ingenuity to groundbreaking ads conjured with the aid of AI, we pride ourselves on pushing the boundaries of what's possible in the realm of creative marketing.

Our productions are made explicitly for all communication purposes. From concept and scriptwriting to image recording and post-production, sound mixing up to delivering the final product for commercials, TV, and social media. Just like that.

## Gallery-4 

Include use image-gallery-4.html
 
4 images in row without shows big images. Best for logos.

{% include image-gallery-4.html folder="/uploads/album" %}


## Gallery w/Lightbox

Include use image-gallery.html
 
3 images in row with link to shows big images. Best for nice gallery .

{% include image-gallery.html folder="/uploads/album" %}


## They trusted us!

How to create side-by-side images with the CSS float property:
Extar for logo gallery, no show-up

<html>
<head>
<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>
</head>
<body>

<div class="row">
  <div class="column">
    <img src="https://www.w3schools.com/howto/img_snow.jpg" alt="Snow" style="width:100%">
    <img src="https://www.w3schools.com/howto/img_forest.jpg" alt="Forest" style="width:100%">
    <img src="https://www.w3schools.com/howto/img_mountains.jpg" alt="Mountains" style="width:100%">
  </div>
  <div class="column">
    <img src="https://www.w3schools.com/howto/img_forest.jpg" alt="Forest" style="width:100%">
    <img src="https://www.w3schools.com/howto/img_mountains.jpg" alt="Mountains" style="width:100%">
     <img src="https://www.w3schools.com/howto/img_snow.jpg" alt="Snow" style="width:100%">
  </div>
  <div class="column">
    <img src="https://www.w3schools.com/howto/img_mountains.jpg" alt="Mountains" style="width:100%">
    <img src="https://www.w3schools.com/howto/img_forest.jpg" alt="Forest" style="width:100%">
    <img src="https://www.w3schools.com/howto/img_forest.jpg" alt="Forest" style="width:100%">
  </div>
</div>

</body>
</html>


Quisque consequat sapien eget quam rhoncus, sit amet laoreet diam tempus. Aliquam aliquam metus erat, a pulvinar turpis suscipit at.

![placeholder](https://placehold.it/200x200 "Small example image") 
![placeholder](https://placehold.it/200x200 "Small example image"
![placeholder](https://placehold.it/200x200 "Small example image") 

<script type="text/javascript" src="/abarel.github.io/assets/js/lightbox.js"></script>
<link rel="stylesheet" href="/abarel.github.io/assets/css/lightbox.css">
