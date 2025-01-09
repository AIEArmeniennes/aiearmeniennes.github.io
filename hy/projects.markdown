---
layout: page
lang: en
title: Projects
permalink: /projects/
---

# Projects sponsored by the AIEA

## Artsakh Online

TODO get text from Valentina

<ol>
{% for article in site.artsakh %}
  <li>
    <a href="{{ article.url }}">{{ article.title }}</a> - {{ article.author }}
  </li>
{% endfor %}
</ol>