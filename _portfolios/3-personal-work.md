---
layout: portfolio
title: Personal Work
subtitle: Illustration
image: /images/momo.png
permalink: /personal-work/
imagefolder: /images/portfolios/personal-work/
images:
  - name: red.png
    thumb: thumb-1.jpg
    text: The first image
    class: w1
  - name: teal.png	
    thumb: thumb-2.jpg
    text: The second image
    class: w2
  - name: red.png
    thumb: thumb-3.jpg
    text: The third image
    class: w1
  - name: teal.png
    thumb: thumb-3.jpg
    text: The third image
    class: w2
  - name: red.png
    thumb: thumb-3.jpg
    text: The third image
    class: w1
  - name: teal.png
    thumb: thumb-3.jpg
    text: The third image
    class: w1
  - name: red.png
    thumb: thumb-3.jpg
    text: The third image
    class: w2
  - name: teal.png
    thumb: thumb-3.jpg
    text: The third image
    class: w2
  - name: red.png
    thumb: thumb-3.jpg
    text: The third image
    class: w2
  - name: teal.png
    thumb: thumb-3.jpg
    text: The third image
    class: w2
  - name: red.png
    thumb: thumb-3.jpg
    text: The third image
    class: w2
  - name: teal.png
    thumb: thumb-3.jpg
    text: The third image
    class: w2
  - name: red.png
    thumb: thumb-3.jpg
    text: The third image
    class: w2
  - name: teal.png
    thumb: thumb-3.jpg
    text: The third image
    class: w2
  - name: red.png
    thumb: thumb-3.jpg
    text: The third image
    class: w2
  - name: teal.png
    thumb: thumb-3.jpg
    text: The third image
    class: w2
---

<div class="container">
    <div class="gutter-sizer"></div>
    <div class="grid-sizer"></div>
	  {% for image in page.images %}
	  <div class="item {{image.class}} three columns">
	  		<img src="{{page.imagefolder}}{{image.name}}">
  	</div>
	  {% endfor %}
</div>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script src="/js/packery.pkgd.min.js"></script>
<script src="/js/imagesloaded.pkgd.min.js"></script>
<script type="text/javascript">
				
	// var $container = $('.container');
  
 //  $container.packery({
 //  	itemSelector: '.item',
 //  	  gutter: 0,
	// 	  "columnWidth": 0,
	// 	  "rowHeight": 0
	// }); 

</script>