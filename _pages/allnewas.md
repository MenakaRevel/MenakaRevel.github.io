---
title: "Menaka Revel - News"
layout: textlay
sitemap: false
permalink: /allnews.html
---

# News
<div>
  {% for article in site.data.news %}
    <div>
        <strong>{{ article.date }}</strong><br>
        {{ article.headline }} <!-- | markdownify }} -->
        {% if article.description %}
          {{ article.description }}
        {% endif %}
    </div>
  {% endfor %}
</div>

