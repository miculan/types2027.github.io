---
layout: page
title: Registration
subtitle: Fees, deadlines and what registration includes.
---

{% assign early = site.data.dates | where: "id", "early-registration" | first %}
{% assign late = site.data.dates | where: "id", "late-registration" | first %}

<div class="callout callout--tba">
  <p><span class="tba">to be announced</span></p>
  <p>Registration opens in early 2027. Fees and the registration link will be
  published on this page.</p>
</div>

## Deadlines

| Event | Date |
| --- | --- |
| {{ early.event }} | {{ early.human }} |
| {{ late.event }} | {{ late.human }} |

At least one author of each accepted abstract is expected to register and
present the contribution in Udine. Participation is open to everybody working
on or interested in type theory, whether or not they contribute a talk.

## Fees

<div class="callout callout--tba">
  <p><span class="tba">to be announced</span></p>
  <p>The fee structure — regular, student, and any accompanying-person rate —
  will be published here when registration opens.</p>
</div>

## What registration includes

Registration is expected to cover attendance at all sessions, the book of
abstracts, coffee breaks and lunches, the social event and the conference
dinner. The exact list will be confirmed when registration opens.

## Visa

Italy is part of the Schengen area. Participants who need a visa should start
the application early; on request, the organisers issue an invitation letter for
registered participants. Write to
<a href="mailto:{{ site.conference.email }}">{{ site.conference.email }}</a>
with your name as it appears in your passport, your affiliation and, if
applicable, the title of your accepted contribution.
