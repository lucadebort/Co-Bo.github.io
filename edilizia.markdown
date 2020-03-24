---
layout: page
title: Edilizia e Lavori Pubblici
permalink: /edilizia/
---

<ul>

{% for argomento in site.edilizia %}

  <li>
    <a href="{{argomento.url}}">{{argomento.title}}</a>
    </li>
{%endfor%}

</ul>
