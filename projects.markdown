---
layout: page
lang: en
title: Projects
permalink: /projects/
---
# Projects sponsored by the AIEA

### Artsakh Online

The main goal of the *Artsakh online* project is to provide concise, expert-authored entries on topics related to Artsakh, from the ancient to the modern period. They will cover issues such as historical geography, linguistics, toponymy, history and art history (e.g. Gandzasar, Dadivank, Shushi, Melik, and so on).  They are openly accessible on the AIEA website in order to reach not only the scholarly community, but also a wider public, who often require precise information to help them find their way around scientific issues which have been the subject of much debate, especially in these last years.

<ol>
{% for article in site.artsakh %}
  <li>
    <a href="{{ article.url }}">{{ article.listtitle }}</a> - {{ article.author }}
  </li>
{% endfor %}
</ol>
