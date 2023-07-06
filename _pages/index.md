---
layout: page
title: Tomás Brizuela
id: home
permalink: /
---

# Bienvenido! 

Cada semana, te envío un correo donde te cuento mis aprendizajes escribiendo en internet.

Y todos los secretos que aprendí creando audiencias y vendiendo productos y servicios.


Si querés recibir estos artículos, de forma semanal, sumate [**acá**](https://tomasbrizuela.crd.co/)



<p style="padding: 1em 1em; background: #F5F5F5; border-radius: 4px;">
 Si primero querés leer algún artículo, te recomiendo empezar por este -> <span style="font-weight: bold">[[Las dos manos]]</span>
</p>

<strong>O por los últimos artículos que publiqué:</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

---

<p style="padding: 1em 1em; background: #F5F5F5; border-radius: 4px;">
  Y acá vas a encontrar   <span style="font-weight: bold">[[Todos los artículos]]</span>
</p>



Espero que los disfrutes.





<style>
  .wrapper {
    max-width: 46em;
  }
</style>
