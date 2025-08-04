---
title: "Menaka Revel - News"
layout: textlay
excerpt: "Menaka Revel at UWaterloo"
sitemap: false
permalink: /allnews.html
---

# News
{% for article in site.data.news %}
<div>
  <strong>{{ article.date }}</strong><br>
  {{ article.headline | markdownify }}
  {% if article.description %}
    {{ article.description | markdownify }}
  {% endif %}
  <br>
</div>
{% endfor %}