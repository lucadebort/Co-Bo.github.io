---
layout: page
title: Lavoro e Formazione
permalink: /lavoro/
---

<ul>

{% for argomento in site.lavoro %}

  <li>
    <a href="{{argomento.url}}">{{argomento.title}}</a>
    </li>
{%endfor%}

</ul>
