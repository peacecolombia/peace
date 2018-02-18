---
layout: page
title: Press 
ref: press
lang: en
---

## News papers and press releases

{% for article in site.data.articles %}
 <a href="{{ article.url}}"> {{article.title}}  </a>
 <p> Published by {{article.source}}, {{ article.date | date: "%B %-d, %Y" }} </p>
 <hr>
{% endfor %}

## Scientific publications

{% bibliography %}

