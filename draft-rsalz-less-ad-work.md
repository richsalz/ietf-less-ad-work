---
###
# Internet-Draft Markdown Template
#
# This template uses kramdown-rfc: https://github.com/cabo/kramdown-rfc
# You can replace the entire file if you prefer a different format.
# Change the file extension to match the format (.xml for XML, etc...)
#
###
title: "Making Less Work for Area Directors"
category: bcp

docname: draft-rsalz-less-ad-work-latest
submissiontype: IETF  # also: "independent", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: gen
workgroup: GENDISPATCH Working Group
keyword:
 - IESG
venue:
  group: GENDISPATCH
  type: Working Group
  mail: gendispatch@ietf.org
  github: richsalz/ietf-less-ad-work

author:
 -
    fullname: Rich Salz
    organization: Akamai Technologies
    email: rsalz@akamai.com

    fullname: Adrian Farrel
    organization: Old Dog Consulting
    email: adrian@olddog.co.uk

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

Anecdotally, every IESG complains about the Area Director (AD) workload,
and says that it takes the first full term to understand the job.
Empirically, the AD workload is high sometimes causing backlogs in
processing of Internet-Drafts and stressing the ADs.

Empirically, the AD workload is high sometimes causing backlogs in
processing of Internet-Drafts and stressing the ADs. This is evidenced
by the limits applied to the number of pages on the regular IESG
telechats, and by the number of documents waiting in excess of fifty
days for initial AD review after a working group has requested
publication.

This document proposes a number of ways that the AD workload can be
reduced. It will be up to the IETF consensus process to determine which
proposals to adopt.

A major goal of this effort is to make it feasible for a wider diversity
of people to volunteer as candidates for AD positions by reducing the
barriers and costs to individuals and their employers.

--- middle

# Introduction

Anecdotally, every IESG complains about the Area Director (AD) workload,
and says that it takes the first full term to understand the job. This
implies that a successful AD will need to serve at least two terms to be
effective, making the role a commitment of at least four years.

Empirically, the AD workload is high sometimes causing backlogs in
processing of Internet-Drafts and stressing the ADs. This is evidenced
by the limits applied to the number of pages on the regular IESG
telechats, and by the number of documents waiting in excess of fifty
days for initial AD review after a working group has requested
publication.

This document proposes a number of ways that the AD workload can be
reduced. These proposals are intended for discussion and adoption
either individually or in groups such that no one suggestion shall be
blocked by discussions of the others. It will be up to the IETF
consensus process to determine which proposals to adopt.

A major goal of this effort is to make it feasible for a wider diversity
of people to volunteer as candidates for AD positions by reducing the
barriers and costs to individuals and their employers.

# Conventions and Definitions

> **DISCUSSION** Probably delete this section.

{::boilerplate bcp14-tagged}

# History of IESG Job Descriptions

The IETF Nominations Committee (NomCom) appoints ADs to the IESG
according to their judgement, but taking feedback from the community
on the suitability of the candidates, and considering the job
descriptions provided by the sitting IESG. It is useful to look at
the job descriptions provided to the NomCom over the years.

In 2013, the first year for which the job description is preserved in
the datatracker, the description said

> The basic IESG activities can consume between 15-40 hours a week.

In 2017, this changed to

> The ability to contribute more time is useful, but if the NomCom should
> pick a few ADs who can only do 15 hrs/week on a routine basis, the IESG can
> cope with that.

Starting with the 2018 NomCom, this changed to the following

> Many ADs allocate 15 hours or more per week...

This boilerplate has been unchanged in the five years since then.

At the same time (2018), the description added text to say

> Enough time must be allocated to manage approximately 10 to 15 working
> groups, [and] to read on the order of 500 pages of internet-drafts every two
> weeks

This text has also not changed in the last five years.

> **TODO:** Would be interesting to find out why this changed.

The IESG secretary says that this past year (ending in March),
the IESG has requested that agendas be limited to 400 pages.

> **TODO:** Get pagecounts for the past several years; maybe from the
> sodastream folks? From the datatracker? The Secretariat says they do not not
> have access to this historic data.

# Rationale

We want the IESG to be staffed with the best possible people with the
appropriate technical and management skills. In order to achieve this,
the job must be achievable, rewarding, and not an insufferable strain on
the ADs. But the high workload and constant stress mean that this is not
always possible.

At the same time, the ADs must be funded, and this is usually by their
employers. But, although some companies consider funding an AD as "paying
the Internet tax," the companies are being asked to release the time of
one of their key engineers for no or little direct return. At the least,
they hope that some of their employee's time will be available for work
within the company; that is, that the AD job will not be a full time job.
Furthermore, as it is often claimed that an AD does not become fully
effective until their second term, the role implies a commitment from
the AD and their employer of at least four years.

The current requirement is not sustainable, and leads to the
centralization of technical leadership in only the largest companies --
those that can afford the costs and mitigate the loss of a key worker.
Of the 14 Area Directors in March 2023, eight (more than half) work for
the one of the 2,000 largest global companies {{FORBES}} or a subsidiary.

In order to make the AD positions (except for the IETF Chair) more
accessible to candidates from different backgrounds and companies,
the IETF needs to make the AD job less time-consuming.

> **TODO:** Look at previous IESG membership.

