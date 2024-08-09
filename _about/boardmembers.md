---
layout: page
title: Boardmembers
permalink: /about/board/
order: 1
---

{% for member in site.boardmembers -%}
  [![ {{ member.name }}]({{site.baseurl}}/assets/about/boardmembers/{{member.image_name}})]({{ site.baseurl }}/{{ member.url }})

  [{{ member.name }}]({{ member.url }})
{%- endfor -%}
