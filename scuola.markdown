---
layout: page
title: Educazione e Scuola
permalink: /scuola/
---

<ul>

{% for argomento in site.scuola %}

  <li>
    <a href="{{argomento.url}}">{{argomento.title}}</a>
    </li>
{%endfor%}

</ul>
