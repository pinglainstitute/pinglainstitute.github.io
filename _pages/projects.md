---
title: "Pingla Institute - Projects"
layout: textlay
excerpt: "Research Projects"
sitemap: false
permalink: /projects
---

## Research programme

The Pingla Institute offers unique opportunities for researchers and interns 
to contribute to groundbreaking studies, participate in workshops, and engage 
in interdisciplinary collaborations. 

We are open to externally supervising HDR PhD/Masters/Honours students 
in our group provided you can fund your study programme. 
Below are some of the research directions and topics that can be pursued:

### Projects

{% for proj in site.data.projects %}
  <h4>{{ proj.title }}</h4>
  <b>Team: {{ proj.team}}</b><br/>
  {{ proj.description }} 
  <br/>
  <br/>
{% endfor %} 

<br/>
<br/>
<br/>
Please apply for a Research Internship.
<br/>
<br/>
<br/>
