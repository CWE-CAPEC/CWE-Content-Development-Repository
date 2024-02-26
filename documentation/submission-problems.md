# CWE - Submission Problems

Last generated: 2024-02-20 17:06:34

WARNING: this file was automatically generated. Do not edit.

# Submission Problem Summary

| ID | Name |
|----|------|
|[SUB.UNCLEAR](#SUB.UNCLEAR)|Unclear weakness|
|[SUB.ATTACK](#SUB.ATTACK)|Too attack-focused|
|[SUB.MITIGATION](#SUB.MITIGATION)|Too mitigation-focused|
|[SUB.OVERLAP](#SUB.OVERLAP)|Duplicate/Overlap|
|[SUB.ABS.SUBTREE](#SUB.ABS.SUBTREE)|Potential subtree issue/gap|
|[SUB.ABS.LOWLEVEL](#SUB.ABS.LOWLEVEL)|Low level of abstraction|
|[SUB.ABS.MULTWEAK](#SUB.ABS.MULTWEAK)|Multiple weaknesses|
|[SUB.RELS](#SUB.RELS)|Unclear relationships|
|[SUB.MISSDET](#SUB.MISSDET)|Missing details|
|[SUB.IPR](#SUB.IPR)|IP Rights Concerns|
|[SUB.RELREFS](#SUB.RELREFS)|No relevant references|
|[SUB.GRAMMAR](#SUB.GRAMMAR)|Grammar/Spelling issues|
|[SUB.NOINIT](#SUB.NOINIT)|Full Submission with No Initial Review|
|[SUB.ACTION](#SUB.ACTION)|Unable to determine action|
|[SUB.ACTCHANGE](#SUB.ACTCHANGE)|Change in action for submission|
|[SUB.MISC](#SUB.MISC)|Miscellaneous/other problem|


# Submission Problem Details

<a name="SUB.UNCLEAR"></a>
## SUB.UNCLEAR - Unclear weakness
**Block Phase** - Init-Consultation


### Description

The submission's name and/or description does not clearly identify a
weakness, or it is written in a way that is vague and could cause the
submission to be incorrectly mapped to.




### Resolution

An initial submission (or full submission) cannot progress past the
consultation phase until SUB.UNCLEAR is addressed.



<a name="SUB.ATTACK"></a>
## SUB.ATTACK - Too attack-focused
**Block Phase** - Init-Consultation


### Description

The submission's name and/or description emphasizes the attack, not
the weakness. Either the submission's weakness is not well-understood,
or it is better described as an attack pattern, which may be suitable
for inclusion in CAPEC.




### Resolution

An initial submission cannot progress to later phases unless it also
includes a clear weakness (i.e., is not subject to SUB.UNCLEAR).



<a name="SUB.MITIGATION"></a>
## SUB.MITIGATION - Too mitigation-focused
**Block Phase** - Init-Consultation


### Description

The submission's name and/or description emphasizes missing or
incorrect mitigation without clarifying the weakness.




### Resolution

The submission cannot progress to later phases unless it also includes
a clear weakness (i.e., is not subject to SUB.UNCLEAR).



<a name="SUB.OVERLAP"></a>
## SUB.OVERLAP - Duplicate/Overlap
**Block Phase** - Init-Consultation


### Description

The submission identifies a weakness, but it is a duplicate of (or
partially overlaps) existing weaknesses, indicating problems with the
submission or associated CWE entries.




### Resolution

The submission cannot progress to later phases until (1) the
duplicate/overlap is understood and (2) it is clear how to resolve
this duplicate/overlap.



<a name="SUB.ABS.SUBTREE"></a>
## SUB.ABS.SUBTREE - Potential subtree issue/gap
**Block Phase** - Production


### Description

The submission might identify an issue for which there could be a
broader gap or organizational challenge that requires analysis of CWE
subtree relationships under Research View 1000, in ways that extend
beyond creation of a parent at the next-highest level of abstraction.




### Resolution

The submission cannot progress past the consultation phase (whether
initial or full) unless it is at an acceptable level of abstraction,
and the subtree issue(s) can be resolved or addressed independently.



<a name="SUB.ABS.LOWLEVEL"></a>
## SUB.ABS.LOWLEVEL - Low level of abstraction
**Block Phase** - Init-Consultation


### Description

The submission identifies an issue, but its abstraction might be too
low-level to merit its own CWE entry. If it is focused on a particular
technology, framework, protocol, or function, then it might not be
unique enough to get its own CWE ID.  This might lead to modification
of an existing entry to include the additional details, or creation of
a higher-level entry for which the submission is one example. (Note:
some older CWE entries have this problem and would not be published
today, generally because they were too specific to a particular
language.)




### Resolution

The submission will be allowed to progress to later phases once the
more-general concept is appropriately identified and described. The
original, lower-level submission will serve as a primary example of
the more general concept.



<a name="SUB.ABS.MULTWEAK"></a>
## SUB.ABS.MULTWEAK - Multiple weaknesses
**Block Phase** - Init-Consultation


### Description

The submission describes or suggests multiple independent weaknesses
that each might deserve a separate CWE ID.




### Resolution

The submission cannot progress past the consultation phase until the
number of relevant weaknesses is identified. If there are multiple
weaknesses, separate names and descriptions are needed.



<a name="SUB.RELS"></a>
## SUB.RELS - Unclear relationships
**Block Phase** - Production


### Description

The submission suggests some relationships, but the name/description
is not explained in a way in which the relationship is relevant; or,
the weakness is apparent, but it is not clear what the best
parent/child relationship(s) would be.




### Resolution

The submission cannot progress to the next phase if SUB.UNCLEAR is
present. It can progress to other phases if the CWE Team agrees that
the potential relationships may require closer investigation.  The
submission cannot progress to the publication stage until clear
relationships and direct parents are identified. The CWE Team may
decide to use high-level relationships (e.g., to Pillars) if deeper
problems such as SUB.ABS.SUBTREE exist and cannot be quickly resolved.



<a name="SUB.MISSDET"></a>
## SUB.MISSDET - Missing details
**Block Phase** - any


### Description

The submission is missing some requested or required details for
fields other than name and description.




### Resolution

The submission cannot progress to later phases if it does not have all
required fields.



<a name="SUB.IPR"></a>
## SUB.IPR - IP Rights Concerns
**Block Phase** - any


### Description

The submission might have concerns related to intellectual property
rights, e.g., by citing or deriving content from sources that are
subject to significant restrictions, or if the content is copied
verbatim from a source without attribution (i.e., plagiarism).




### Resolution

The submission cannot progress to later phases until it is clear that
there are no IP concerns.



<a name="SUB.RELREFS"></a>
## SUB.RELREFS - No relevant references
**Block Phase** - Production


### Description

The submission does not provide relevant references that explain the
weakness, or the relevance is not easily found.




### Resolution

The submission is not likely to progress to later phases if there are
no applicable, easily-accessible references. The submitter could
resolve by providing additional details such as a section name and
quote from the reference.  If references still are not available, the
CWE Team may decide to make an exception if no suitable reference is
available.



<a name="SUB.GRAMMAR"></a>
## SUB.GRAMMAR - Grammar/Spelling issues
**Block Phase** - Production


### Description

The submission has multiple occurrences of errors with grammar,
spelling, etc. that should be fixed before publication.




### Resolution

The submission will not be allowed to progress to later phases if the
grammar or spelling problems are so significant that they are likely
to cause difficulty for readers to understand the weakness. If the
issues are minor, then the submission could progress.  However, no
submission can be published without grammar and spelling
checks. American English is used for spelling.



<a name="SUB.NOINIT"></a>
## SUB.NOINIT - Full Submission with No Initial Review
**Block Phase** - Init-Consultation, Production


### Description

A full submission was provided, but it did not go through the Initial
Review / Initial Consultation phases (Proposal stage) and has
significant problems that should have been resolved in that phase
(e.g., SUB.UNCLEAR).  This primarily applies to situations when
external requesters provided a Full Submission form (Production stage)
in 2021 and 2022, before the CWE Team launched the external submission
web server and process.




### Resolution

The submission must be treated as if in the
Initial-Review/Initial-Consultation phase, and the Full submission
will not be evaluated until the Proposal stage is complete.



<a name="SUB.ACTION"></a>
## SUB.ACTION - Unable to determine action
**Block Phase** - Init-Consultation


### Description

It is not clear what action to perform based on the submission, e.g.,
create new entry, update existing entry, etc.




### Resolution

The submission cannot progress to the Production stage until the
relevant actions(s) are identified.



<a name="SUB.ACTCHANGE"></a>
## SUB.ACTCHANGE - Change in action for submission
**Block Phase** - Init-Consultation


### Description

The submission's action needs to change, e.g., from "New Entry" to
"Modification," or vice versa. This potentially requires changes to
the kinds of information that will need to be provided.




### Resolution

The submission cannot progress to the Production stage until the
informational needs are addressed.



<a name="SUB.MISC"></a>
## SUB.MISC - Miscellaneous/other problem
**Block Phase** - any


### Description

The submission has some other problem that is not covered elsewhere.




### Resolution

This will depend on the nature of the problem.




