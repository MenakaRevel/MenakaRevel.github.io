---
title: "Menaka Revel - News"
layout: pagelay
sitemap: false
permalink: /allnews.html
---

# News
<div class="news-list">
  {% for article in site.data.news %}
    <div class="news-item" style="margin-bottom: 1.5em;">
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

