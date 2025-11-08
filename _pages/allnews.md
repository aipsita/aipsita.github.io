---
title: "News"
layout: textlay
sitemap: false
permalink: /allnews.html
---

## News

<div class="jumbotron">
{% for article in site.data.news %}
<b>{{ article.date }}</b>: <strong>{{ article.title }}</strong><br>
{{ article.description }}<br><br>
{% endfor %}

</div>
