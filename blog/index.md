---
layout: default
permalink: /blog/
title: "Bisect Blog"
---

<!-- App name and description -->
<div class="app-h1">
  <a href="/">bisect</a>
</div>

<div class="main-container">
<article>
<div class="post-index-container">

  {% for page in site.posts limit:5 %}

<div class="blog-post">
<h1><a href="{{ page.url }}">{{ page.title }}</a></h1>
<p>
  <span class="post-date"><time datetime="{{ page.date | date_to_xmlschema }}" itemprop="datePublished">{{ page.date | date: "%B&nbsp;%d,&nbsp;%Y" }}</time>{% if page.modified %} (Modified <time datetime="{{ page.modified | date: "%Y-%m-%d" }}" itemprop="dateModified">{{ page.modified | date: "%B&nbsp;%d,&nbsp;%Y" }}</time>){% endif %}</span>
</p>

{{ page.content }}

</div>

  <hr />
  {% endfor %}

  <div style="height: 3em;"></div>

</div>

</article>
</div>

<!-- Footer -->
<div class="gray-box footer-box">
<span class="tiny">
Bisect is being <span class="emph">Made in India</span>
by <span class="emph"><a href="http://roopc.net/">Roopesh Chander</a></span>
</span>
</div>
