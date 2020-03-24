---
layout: page
title: Anagrafe e Stato Civile
permalink: /anagrafe/
---

<ul>

{% for argomento in site.anagrafe %}

  <li>
    <a href="{{argomento.url}}">{{argomento.title}}</a>
    </li>
{%endfor%}

</ul>
