---
layout: portfolio
title: Production Design
subtitle: Design for Animation/ UI Design
image: /images/momo.png
permalink: /production-design/
imagefolder: /images/portfolios/production-design/
images:
  - name: 01.png
    thumb: thumbnail/01.png
    text: The first image
    class: w1
  - name: 02.png	
    thumb: thumbnail/02.png
    text: The second image
    class: w2
  - name: 03.png
    thumb: thumbnail/03.png
    text: The third image
    class: w1
  - name: 04.png
    thumb: thumbnail/04.png
    text: The third image
    class: w2
  - name: 05.png
    thumb: thumbnail/05.png
    text: The third image
    class: w1
  - name: 06.png
    thumb: thumbnail/06.png
    text: The third image
    class: w1
  - name: 07.png
    thumb: thumbnail/07.png
    text: The third image
    class: w2
  - name: 08.png
    thumb: thumbnail/08.png
    text: The third image
    class: w2
  - name: 09.png
    thumb: thumbnail/09.png
    text: The third image
    class: w2
  - name: 10.png
    thumb: thumbnail/10.png
    text: The third image
    class: w2
  - name: 11.png
    thumb: thumbnail/11.png
    text: The third image
    class: w2
  - name: 12.png
    thumb: thumbnail/12.png
    text: The third image
    class: w2
  - name: 13.png
    thumb: thumbnail/13.png
    text: The third image
    class: w2
  - name: 14.png
    thumb: thumbnail/14.png
    text: The third image
    class: w2
---

<div class="container">
    <div class="gutter-sizer"></div>
    <div class="grid-sizer"></div>
	  {% for image in page.images %}
	  <div class="item {{image.class}} three columns imagefill">
	  		<img src="{{page.imagefolder}}{{image.thumb}}">
  	</div>
	  {% endfor %}
</div>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/jquery.imagesloaded/2.1.0/jquery.imagesloaded.min.js"></script>
<script src="/js/imagefill.js"></script>
<script src="/js/packery.pkgd.min.js"></script>
<script type="text/javascript">
				// $('.imagefill').imagefill(); 
	// var $container = $('.container');
  
 //  $container.packery({
 //  	itemSelector: '.item',
 //  	  gutter: 0,
	// 	  "columnWidth": 0,
	// 	  "rowHeight": 0
	// }); 

</script>