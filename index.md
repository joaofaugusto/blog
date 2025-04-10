---
layout: default
title: Início
---

# Bem-vindo

Verbalizando rascunhos mentais, projetos e ideias.

## Posts recentes

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%d/%m/%Y" }}</small>
    </li>
  {% endfor %}
</ul>
