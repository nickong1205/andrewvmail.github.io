---
layout: default
title: Portfolio
permalink: /portfolio/
---

<div class="container portfolio">
	  {% for portfolio in site.portfolios %}
	    <div class="portfolio four columns">

	      <div class="portfolio-box">
		      	<a href="{{ portfolio.url }}">

		      			      <img class="portfolio-image" src="{{ portfolio.image }}">
		      			      <div class="portfolio-image-eye"></div>
		      		<h1 class="portfolio-title">{{ portfolio.title }}</h1>
		      	</a>
		      <div class="entry portfolio-subtitle">
		        {{ portfolio.subtitle }}
	      </div>
	      </div>
	    </div>
	  {% endfor %}
</div>




