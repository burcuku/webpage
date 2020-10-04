---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

My research aims to improve the reliability of software by building program analysis, testing and verification techniques. As software systems have become ubiquitous in our lives, modern applications are designed to be highly concurrent, responsive, fault tolerant and distributed. Increased complexity of the software systems makes it more difficult to reason about possible behaviors of a system and to produce correct software. 

My goal is to advance the state of the art of software reliability techniques for modern programming models and software systems. To this end, my research spans software engineering, formal methods, programming models and languages, concurrent programming, and distributed systems.


## Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
