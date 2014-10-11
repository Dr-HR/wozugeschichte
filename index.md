---
layout: page
title: Gastprof. Dr. Hazel Rosenstrauch
tagline: WS 2014/15
---
{% include JB/setup %}
<div id="home">
  <h2>APPetithappen</h2>
<ul class="posts">
  {% for post in site.posts %}
    <li class='col-md-6'>
      <a href="{{ BASE_PATH }}{{ post.url }}">
        <article>
          <h3>{{ post.title }}</h3>

          <br /> {% if post.tagline %} <p>{{ post.tagline }}</p>{% endif %}
          <br />
          <span class="category">{{ post.category }}  </span>
          <hr />
        </article>
      </a>
    </li>
  {% endfor %}
</ul>

</div>
