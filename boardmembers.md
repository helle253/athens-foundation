---
layout: page
title: Boardmembers
permalink: /board/
order: 1
---

{% for member in site.boardmembers -%}
  [{{ member.name }}]({{ member.url }})
{%- endfor -%}
