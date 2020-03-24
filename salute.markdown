---
layout: page
title: Salute
permalink: /salute/
---

<ul>

{% for argomento in site.salute %}

  <li>
    <a href="{{argomento.url}}">{{argomento.title}}</a>
    </li>
{%endfor%}

</ul>
