---
layout: default
---

# Max
Hello World!


-----------------------


<div class="blog-index">  
  {% assign post = site.posts.first %}
  {% assign content = post.content %}
  {% include _post.md %}
</div>
