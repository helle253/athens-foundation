---
layout: page
title: Boardmembers
permalink: /about/board/
order: 1
---

{% for member in site.boardmembers -%}
  [![ {{ member.name }}](/assets/images/about/boardmembers/{{member.image_name}})]({{ member.url }})
  [{{ member.name }}]({{ member.url }})
{%- endfor -%}
