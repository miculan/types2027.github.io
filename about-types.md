---
layout: page
title: About TYPES
subtitle: The conference series, from the EU networks of 1990 to the 33rd edition.
---

[The TYPES meetings](https://sites.google.com/view/thetypesconferences) are a forum to present new and ongoing work in all
aspects of type theory and its applications, especially in formalised and computer assisted
reasoning and computer programming. Participation is open to everybody working
on or interested in these topics, whether or not they contribute a talk.

## From network workshops to a conference series

The TYPES meetings from 1990 to 2008 were annual workshops of a sequence of five
EU-funded networking projects. From 2009 onwards, TYPES has been run as an
independent conference series.

The character of those early workshops has survived the change of format. TYPES
remains a working meeting rather than a showcase: contributions are selected on
a two-page abstract, work in progress is as welcome as finished results, and the
programme leaves room for discussion.

In recent editions the conference has been followed by an open call for full
papers, published in the Leibniz International Proceedings in Informatics
(LIPIcs) series and reviewed to the standards of a journal publication.

## Previous editions

The series has met thirty-two times, which makes Udine the thirty-third edition. Previous editions has been: {% assign chrono = site.data.editions | reverse %}
{% for e in chrono %}{% if e.url %}<a href="{{ e.url }}"{% if e.archived %} title="Internet Archive snapshot"{% endif %}>{{ e.city }}</a>{% else %}{{ e.city }}{% endif %} ({{ e.year }}{% if e.note %}, {{ e.note }}{% endif %}){% unless forloop.last %}, {% endunless %}{% endfor %}.

<p class="note">The series keeps its own record of past meetings on the
<a href="https://sites.google.com/view/thetypesconferences">TYPES conferences site</a>.
Where an edition's own website has gone, the link here points to an
Internet Archive snapshot. The meetings from 1990 to 1996, and the one in
Durham in 2000, have no website on record — if you know of one, please
<a href="{{ '/practical/#contact' | relative_url }}">tell us</a>.</p>

## TYPES in Friuli

This is not the first time the series comes to this corner of Italy. The 2007
edition was held in **Cividale del Friuli**, close to Udine. Torino has hosted the meeting three times, in 1995, 2003 and 2008.

Cividale is worth the short trip during the conference week too — see the
[practical information]({{ '/practical/#venue' | relative_url }}).
