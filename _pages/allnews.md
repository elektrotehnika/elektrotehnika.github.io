---
title: "News"
layout: textlay
excerpt: "Center for Integrated Systems (CIS) at University of Kragujevac."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br> {{ article.headline | markdownify}}</p>
{% endfor %}
