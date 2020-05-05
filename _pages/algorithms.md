---
layout: archive
permalink: /alg/
title: "Posts related to algorithms, data strucutures and problem solving"
author_profile: true
---

 {% for post in site.posts %}
   {% if post.categories contains 'algorithms' %}
    {% include archive-single.html %}
   {% endif %}
{% endfor %}