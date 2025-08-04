---
title: "Menaka Revel - News"
layout: textlay
excerpt: "Menaka Revel at UWaterloo"
sitemap: false
permalink: /allnews.html
---

# News
<!-- {% for article in site.data.news %}
<div>
  <strong>{{ article.date }}</strong><br>
  {{ article.headline | markdownify }}
  {% if article.description %}
    {{ article.description | markdownify }}
  {% endif %}
  <br>
</div>
{% endfor %} -->

<ul>
  {% for article in site.data.news %}
    <li>
      <strong>{{ article.date }}</strong> – {{ article.headline | markdownify }}
      {% if article.description %}
        <br>{{ article.description | markdownify }}
      {% endif %}
    </li>
    <br>
  {% endfor %}
</ul>
