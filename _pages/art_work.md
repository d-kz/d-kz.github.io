---
layout: default
title: Art"work" 
home: 0
about: Sometimes work is literally art.. 
---

# {{page.title}}

{% for image in site.static_files %}
 {% if image.path contains 'images/artwork' %}
[{{ image.path }}]({{ site.baseurl }}{{ image.path }})
![{{ site.baseurl }}{{ image.path }}]({{ site.baseurl }}{{ image.path }})
 {% endif %}
{% endfor %}

