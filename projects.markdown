---
layout: page
lang: en
title: Projects
permalink: /projects/
---
<h1>Projects sponsored by the AIEA</h1>

<h2>Artsakh Online</h2>

<p>TODO get text from Valentina</p>

<ol>
{% for article in site.artsakh %}
  <li>
    <a href="{{ article.url }}">{{ article.listtitle }}</a> - {{ article.author }}
  </li>
{% endfor %}
</ol>