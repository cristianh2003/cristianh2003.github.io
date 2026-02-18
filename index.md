---
layout: default
title: Inicio
---

<h1>Bienvenido a mi  Blog personal</h1>
<p>Aquí publicaré temas de interes sobre Tecnología, Software, Hardware, etc.</p>

<hr>

<h2>Artículos Recientes:</h2>

<ul>
  {% for post in site.posts %}
    <li>
      <span style="font-size: 0.8em; color: #666;">{{ post.date | date: "%Y-%m-%d" }}</span>
      <h3>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </h3>
      <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
    </li>
  {% endfor %}
</ul>