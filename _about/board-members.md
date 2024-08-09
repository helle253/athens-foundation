---
layout: page
title: Board Members
permalink: /about/board/
order: 1
---

Our board members are the people who make the decisions about the direction of the organization. They are the ones who decide what projects we will take on, what events we will host, and how we will spend our money. They are the ones who make sure that we are following our mission and that we are doing what we can to help the community.

{% for member in site.board_members -%}
  [![ {{ member.name }}](/assets/images/about/board-members/{{member.image_name}})]({{ member.url }})

  [{{ member.name }}]({{ member.url }})
{%- endfor -%}
