# Guidelines for Content Submissions

## Table of Contents
- [How To Submit New Content](#how-to-submit-new-content)
- [Common Problems with Integrating Content Suggestions Into CWE](#common-problems-with-integrating-content-suggestions-into-cwe)
  - [Submission is not Weakness-focused](#submission-is-not-weakness-focused)
  - [Submission requires additional reorganization within CWE](#submission-requires-additional-reorganization-within-cwe)
  - [Submission requires additional research to include](#submission-requires-additional-research-to-include)
  - [Not all requested information is provided](#not-all-requested-information-is-provided)
  - [Descriptions are not clearly written](#descriptions-are-not-clearly-written)
  - [Submission elements are missing or do not follow guidelines](#submission-elements-are-missing-or-do-not-follow-guidelines)
- [External Submissions Review Process](#external-submissions-review-process)
  - [Stage 1: Initial Submission](#stage-1-initial-submission)
  - [Stage 2: Full Submission](#stage-2-full-submission)
  - [Stage 3: Content Generation](#stage-3-content-generation)
  - [Stage 4: Publication](#stage-4-publication)
- [Additional Supporting Information](#additional-supporting-information)
  - [Other Information](#other-information)
  - [Elements to Include](#elements-to-include)


## How To Submit New Content

When organizations or individuals wish to submit new content suggestions for CWE, the [CWE Submission
Form](https://cwesubmission.mitre.org/) should be used.

All new content submissions must adhere to the [Terms of Use](https://cwe.mitre.org/about/termsofuse.html).

When submitting content for a new CWE, the web submission form has five required elements:

1. Submitter Contact Information 
2. Submission Details 
3. Related Weaknesses 
4. References 
5. Review & Submit 

When Submitting a modification to an existing CWE, the web submission form has three required elements:

1. Submitter Contact Information 
2. Modification Details 
3. Review & Submit 

After clicking “Submit,” you will receive a confirmation message and your submission will be added to the CWE team’s
working queue. After internal processing, content submissions will be added to our GitHub repository for the wider
community to track and provide input.

## Common Problems with Integrating Content Suggestions Into CWE 
The CWE team has identified the following common submission problems from previous content suggestions that may delay or
ultimately affect whether your content submission is integrated into CWE.

For details on all known potential submission problems, click [here](submission-problems.md).

For details on all known potential scope exclusions, click [here](scope-exclusions.md).

### Submission is not Weakness-focused
Weaknesses are sometimes more easily understood based on their attacks, or when expressed as a lack of a particular
protection mechanism. This is not how CWE entries are defined. It may require additional effort to conduct the
root-cause analysis to identify the underlying weakness. 

### Submission requires additional reorganization within CWE
While weaknesses related to numeric calculation, buffer overflows, injection, etc. have been researched extensively and
have a stable organizational scheme within CWE, other portions of CWE are less mature. Submissions related to these
parts of CWE might require broader reorganization of associated relationships across multiple views, possibly forcing
the creation or deprecation of multiple entries, not just the original submission.

### Submission requires additional research to include
This is especially the case with newly discovered weaknesses. In some cases, if original research is needed, it may be
too resource-intensive to conduct the original research to address the submission quickly, or when highly specialized
knowledge is required to understand the issue. 

### Not all requested information is provided
### Descriptions are not clearly written
### Submission elements are missing or do not follow guidelines

## External Submissions Review Process 

Each submission needs to be reviewed by the CWE team to determine if it is suitable for being included as new CWE
content. The External Submission review process can be thought of in 4 different stages: **Initial Submission**, **Full
Submission**, **Content Generation**, and **Publication**.  These stages, as well as the more granular phases within
each stage are described in detail below.

### Stage 1: Initial Submission 
An external submitter either provides a name, short description of the weakness, one or more references, and suggested
relationships for a new CWE submission or provides modification information to modify and existing CWE. The CWE Team
works with the submitter to ensure that the initial submission does not have any [submission
problems](submission-problems.md) that would prevent it from being integrated into CWE content.

#### Phase 1: Received

The CWE Team receives an initial submission from the web submission server and creates an internal submission tracking
file.  Submissions in this phase will typically not be pushed to the CDR to ensure that the information provided is
suitable for public release.

#### Phase 2: Ack-Receipt

The CWE Team notifies the original submitter that the initial submission has been received.  At this stage the
submission will be moved to the CDR, where a GitHub issue tracker will be created for the submission and the internal
submission tracking file will be pushed.

#### Phase 3: Init-Review

A member of the CWE Team performs an initial review of the submission, going through each potential [submission
problem](submission-problems.md) and [scope exclusion](scope-exclusions.md) to ensure there are no issues.  Any
identified submission problem will be added to the submission tracking file and also indicated as a label to the CDR
issue tracker.

#### Phase 4: Init-Consultation

Members of the CWE Team work with the submitter to resolve any identified submission problems. This discussion will
happen as comments under the submission's CDR issue tracker.

#### Phase 5: Init-Rejected

The CWE Team rejects the initial submission and notifies the submitter.

#### Phase 6: Init-Accepted

The CWE Team accepts the initial submission and notifies the submitter.

### Stage 2: Full Submission
If the initial submission is accepted, then the CWE Team asks the submitter to provide full details for the submission,
including over 10 different fields that will make the basis of a new CWE entry, such as potential mitigations, common
consequences, demonstrative code examples, and others. The CWE Team works with the submitter to ensure that the full
submission has appropriate, correct details.  

#### Phase 7: Full-Sub-Requested

The CWE Team asks the submitter to provide full details for their submission.  Currently, this is done by posting a
comment to the CDR issue tracker.  The submitter can then move that comment to a text editor of their choice, add the
details inline, and reply with the updated information as a new comment to the CDR issue tracker.

#### Phase 8: Full-Sub-Received

The submitter has provided the full submission details, but they have not yet been reviewed by the CWE team.

#### Phase 9: Full-Review

The CWE Team reviews the full submission details, ensures that all requested details are provided, and performs a
quality check on each field within the submission.

#### Phase 10: Full-Consultation

If necessary, the CWE Team works directly with the submitter to resolve any gaps or identified quality concerns.

#### Phase 11: Full-Accepted

The CWE Team accepts the full, detailed submission.

### Stage 3: Content Generation
At this stage, all relevant details should have been provided. The CWE Team prepares the content for inclusion in the
next CWE version, whether as a new CWE entry, a modification to an existing entry/entries, or both. The CWE Team works
with the submitter and/or the community to address any small errors or omissions that might not have been addressed
during earlier stages.

#### Phase 12: Production

The CWE Team begins to integrate appropriate details into its internal repository of CWE content, which is used to
generate new CWE versions.

#### Phase 13: CWE-Assigned

For any new entry/entries, the CWE Team assigns a CWE identifier and translates the full submission's content into XML
format.

#### Phase 14: CWE-Modified

For any entry/entries requiring modification, the CWE Team integrates any modifications into XML format.

#### Phase 15: Final-Coordination

The CWE Team performs final coordination with the submitter before the content is published, such as confirming credits
to the submitter, final review of the changes, etc.

### Stage 4: Publication
The changes are included in a new CWE version, whether as a new CWE entry, a modification to an existing entry/entries,
or both.

#### Phase 16: CWE-Published

The CWE changes and/or new entries are published in a new CWE version.

#### Phase 17: Post-Publication

The CWE Team notifies the submitter of the publication and determines if any additional changes are necessary.

#### Phase 18: Closed

The CWE Team closes the external submission, and no more action is necessary. Any future changes, if needed, would apply
to the relevant CWE entry/entries.

## Additional Supporting Information
The following is intended as supplementary guidance information to help clarify the overall submission process to follow
the web form.


### Other Information 

| Topic                                                                                   | Explanation                                                                                                                                                                               |
| --------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Glossary](https://cwe.mitre.org/documents/glossary/index.html)                         | A glossary of commonly used terms within CWE. CWE tries to use a restricted vocabulary to minimize inconsistency.                                                                         |
| [Vulnerability Theory](https://cwe.mitre.org/documents/vulnerability_theory/intro.html) | This document includes some of the core concepts underlying how CWE classifies and represents weaknesses. These concepts directly influence how weaknesses are described by the CWE Team. |
| [Schema](https://cwe.mitre.org/documents/schema/)                                       | XML Schema Definition (XSD) for CWE content. This includes various enumerations that clarify how CWE represents some key information.                                                     |


### Elements to Include 
Following is the minimum list of elements that will ultimately need to be determined for a
successful new entry in the CWE corpus.

- [Name](#name) 
- [Summary](#summary) 
- [Extended Description](#extended-description) 
- [Modes of Introduction](#modes-of-introduction) 
- [Potential Mitigations](#potential-mitigations) 
- [Common Consequences](#common-consequences) 
- [Applicable Platforms](#applicable-platforms)
- [Demonstrative Examples](#demonstrative-examples) 
- [Observed Examples](#observed-examples) 
- [Relationships](#relationships) 
- [References](#references)

#### Name 
Ideally, the name focuses on the weakness/mistake - not the attack. Minimize use of ambiguous words to keep the
name short. Where feasible, use terminology as defined in the CWE glossary and/or vulnerability theory documents. The
name should include: (1) the intended behavior of the code, (2) the mistake (i.e. weakness), (3) the affected resource
(if relevant), and (4) the affected technology (if relevant).

Use of CWE-specific vocabulary is preferred but not required.

#### Summary 
The summary consists of only one or two sentences that describe the weakness itself, i.e. the mistake that is made. Often, the summary will describe what the developer/designer is attempting to do. Critical parts of the summary include: (1) the intended behavior of the code, (2) the mistake (i.e. weakness), (3) the affected resource (if relevant), and (4) the affected technology (if relevant). Each summary part is only expressed with individual words or brief phrases; the extended description can be more comprehensive in its explanation.

Use of CWE-specific vocabulary is preferred but not required.

The summary (and name) should avoid focusing on: (1) the attack, (2) the absence of a mitigation, or (3) the technical impact. If a summary has a strong reliance on this information, this may be an indicator that the entry is not weakness-focused.

#### Extended Description
The extended description provides additional explanation for the weakness. Generally, the intended audience is a developer/designer who might not immediately understand how the weakness can be a problem, or who may have an overly simplistic understanding of the problem.

Use of CWE-specific vocabulary is preferred but not required.

The extended description may consist of multiple paragraphs, but typically it is only one or two paragraphs long.

The extended description:
- Explains why the weakness should be a concern to the developer/designer.
- Briefly summarizes the technical impact that could result.
- Gives subtleties or variations that are necessary to have a broader understanding of the issue.

#### Modes of Introduction
This provides information about how and when a given weakness may be introduced. Multiple introduction points can be provided if they exist.  It includes the following elements:
- **Phase**: This element indicates the development life cycle phase during which a particular mitigation may be applied. As of schema 6.6, the Phase can cover one or more of: *Policy*, *Requirements*, *Architecture and Design*, *Implementation*, *Build and Compilation*, *Testing*, *Documentation*, *Bundling*, *Distribution*, *Installation*, *System Configuration*, *Operation*, *Patching and Maintenance*, *Porting*, *Integration*, and *Manufacturing*.
- **Note**: (Optional) The typical scenario(s) under which the weakness may be introduced during the given phase.

#### Potential Mitigations
This element should cover one or more techniques that will eliminate and/or reduce the frequency or impact of the weakness. It includes the following elements:
- **Phase**: This element indicates the development life cycle phase during which a particular mitigation may be applied. As of schema 6.6, the Phase can cover one or more of: *Policy*, *Requirements*, *Architecture and Design*, *Implementation*, *Build and Compilation*, *Testing*, *Documentation*, *Bundling*, *Distribution*, *Installation*, *System Configuration*, *Operation*, *Patching and Maintenance*, *Porting*, *Integration*, and *Manufacturing*.
- **Description**: A freeform description of the mitigation. Where feasible, the mitigation should be written as generally as possible to account for variations in different languages, frameworks, technologies, etc. At the same time, however, it should be as specific to the weakness as possible. Vague or generic phrases such as "validate inputs," "use defense in depth," or "use a secure algorithm" are discouraged.
- **Effectiveness**: How effective the mitigation may be in preventing the weakness.
  - <u>High</u> - frequently successful in eliminating the weakness entirely.
  - <u>Moderate</u> - will prevent the weakness in multiple forms, but it does not have complete coverage of the weakness.
  - <u>Limited</u> - may be useful in limited circumstances, or it is only applicable to a subset of potential errors of this weakness type.
  - <u>Incidental</u> - generally not effective and will only provide protection by chance, rather than in a reliable manner.
  - <u>Defense in Depth</u> - may not necessarily prevent the weakness, but it may help to minimize the potential impact of an attacker exploiting the weakness.
- **Effectiveness Notes**: If useful, a freeform text description of the effectiveness of the mitigation.

#### Common Consequences
This element will cover the typical negative security impact (or impacts) that occurs if this weakness can be exploited by an attacker. It includes the following elements:
- **Scope**: Identifies the security property (or properties) being violated. Acceptable values include *Confidentiality*, *Integrity*, *Availability*, *Access Control*, *Accountability*, *Authentication*, *Authorization*, *Non-Repudiation*, and *Other*.
- **Impact**: Describes the technical impact that arises if an adversary succeeds in exploiting this weakness.
- **Likelihood**: Identifies how likely the specific consequence is expected to be seen relative to other specified consequences. For example, there may be high likelihood that a weakness will be exploited to achieve a certain impact, but a low likelihood that it will be exploited to achieve a different impact. Acceptable values are High, Medium, Low, and Unknown. Note that these values are not formally defined.
- **Note**: (Optional) Provides additional commentary about a consequence.

#### Applicable Platforms
This element specifies the programming languages (or language families), operating systems, frameworks, architectures, technologies, and/or product classes in which this weakness is usually found.

While this element is well-defined within the CWE schema, it might be unnecessarily limited for external submissions. See the [ApplicablePlatformsType](https://cwe.mitre.org/documents/schema/#ApplicablePlatformsType) and related enumerations for examples.

#### Demonstrative Examples
The entry should have one or more demonstrative examples. A useful example contains several different elements, as outlined below.

**WARNING**: Submitters should not necessarily put significant effort into creating these examples until the CWE team has reviewed and accepted the general concepts behind the submitted entry.

It includes the following elements:
- **Introductory Text**: Describes what the code is attempting to do, possibly providing the context or setting in which the code should be viewed.
- **"Bad" Code Snippets**: Provide one or more code snippets (or algorithm descriptions) that contain the weakness. The primary audience is assumed to be a programmer who is knowledgeable about the language being used.
  - The code should have the correct syntax.
  - The snippets should only focus on the least amount of code for the reader to understand what the code is attempting to do; so, for example, statements that load common libraries can be omitted.
  - The snippets should not try to obscure the associated weakness, as these examples are meant to be easy for the reader to understand.
  - Where feasible, the snippets should only have one weakness, unless the example is intentionally demonstrating a chain or composite.
- **Explanatory Text**: Where reasonable, explanatory text should indicate where the mistake occurs, including what assumptions the programmer may have made along the way. This can include some examples for how the attack could be launched.
- **"Good" Code Snippets**: Show or explain how the "bad" code snippet could be modified to eliminate the weakness.

Note that these details do not closely follow the internal format as used by CWE. If the submitted content is accepted, the CWE team will perform the appropriate conversions into XML. For more information, see the DemonstrativeExamplesType in the schema definition.

#### Observed Examples
Where known, the submission should identify multiple publicly-reported vulnerabilities in real-world software that exhibit the weakness.  It has the following elements:
- **CVE Identifier**: The CVE ID for the example.  Should be provided when available
- **Link**: Link to the reference. The link should not require registration.
- **Summary**: A short sentence or phrase summarizing the weakness. The summary does not necessarily have to name the affected product or service, rather, cover the mistake that leads to the weakness, and possibly the technical impact. Preferably, the summary should not give the actual vendor or product name, nor should it be a verbatim copy of the associated CVE description.

#### Relationships
Identify the parent CWE(s) under which this weakness should be classified. Ensure that these parents are Weakness types, not categories. The CWE team will perform additional analysis to ensure that the appropriate relationships exist.

If no clear parent/child relationship can be identified, then identify similar CWEs, and/or include suggestions for how to close the gap.

When suggesting relationships, try to consider where they fall under the hierarchy-oriented Development View ([CWE-699](https://cwe.mitre.org/data/definitions/699.html)), the Research View ([CWE-1000](https://cwe.mitre.org/data/definitions/1000.html)), and/or the Hardware Design View ([CWE–1194](https://cwe.mitre.org/data/definitions/1194.html)).

#### References
References can include one or more academic papers, white papers, blog posts, slide presentations, or videos that describe the weakness, with URLs.

- In general, the reference should be freely available on the web, without requiring registration.
- Where feasible, the original announcement of the weakness should be included as a reference.
- References should not be overtly "commercial" or marketing-oriented in tone.
- Where feasible, URLs that are unlikely to change should be preferred.