---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---


My research area is geometric topology. Some of my interests include low-dimensional topology; manifolds, fiber bundles, and characteristic classes; group actions and Nielsen realization; mapping class groups, diffeomorphism groups, and arithmetic groups. 

Collaborators: Alina al Beaini, [Mauricio Bustamante](https://bustamantemath.wixsite.com/math), [Lei Chen](https://sites.google.com/site/alicemath1991/home), [Jeffrey Giansiracusa](https://sites.google.com/view/jeffreygiansiracusa/home?authuser=0), [Junzhi Huang](https://sites.google.com/yale.edu/junzhihuang/home), [Manuel Krannich](https://manuelkrannich.github.io/), [Alexander Kupers](https://www.utsc.utoronto.ca/people/kupers/), [Jean-Francois Lafont](https://people.math.osu.edu/lafont.1/), [Kathryn Mann](https://e.math.cornell.edu/people/mann/index.html), [Nick Salter](https://nsalter.science.nd.edu/), [Daniel Studenmund](https://sites.google.com/view/studenmund/home), [Genevieve Walsh](https://gwalsh01.pages.tufts.edu/)



## Research articles

Note: frequently the version on this page is more up-to-date than the version on the arXiv.

{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.paperurl != 'exposition' %} 
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Other articles


{% for post in site.publications reversed %}
  {% if post.paperurl == 'exposition' %} 
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


## Notes 

Local coefficients and Poincare duality [pdf](http://bena-tshishiku.github.io/files/papers/Poincare-duality-local-coefficients.pdf)
