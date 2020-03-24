---
layout: page
title: Cultura
permalink: /cultura/
---

<ul>

{% for argomento in site.cultura %}

  <li>
    <a href="{{argomento.url}}">{{argomento.title}}</a>
    </li>
{%endfor%}

</ul>
