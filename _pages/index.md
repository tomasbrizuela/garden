---
layout: page
title: Tomás Brizuela
id: home
permalink: /
---

# Bienvenido! 

Correos semanales donde te cuento mis aprendizajes escribiendo en internet para crear audiencias y vender productos y servicios.

<p style="padding: 1em 1em; background: #F5F5F5; border-radius: 4px;">
  Si querés ver la lista completa de artículos, entrá  <span style="font-weight: bold">[[Todos los artículos]]</span>
</p>

<p style="padding: 1em 1em; background: #F5F5F5; border-radius: 4px;">
  Te recomiendo empezar por acá <span style="font-weight: bold">[[Las dos manos]]</span>
</p>

<strong>Últimos artículos</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

---



Espero que los disfrutes.

Si querés recibir estos artículos de forma semanal, sumate [**acá**](https://tomasbrizuela.crd.co/)



<style>
  .wrapper {
    max-width: 46em;
  }
</style>
