---
layout: page
title: Accepted talks
subtitle: The contributions accepted for presentation in Udine.
---

{%- assign papers = site.data.papers -%}
{%- assign notification = site.data.dates | where: "id", "notification" | first -%}

{% if papers.size > 0 %}
The following contributions have been accepted for TYPES 2027.

<ul class="plain">
{%- for p in papers %}
  <li>
    <strong>{{ p.title }}</strong><br>
    {% for a in p.authors %}{{ a.first }} {{ a.last }}{% unless forloop.last %}, {% endunless %}{% endfor %}
  </li>
{%- endfor %}
</ul>
{% else %}
<div class="callout callout--tba">
  <p><span class="tba">to be announced</span></p>
  <p>The list is published after the author notification of
  {{ notification.human }}. It is generated from the submission system, so it
  appears here as soon as the decisions are exported.</p>
</div>
{% endif %}
