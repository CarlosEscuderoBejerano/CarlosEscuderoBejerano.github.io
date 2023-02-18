---
title: Miembros tabla
permalink: /miembros tabla
---

# Aquie econtraras a todos los miembros

| Nombre | Edad | Sexo |
{% for persona in site.data.personas %}
  | {{ persona.nombre }} |  {{persona.edad }} | {{ persona.sexo }} |
{% endfor %}


