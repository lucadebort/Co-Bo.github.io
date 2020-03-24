---
layout: page
title: Welfare e benessere sociale
permalink: /sociale/
---

<ul>

{% for argomento in site.sociale %}

  <li>
    <a href="{{argomento.url}}">{{argomento.title}}</a>
    </li>
{%endfor%}

</ul>
