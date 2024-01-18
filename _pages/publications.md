---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
header:
  overlay_image: https://paoe-dejili.github.io/assets/images/laura-ockel-qOx9KsvpqcM-unsplash.jpg
  caption: "Photo credit: [**UnsplashのLaura Ockelが撮影した写真**](https://unsplash.com/ja/%E5%86%99%E7%9C%9F/qOx9KsvpqcM)"
comments: false
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
