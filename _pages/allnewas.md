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
      <p>
        <strong>{{ article.date }}</strong><br>
        {{ article.headline | markdownify }}
        {% if article.description %}
          <br><em>{{ article.description }}</em>
        {% endif %}
      </p>
    </div>
  {% endfor %}
</div>

