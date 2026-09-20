---
layout: page
title: Submission
subtitle: How to prepare and submit a two-page abstract.
---

{%- assign abstract_deadline = site.data.dates | where: "id", "abstract" | first -%}

## What to submit

A contribution to TYPES 2027 is an **extended abstract of at most two pages**,
including references. The abstract should make clear what the contribution is,
why it is of interest to the TYPES community, and what the author intends to
present in the talk.

Abstracts are reviewed by the programme committee. Selection is based on
relevance to the scope of the conference and on the quality of the abstract;
the review process is light-touch, in keeping with the character of the TYPES
meetings as a working conference.

## Format

Abstracts must be prepared with the conference style file and submitted in PDF.

<div class="callout callout--tba">
  <p><span class="tba">to be announced</span></p>
  <p>The LaTeX style file and a template will be linked here once the
  submission system opens.</p>
</div>

## Where to submit

Submission is handled through a **HotCRP** instance set up for the conference.

<div class="callout callout--tba">
  <p><span class="tba">to be announced</span></p>
  <p>The address of the submission site will be published here well before the
  deadline of {{ abstract_deadline.human }}.</p>
</div>

Each HotCRP installation keeps its own accounts: an account on the site of
another conference does not carry over, so authors will need to register on the
TYPES 2027 instance before submitting. Abstracts can be revised on the
submission site up to the deadline.

## Deadlines

{% include dates.html %}

## After acceptance

At least one author of each accepted abstract is expected to
[register]({{ '/registration/' | relative_url }}) and to present the
contribution in Udine. Accepted abstracts are collected in a book of abstracts
distributed to participants and published on this website.

A separate call for full papers for the
[post-proceedings]({{ '/call-for-contributions/#post-proceedings' | relative_url }})
is expected to open after the conference.

## Questions

Write to <a href="mailto:{{ site.conference.email }}">{{ site.conference.email }}</a>.
