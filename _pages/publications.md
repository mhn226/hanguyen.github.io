---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


### 2019

{% for post in site.publications % }
  {% post --query @*[year=2019] %}
{% endfor %}


### 2020

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
