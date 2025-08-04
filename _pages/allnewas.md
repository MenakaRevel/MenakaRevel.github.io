---
title: "Menaka Revel - News"
layout: textlay
excerpt: "Menaka Revel at UWaterloo"
sitemap: false
permalink: /allnews/
---

# News
{% for article in site.data.news %}
<div>
  <strong>{{ article.date }}</strong><br>
  {{ article.headline | markdownify }}
  {% if article.description %}
    <br><em>{{ article.description | markdownify }}</em>
  {% endif %}
  <br><br>
</div>
{% endfor %}