---
layout: page
title: Miembros 
ref: members/
lang: es
---

{% for p in site.data.people %}
{% assign person=p[1] %}
<div class="row">
	<div class="col-md-2"> <img class="img-circle" src="{{site.baseurl}}/assets/{{person.pictureFileStem}}.jpg" width="50"> </div>
		<div class="col-md-3"> <a href="{{person.url}}"> <strong>{{person.Name}}</strong></a> </div> 
		<div class="col-md-4">{{person.Affiliation}}</div>

	</div>
	{% endfor %}



## Futuros miembros
Si están insteresados en unirse a esta iniciativa, contáctenos mediante correo electrónico.

