---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

Below is a list and a short description of the academic courses I've tought in the past. 

A PDF containing my teaching portfolio as of January 2021 is available at __[http://kasperschmidt.github.io/files/Schmidt_teaching_portfolio.pdf](http://kasperschmidt.github.io/files/Schmidt_teaching_portfolio.pdf)__


{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
