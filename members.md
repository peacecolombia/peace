---
layout: page
title: Members 
ref: members/
lang: en
---

{% assign members = site.data.miembros | sort: 'Name' %}

{% for person in members %}
<div class="row">
	<div class="col-md-auto"> <img class="img-circle" src="{{site.baseurl}}/assets/{{person.pictureFileStem}}.jpg" width="50"> </div>
		<div class="col-md-auto"> <a href="{{person.url}}"> <strong>{{person.Name}}</strong></a> </div> 
		<div class="col-md-auto">{{person.Affiliation}}</div>
	</div>
{% endfor %}



## Future members
If you are interested in being part of this initiative, please contact any of the current members.

