---
layout: page
lang: fr
title: Artsakh en ligne
permalink: /projects/
---

L'objectif principal du projet *Artsakh online* est de fournir des articles concis, rédigés par des experts, sur des sujets liés à l'Artsakh, de la période ancienne à la période moderne. Elles couvriront des questions telles que la géographie historique, la linguistique, la toponymie, l'histoire et l'histoire de l'art (par exemple Gandzasar, Dadivank, Shushi, Melik, etc.).  Elles sont accessibles sur le site web de l'AIEA afin d'atteindre non seulement la communauté scientifique, mais aussi un public plus large, qui est souvent demandeur d'informations précises pour s'orienter dans des questions scientifiques qui ont fait l'objet de nombreux débats, en particulier ces dernières années.

<ol>
{% for article in site.artsakh %}
  <li>
    <a href="{{ article.url }}">{{ article.listtitle }}</a> - {{ article.author }}
  </li>
{% endfor %}
</ol>
