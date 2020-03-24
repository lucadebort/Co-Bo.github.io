---
layout: page
title: Casa
permalink: /casa/
---

<ul>
  <li>  <a href="/">🏠Home</a></li>
  <li> {{page.title}} </li>
{% for argomento in site.casa %}

  <li>
    <a href="{{argomento.url}}">{{argomento.title}}</a>
    </li>
{%endfor%}

</ul>
