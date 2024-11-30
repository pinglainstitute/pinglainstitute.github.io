---
title: "Pingla Institute - Blog"
layout: gridlay
excerpt: "Pingla Institute -- Blog."
sitemap: false
permalink: /news/
---

# Latest News

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.summary }}</p>
{% endfor %}

<br/>
<br/>
<br/>
<br/>
Follow us on <a href='https://www.linkedin.com/company/pinglainstitute/'>LinkedIn</a> or <a href='https://www.facebook.com/pinglainstitute'>Facebook</a> for more.
<br/>
<br/>
<br/>
