---
layout: page
title: Gastprof. Dr. Hazel Rosenstrauch
tagline: WS 2014/15
---
{% include JB/setup %}
<div id="home">
  <h1>APPetithappen</h1>
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; {{ post.category }} &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

</div>
