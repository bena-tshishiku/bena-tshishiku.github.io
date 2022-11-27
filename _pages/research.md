---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---


My research area is geometric topology. Some of my interests include low-dimensional topology; manifolds, fiber bundles, and their characteristic classes; mapping class groups, diffeomorphism groups, and arithmetic groups. 

Collaborators: Mauricio Bustamante, Lei Chen, Jeffrey Giansiracusa, Junzhi Huang, Manuel Krannich, Alexander Kupers, Jean-Francois Lafont, Kathryn Mann, Nick Salter, Daniel Studenmund, Genevieve Walsh



## Research articles

Note: frequently the version on this page is more up-to-date than the version on the arXiv.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


## Other articles

{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.paperurl == 'exposition' %} 
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
