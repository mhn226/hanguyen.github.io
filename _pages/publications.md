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
  {% if post.year == '2019'  %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


### 2020

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
