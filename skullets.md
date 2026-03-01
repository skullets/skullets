---
layout: page
title: Comics
permalink: /skullets/
---

{% for post in site.skullets reversed %}
  <div style="margin-bottom:40px;">
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <img src="{{ post.image }}" style="max-width:600px;border-radius:10px;">
  </div>
{% endfor %}
