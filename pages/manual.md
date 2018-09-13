---
title: Руководство
layout: page
---
<ul>
{% for manpage in site.manual %}
<li><a href="{{ manpage.url }}">{{ manpage.title }}</a></li>
{% endfor %}
</ul>
