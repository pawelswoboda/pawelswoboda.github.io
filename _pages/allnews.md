---
title: "Home"
layout: textlay
excerpt: "Paul Swoboda at Max Planck Institute for Informatics."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
