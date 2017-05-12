---
layout: page
title: Complexity guide
permalink: guide/
---

{% for guide in site.guide %}
  <div class="project-link">
    <a class="post-link" href="{{ guide.url | relative_url }}">
      {{ guide.title | escape }}
    </a>  
  </div>
{% endfor %}
