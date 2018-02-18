---
layout: page
title: Prensa 
ref: press
lang: es
---

## Periodicos y comunicados de prensa

{% for article in site.data.articles %}
 <a href="{{ article.url}}"> {{article.title}}  </a>
 <p> Publicado por {{article.source}}, {{ article.date | date: "%m/%d/%Y" }} </p>
 <hr>
{% endfor %}

## Publicaciones científicas

{% bibliography %}

