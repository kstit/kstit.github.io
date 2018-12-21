---
layout: default
title: Komitety
index: 2
column: 1
---

##### Przewodniczący KSTiT 2019

Tadeusz Więckowski – Politechnika Wrocławska



##### Komitet Sterujący

{% for person in site.data.steering %}
- {{person.name}}, <em>{{person.affiliation}}</em>
{% endfor %}


##### Komitet Programowy

{% for person in site.data.program %}
- {{person.name}}, <em>{{person.affiliation}}</em>
{% endfor %}


##### Komitet Organizacyjny

{% for person in site.data.organizers %}
{{person.name}},{% endfor %}
