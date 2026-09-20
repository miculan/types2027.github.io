---
layout: page
title: Organisation
subtitle: The people behind TYPES 2027.
---

TYPES 2027 is organised by the Department of Mathematics, Computer Science and
Physics of the **University of Udine**, under the auspices of the TYPES
conference series.

{% assign groups = "organising,programme,steering" | split: "," %}
{% for key in groups %}
  {% assign g = site.data.committees[key] %}
  {% if g %}
## {{ g.title }}

{% if g.note %}{{ g.note }}{% endif %}

{% if g.members and g.members.size > 0 %}
<ul class="plain">
  {% for m in g.members %}
  <li>
    {% capture who %}{{ m.first }} {{ m.last }}{% endcapture -%}
    {% if m.homepage %}<a href="{{ m.homepage }}">{{ who }}</a>{% else %}{{ who }}{% endif %}
    {% if m.affiliation %}<span class="note">({{ m.affiliation }})</span>{% endif %}
    {% if m.role %} — {{ m.role }}{% endif %}
  </li>
  {% endfor %}
</ul>
{% else %}
<div class="callout callout--tba">
  <p><span class="tba">to be announced</span></p>
</div>
{% endif %}
  {% endif %}
{% endfor %}

## The conference series

The TYPES meetings started in 1990 as workshops of a sequence of EU-funded
networking projects, and have run as an independent conference series since 2009.
Udine is the thirty-third edition; the previous thirty-two are listed on the
[About TYPES]({{ '/about-types/' | relative_url }}) page.
