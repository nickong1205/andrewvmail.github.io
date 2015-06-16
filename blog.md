---
layout: default
title: Blog
permalink: /blog/
---

<div class="posts">
  {% for post in site.posts %}
    <article class="post">
      <h1 class="post-title">{{ post.title }}</h1>
      <h2 class="post-subtitle">{{ post.subtitle }}</h2>

       <img class="post-image" src="{{ post.image }}">

      <div class="post-entry">
        {{ post.excerpt }}
      </div>

      <div class="date">{{ post.date | date: "%B %e, %Y" }}</div>

      <!-- <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a> -->
      <div class="likes"><a href="{{ post.url }}#disqus_thread"></a>
    </article>
  {% endfor %}
</div>

<script type="text/javascript">
/* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
var disqus_shortname = 'nickmomo'; // required: replace example with your forum shortname

/* * * DON'T EDIT BELOW THIS LINE * * */
(function () {
    var s = document.createElement('script'); s.async = true;
    s.type = 'text/javascript';
    s.src = '//' + disqus_shortname + '.disqus.com/count.js';
    (document.getElementsByTagName('HEAD')[0] || document.getElementsByTagName('BODY')[0]).appendChild(s);
}());
</script>
