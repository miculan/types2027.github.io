---
layout: page
title: Call for contributions
subtitle: Two-page abstracts on all aspects of type theory and its applications.
---

{%- assign abstract_deadline = site.data.dates | where: "id", "abstract" | first -%}

TYPES 2027, the 33rd International Conference on Types for Proofs and Programs,
invites contributions on all aspects of type theory and its applications. The
conference takes place in Udine, Italy, on 7-11 June 2027.

## Scope

The TYPES meetings are a forum to present new and ongoing work in all aspects of
type theory and its applications, especially in formalised and computer assisted
reasoning and computer programming. Topics include, but are not limited to:

- foundations of type theory and constructive mathematics;
- applications of type theory;
- dependently typed programming;
- industrial uses of type theory technology;
- meta-theoretic studies of type systems;
- proof assistants and proof technology;
- automation in computer-assisted reasoning;
- links between type theory and functional programming;
- formalising mathematics using type theory;
- homotopy type theory and univalent foundations.

Participation is open to everybody working on or interested in these topics,
whether or not they contribute a talk.

## Contributed talks

Presentations are selected on the basis of an extended abstract of **at most two
pages**, references included. Submitted abstracts are reviewed by the programme
committee for relevance and quality; work in progress, work already presented
elsewhere and overviews of larger projects are all in scope, as long as they are
of interest to the TYPES community.

Full details are in the [submission section](#submission) below.

## Invited speakers

<div class="callout callout--tba">
  <p><span class="tba">to be announced</span></p>
  <p>The invited speakers will be announced here well before the abstract
  submission deadline.</p>
</div>

## Post-proceedings

As in recent editions of the conference series, we intend to publish
post-proceedings in the [Leibniz International Proceedings in Informatics
(LIPIcs)](https://www.dagstuhl.de/en/publications/lipics) series. The call for
papers is expected to open after the conference and to be open to all
participants, not only to those who presented a talk. Submissions are full
papers, reviewed to the standards of a journal publication.

<div class="callout">
  <p>Publication details, including page limits and the exact timeline, will be
  confirmed on this page. <span class="tba">to be confirmed</span></p>
</div>

## Submission

### What to submit

A contribution to TYPES 2027 is an **extended abstract of at most two pages**,
including references. The abstract should make clear what the contribution is,
why it is of interest to the TYPES community, and what the author intends to
present in the talk.

Abstracts are reviewed by the programme committee. Selection is based on
relevance to the scope of the conference and on the quality of the abstract;
the review process is light-touch, in keeping with the character of the TYPES
meetings as a working conference.

### Format

Abstracts must be prepared with the conference style file and submitted in PDF.

<div class="callout callout--tba">
  <p><span class="tba">to be announced</span></p>
  <p>The LaTeX style file and a template will be linked here once the
  submission system opens.</p>
</div>

### Where to submit

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

### After acceptance

At least one author of each accepted abstract is expected to
[register]({{ '/registration/' | relative_url }}) and to present the
contribution in Udine. Accepted abstracts are collected in a book of abstracts
distributed to participants and published on this website.

A separate call for full papers for the
[post-proceedings]({{ '/call-for-contributions/#post-proceedings' | relative_url }})
is expected to open after the conference.


## Important dates

{% include dates.html %}
