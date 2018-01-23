---
layout: page
title: Miembros 
ref: members/
lang: es
---

{% assign sortedPerson=site.data.people | sort %}
{% for p in sortedPerson %}
{% assign person=p[1] %}
<div class="row">
	<div class="col-md-auto"> <img class="img-circle" src="{{site.baseurl}}/assets/{{person.pictureFileStem}}.jpg" width="50"> </div>
		<div class="col-md-auto"> <a href="{{person.url}}"> <strong>{{person.Name}}</strong></a> </div> 
		<div class="col-md-auto">{{person.Affiliation}}</div>
		<div class="col-md-auto" width="100">{{person.Perfil}}</div>

	</div>
	{% endfor %}



## Futuros miembros
Si están insteresados en unirse a esta iniciativa, contáctenos mediante correo electrónico.

