---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

{% include base_path %}

Patents
======
  {% for post in site.patents %}
    {% include archive-single.html %}
  {% endfor %}
  
Publications
======
  {% assign sorted = site.publications | sort: 'order' %}
  {% for post in sorted %}
    {% include archive-single.html %}
  {% endfor %}
