---
layout: default
---


<nav>
  {% for item in site.data.navigation %}
    <a href="{{ item.link }}" {% if page.url == item.link %}style="color: red;"{% endif %}>
      {{ item.name }}
    </a>
  {% endfor %}
</nav>

# Max
Hello World!


-----------------------


<div class="blog-index">  
  {% assign post = site.posts.first %}
  {% assign content = post.content %}
  {% include _post.md %}
</div>
