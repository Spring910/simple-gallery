---
title: Gallery index
layout: index
---

{% for exhibit in site.exhibits %}

<p> {{ exhibit.title }} by {{ exhibit.creator }}</p>
<p> {{ exhibit.licence }}

{% endfor %}