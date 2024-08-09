---
layout: page
title: Grant Award Listing
permalink: /grants/recipients/
order: 2
---

{% for recipient in site.recipients -%}
  [{{ recipient.name }}]({{ recipient.url }})
{%- endfor -%}
