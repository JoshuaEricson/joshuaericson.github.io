---
layout: default
permalink: /
---

{% include landing.html %}

<div class="wow animated slideInUp m-3 pb-1" data-wow-delay=".15s">
  <h1>Projects</h1>
  {% include projects/index.html %}
</div>

<div class="wow animated slideInUp m-3 pt-3" data-wow-delay=".15s">
  <h1>Blog</h1>
  {% include blog/search.html %}
  {% include blog/index.html %}
</div>