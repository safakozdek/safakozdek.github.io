---
layout : archive
title : "Blog"
excerpt : "Some blog posts related to my area of interests."
author_profile: true
permalink : /blog/

# header:
#  image: /assets/images/blogimg/head.jpg
#  caption: March 2016, Mt. Kinabalu, Borneo
#feature_row:
#  - image_path: assets/images/blogimg/nyc365.gif
#    title: "365 Days of NYC"
#    url: nyc365blog
#    excerpt: Every day input from NYC
---

{% for post in site.posts %}
  {% if post.categories contains 'blog' %}
   {% include archive-single.html %}
  {% endif %}
{% endfor %}
