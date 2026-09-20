---
layout: page
title: Invited speakers
subtitle: The invited lectures of TYPES 2027.
---

{%- assign invited = site.data.invited -%}

{% if invited.size > 0 %}
<ul class="cards">
{%- for entry in invited %}
  {%- assign s = entry[1] %}
  <li>
    <h3>{% if s.homepage %}<a href="{{ s.homepage }}">{{ s.first }} {{ s.last }}</a>{% else %}{{ s.first }} {{ s.last }}{% endif %}</h3>
    <p class="note">{{ s.affiliation }}</p>
    {%- if s.title %}<p><strong>{{ s.title }}</strong></p>{% endif %}
  </li>
{%- endfor %}
</ul>
{% else %}
<div class="callout callout--tba">
  <p><span class="tba">to be announced</span></p>
  <p>The invited speakers will be announced well before the abstract submission
  deadline.</p>
</div>
{% endif %}
