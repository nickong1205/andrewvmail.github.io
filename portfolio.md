---
layout: default
title: Portfolio
permalink: /portfolio/
---

<div class="container portfolio">
	<div class="row">
	  {% for portfolio in site.portfolios %}
	    <div class="three columns portfolio-box">

	      <a href="{{ portfolio.url }}">
		      <img src="{{ portfolio.image }}">
	      	<h1>{{ portfolio.title }}</h1>
	      </a>

	      <div class="entry">
	        {{ portfolio.subtitle }}
	      </div>
	      
	    </div>
	  {% endfor %}
	</div>
</div>