> **DISCUSSION** It's interesting, because a number of academics have been
> ADs, and some people from smaller companies.

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

> **DISCUSSION** I'm not clear on this idea. Is it based on a
> misunderstanding of the current requirements? Currently, no AD is
> required to ballot on any document, although it might be considered
> as bad manners to not ballot. However, a "no objection" doesn't
> require a review, and indeed many ADs trust their co-ADs or the
> sponsoring AD. I believe that the IESG would respond in the same
> way: that the reviews are not the problem.
>
> This might, however, turn into advice and guidance phrased as
> "expectations and non-expectations for document review during
> IESG evaluation." It could cover:
> - trusting other ADs
> - sharing review responsibilities between ADs
> - delegation of review to others such as Directorates
> - the meaning of "no objection"
>
> We might, however, look again at the number of "no objections"
> required for a ballot to pass on a standards track draft because
> it could be claimed that this puts additional pressure on ADs to
> do reviews. I don't think this needs to be done, because I think
> that ADs need to understand better that "no objection" can be
> entered without doing a review.

## No "revisit" documents open across change-over

An incoming AD should not pick up the documents left by the predecessor.
A new AD should not be able to add work on authors, or to any
reviewers (directorates and other ADs).

If the IESG believes that a previous AD did a poor job, it should vote
on that and announce it to the IETF community.

> **DISCUSSION** I think this could be phrased a little more tactfully.
> Maybe the thing to say is that ballots cast before AD hand-over should
> stand, making it unnecessary for incoming ADs to review and ballot.

> I'd note that this idea is not going to make a substantial difference.
> It is likely to affect just a few documented each year. At absolute
> maximum this is going to represent 5% of the annual workload of an
> incoming AD. Yes, it's annoying when your I-D is delayed by this, but
> it is rare, and it should only make two weeks difference.

> **COUNTERPOINT**
> I like your suggested wording.  But having had documents cross over the
> March change-over multiple times, the workload isn't just on the AD, but
> on the authors, other reviewers (as I added to the text above), etc.

## Documents, not scheduling

What is the rationale for the IESG setting meeting logistics?
How much time is consumed with scheduling?

We have professional staff, with Board oversight, and consultations.
The meeting venue requirements are being discussed as an update to
{{RFC8718}} and any policy changes will be acted on.

> **DISCUSSION** Isn't this an example of the issue rather than the
> problem itself? Should we rephrase this more along the line of
> "priorities"? That is, once the ADs have done "facilitating" the
> work of the working groups, they are free to spend their time on
> anything they like. But actually, the IESG would always say that
> they are making daily decisions about the priority of what they
> spend their time on. They would say that one of their jobs is to
> look at the IETF and see what needs them to act, and that sometimes
> this results in documents being delayed in favour of other tasks.
> So what is needed is to give the IESG instructions about priorities
> and what tasks to drop. This can go further by listing the tasks
> that should be done by others, but it is hard to make such a long
> list: it is easier to list the tasks that should be done first.

## Content not language

It is not an effective use of technical experts to review and correct
for things like typos, etc. We recognize that many ADs will be "unable
to help themselves" as the personality trait of nit-picking is endemic
to our profession, and they should feel free to point out nits, but
they should be conscious of the time and effort involved.

If a document lacks clarity or has so many issues with English that
there is a risk of it being misunderstood, the AD should recognize this
and feel free to send the document back to the WG for the authors to
fix. This may be hard, particularly for contributors where English is not
their native language, but all working groups have the resources to help
with this.

> **CITATION** I think it was the MPLS WG that instituted an English
> language review team.

Perhaps the IETF can offer resources to help with this before a document
gets to the RFC Production Center (which is more focused on copyediting,
anyway).

> **DISCUSSION** I am wary about the "spend money" solution. It's the thin
> end of a nasty wedge that is already rearing its head in a number of
> places across the IETF. We have loads of people for whom English is their
> native language; they participate in WGs and care about the output, so
> they should help.

# Increasing the candidate pool

This document offers a number of suggestions to reduce the workload
of an IETF Area Director. Previous NomCom's have repeatedly heard that
the effort is involved is a full-time job. Few companies other than
large IT or Internet firms, can afford this.

> **DISCUSSION** Previous para is fine, but probably not here.
> OTOH, the topic of this section is not mentioned in the Abstract and
> Introduction. I think I don't object to it being in the document.

This document offers some suggestions, in addition to reducing the workload,
that might help increase the diversity of candidates.

## Reimburse travel

Might help get more volunteers from other (less-wealthy? smaller companies?)
parts of the world.

We have learned to accommodate more remote meetings, perhaps that is enough.

> **DISCUSSION** I think that ADs feel they need to participate in person.
> They might be helped by a discussion of this point. If the travel budget
> really is an issue, then I think it is worth looking at, although I'd
> note that in order to be considered as an AD, someone has normally been
> attending IETF meetings in person, anyway.

## Pre-AD training

"So you want to be an AD" could be worthwhile training to offer.
Of course the IESG and the way they work varies, and it would have to
be done in consultation with them.

> **DISCUSSION** being careful that this is not an additional burden
> on the sitting ADs whose workload is too high!

# Security Considerations

This changes the IESG review process.

# IANA Considerations

This document has no IANA actions.

--- back

# Acknowledgments
{:numbered="false"}

None yet.

