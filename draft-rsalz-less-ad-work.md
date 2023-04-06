---
###
# Internet-Draft Markdown Template
#
# This template uses kramdown-rfc: https://github.com/cabo/kramdown-rfc
# You can replace the entire file if you prefer a different format.
# Change the file extension to match the format (.xml for XML, etc...)
#
###
title: "Making Less work for Area Directors"
category: bcp

docname: draft-rsalz-less-ad-work-latest
submissiontype: IETF  # also: "independent", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: gen
workgroup: WG Working Group
keyword:
 - IESG
venue:
  group: GENDISPATCH
  type: Working Group
  mail: gendispatch@ietf.org
  arch: https://example.com/WG
  github: rsalz/ietf-less-ad-work

author:
 -
    fullname: Rich Salz
    organization: Akamai Technologies
    email: rsalz@akamai.com

normative:

informative:
  FORBES:
    target: https://www.forbes.com/lists/global2000/?sh=3d73be235ac0
    title: The Global 2000
    author:
    - org: Forbes Magazine
    date: 2022
  RFC8718:



--- abstract

This draft proposes a number of ways that the Area Director workload can
be reduced. It will be up to the IETF consensus process to set the final
list.

A major goal of this effort is to make it feasible for a wider diversity
of people to volunteer as a candidate for AD. Anecdotally, every IESG
complains about the AD workload, and says that it takes the first
full term to understand the job.


--- middle

# Introduction

Repeat the abstract.

# Conventions and Definitions

{::boilerplate bcp14-tagged}

# History of IESG Job Descriptions

It might be useful to look at the job descriptions that the IESG provided to
NomCom over the years.

In 2016, the description said

> The basic IESG activities can consume between 15-40 hours a week.

In 2017, this changed to

> The ability to contribute more time is useful, but if the NomCom should
> pick a few ADs who can only do 15 hrs/week on a routine basis, the IESG can
> cope with that.

Starting with the 2018 NomCom, this changed to the following

> Many ADs allocate 15 hours or more per week...

This boilerplate has been unchanged in the five years since then.

> **TODO:** Would be interesting to find out why this changed.

Interestingly, the number of pages has also not changed "read on the
order of 500 pages of internet-drafts every two weeks."

> **TODO:** Get pagecounts for the past several years; maybe from the
> sodastream folks?

# Rationale

We need to make the AD job (except for the IETF Chair),
less time-consuming. The current requirement is not sustainable, and will
lead to centralization of technical leadership in only the largest
companies.
Of the 14 current Area Directors, eight (more than half) work for the one
of the 2,000 largest global companies {{FORBES}} or a subsidiary.

> **TODO:** Look at previous IESG membership

# Recommendations/Suggestions

## Only one AD to approve

An Internet-Draft ballot should allow only one AD in each area to vote.
The other director(s) can either vote "no objection" or the ballot
tracking can be modified to handle this more directly.
Coordination between area ADs is left to them to handle; this document
suggests that the *non-responsible* AD be the one to vote.
During discussion, all ADs should participate.

For any area with a directorate, the default ballot position should be
to accept that review, if one is given.

## No "revisit" documents open across change-over

An incoming AD should not pick up the documents left by the predecessor.
A new AD should not add be able to add work on authors, or for them.

If the IESG believes that a previous AD did a poor job, it should vote
on that and announce it to the IETF community.

## Documents, not scheduling

What is the rationale for the IESG setting meeting logistics?
How much time is consumed with scheduling?

We have professional staff, with Board oversight, and consultations.
The meeting venue requirements are being discussed as an update to
{{RFC8718}} and any policy changes will be acted on.

## Content not language

It is not an effective use of technical experts to review and correct
for things like typo's, etc.
We recognize that many ADs will be "unable to help themselves" as
the personality trait of nit-picking is endemic to our profession.
ADs can point out things that are not clear, and if
there are many of them, feel free to send the document back to the WG.
This will be hard, particularly for contributors where English is not
their native language.
Perhaps the IETF can offer resources to help with this before a document
gets to the RFC Production Center (which is more focused on copyediting,
anyway).

# Increasing the candidate pool

This document offers a number of suggestions to reduce the workload
of an IETF Area Director. Previous NomCom's have repeatedly heard that
the effort is involved is a full-time job. Few companies other than
large IT or Internet firms, can afford this.
This document offers some suggestions, in addition to reducing the workload,
that might help increase the diversity of candidates.

## Reimburse travel

Might help get more volunteers from other (less-wealthy? smaller companies?)
parts of the world.
We have learned to accomodate more remote meetings, perhaps that is enough.

## Pre-AD training

"So you want to be an AD" could be worthwhile training to offer.
Of course the IESG and the way the work vary, and it would have to
be done in consultation with them.

# Security Considerations

This changes the IESG review process.

# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

None yet.
