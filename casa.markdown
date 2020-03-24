---
layout: page
title: Casa
permalink: /casa/
---

<p>Ti trovi in: <b>{{page.title}}</b></p>
<ul>
  <li>  <a href="/">🏠Home</a></li>
  <li> {{page.title}} </li>
{% for argomento in site.casa %}

  <li>
    <a href="{{argomento.url}}">{{argomento.title}}</a>
    </li>
{%endfor%}

</ul>
