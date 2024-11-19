---
title: "Pingla Institute - Projects"
layout: textlay
excerpt: "Research Projects"
sitemap: false
permalink: /vacancies
---

## Research programme

The Pingla Institute offers unique opportunities for researchers and interns to contribute to groundbreaking studies, participate in workshops, and engage in interdisciplinary collaborations. 

We are open to externally supervising HDR PhD/Masters/Honours students 
in our group provided you can fund your study programme. 
Below are some of the research directions and topics that can be pursued:

## Potential thesis topics

<ul style="list-style-type:disc;">
{% for proj in site.data.projects %}
  <li>
  <b>{{ proj.title }}</b><br/>
  {{ proj.description }} 
  </li>
{% endfor %} 
</ul>


<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/ideas.jpeg" width="95%">
</figure>
