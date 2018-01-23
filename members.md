---
layout: page
title: Members 
ref: members/
lang: en
---

{% assign sortedPerson=site.data.people | sort %}
{% for p in sortedPerson %}
{% assign person=p[1] %}

<div class="row">
	<div class="col-md-auto"> <img class="img-circle" src="{{site.baseurl}}/assets/{{person.pictureFileStem}}.jpg" width="50"> </div>
		<div class="col-md-auto"> <a href="{{person.url}}"> <strong>{{person.Name}}</strong></a> </div> 
		<div class="col-md-auto">{{person.Affiliation}}</div>
		<div class="col-md-auto">{{person.Profile}}</div>
	</div>
	{% endfor %}



## Future members
If you are interested in being part of our research group, send us an email with your CV and your research interests.

