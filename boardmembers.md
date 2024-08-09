---
layout: page
title: Boardmembers
permalink: /board/
order: 1
---

{% for member in site.boardmembers -%}
  [![ {{ member.name }} ](/assets/boardmembers/{{member.image_name}})]({{ member.url }})

  [{{ member.name }}]({{ member.url }})
{%- endfor -%}
