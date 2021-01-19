---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

Below I have listed a short description of the courses I've been teaching resently with links to the respective course sites. 

A PDF containing my teaching portfolio is available at __[http://kasperschmidt.github.io/files/Schmidt_teaching_portfolio.pdf](http://kasperschmidt.github.io/files/Schmidt_teaching_portfolio.pdf)__


{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
