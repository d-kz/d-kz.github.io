---
layout: default
title: Photography Portfolio
home: 0
about: Favourite photos in high resolution. 
---

# {{page.title}}

{% for image in site.static_files %}
 {% if image.path contains 'images/portfolio' %}
[{{ image.path }}]({{ site.baseurl }}{{ image.path }})
![{{ site.baseurl }}{{ image.path }}]({{ site.baseurl }}{{ image.path }})
 {% endif %}
{% endfor %}

