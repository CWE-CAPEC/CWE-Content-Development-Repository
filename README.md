**Disclaimer: This page is currently under active development**

# Table of Contents

- [CWE Content Development Repository](#cwe-content-development-repository)
- [Pilot Program](#pilot-program)
- [Repository Layout](#repository-layout)
- [Guidelines for New Content Suggestions](#guidelines-for-new-content-suggestions)
- [Summary of Stages and Phases](#summary-of-stages-and-phases)
  - [STAGE 1: Initial Submission](#stage-1-initial-submission)
  - [STAGE 2: Full Submission](#stage-2-full-submission)
  - [STAGE 3: Production](#stage-3-production)
  - [STAGE 4: Publication](#stage-4-publication)
- [Common Problems with Integrating Content Suggestions Into CWE](#common-problems-with-integrating-content-suggestions-into-cwe)
- [Additional Supporting Information](#additional-supporting-information)


# CWE-Content-Development-Repository

The CWE Program has created this public GitHub repository to increase transparency and third-party collaborative input into the CWE content development process.  Submissions are received through the [CWE Submission Form](https://cwesubmission.mitre.org/), after which submission documentation is uploaded here for the entire CWE community to view and comment as the entry develops towards being ready for publication.

All CWE content submissions must adhere to the [CWE Terms of Use](https://cwe.mitre.org/about/termsofuse.html).

# Pilot Program - September 12th, 2023 to March 2024

- This pilot will remain open for all community members with a current CWE content suggestion (as of September 12) until we are ready for a full release.  If you are having issues accessing the repository, please reach out and we will get you access as soon as we can.
- Each submission has been given its own GitHub issue where discussion around that submission should take place.  Feel free to look through all issues with the label “External-Submission” and provide comments as you see fit.
  - Each issue will also have a link to the submission file within the repository.  These files have more detailed process information and information about potential problems with the submission.
- We are very interested in feedback, both good and bad.  Please provide feedback by creating a new issue and choosing the template called “Feedback Template”.  You may also reach out to cwe-submissions@mitre.org with any feedback as well.


# Repository Layout

Each content submission is given its own issue in the repository.  Each issue is titled with the unique submission ID followed by the name for the submission.  Each issue will also include the description of the submission as well as a link to the more detailed submission file, contained in this repository.  All submission files will be under the _submissions_ folder.  The CWE team expects the community to interact with each submission by posting comments directly to each issue.  The CWE team will take these comments into account when reviewing each submission.  When changes to a submission are made, they will also be pushed to this repository.  

# Guidelines for New Content Suggestions

When organizations or individuals wish to suggest new content for CWE, they should start the process by using the official [CWE Content Web Submission Form](https://cwesubmission.mitre.org/).

All CWE content submissions must adhere to the [CWE Terms of Use](https://cwe.mitre.org/about/termsofuse.html).

The web submission form has five required elements:
1. Submitter Contact Information (this will not be shared publicly on the GitHub site)
2. Submission Details
3. Related Weaknesses
4. References
5. Review & Submit

After clicking "Submit", you will receive a confirmation message and your suggestion will be added to the CWE team’s working queue. After internal processing, content suggestions will be added to our GitHub repository for the wider community to track and provide input.

# Summary of Stages and Phases

**Disclaimer: This section needs modification to include the public GitHub space, currently under active development**

The CWE team has several different stages and phases for external content submissions.  You will see that each issue in this repository has a label with it's associated phase, and the submission files themselves have the stage that the submission is.  The following outlines these stages and phases.

### STAGE 1: Initial Submission 
An external submitter ("requester") provides a name, short description of the weakness, one or more references, and suggested relationships. The CWE Team works with the submitter to ensure that the initial submission is correctly described and able to be integrated into CWE content. In the future, it is planned that the broader CWE community will be able to contribute suggestions during this stage.

#### Phase 1: Received

The CWE Team receives an initial submission from the public submission server and brings it into the internal GitLab repository for tracking.

#### Phase 2: Ack-Receipt

The CWE Team notifies the original submitter that the initial submission has been received.

#### Phase 3: Init-Review

A member of the CWE Team performs an initial review of the submission, using a checklist to identify any potential problems with the submission, or any relevant scope exclusions.

#### Phase 4: Init-Consultation

Members of the CWE Team work with the submitter to resolve any critical problems. Note: this phase only occurs when significant problems arise.

#### Phase 5: Init-Rejected

The CWE Team rejects the initial submission and notifies the submitter.

#### Phase 6: Init-Accepted

The CWE Team accepts the initial submission and notifies the submitter.

### STAGE 2: Full Submission
If the initial submission is accepted, then the CWE Team asks the submitter to provide full details for the submission, including over 10 different fields that will make the basis of a new CWE entry, such as potential mitigations, common consequences, demonstrative code examples, and others. The CWE Team works with the submitter to ensure that the full submission has appropriate, correct details.  In the future, it is planned that the broader CWE community will be able to contribute suggestions during this stage.

#### Phase 7: Full-Sub-Requested

The CWE Team asks the submitter to provide full details for their submission, as described in a detailed text form.

#### Phase 8: Full-Sub-Received

The submitter provides a completed full-detail text form.

#### Phase 9: Full-Review

The CWE Team reviews the form, ensures that all requested details are provided, and performs a quality check on each field within the submission.

#### Phase 10: Full-Consultation

If necessary, the CWE Team works directly with the submitter to resolve any gaps or identified quality concerns.

#### Phase 11: Full-Accepted

The CWE Team accepts the full, detailed submission.

### STAGE 3: Production
At this stage, all relevant details should have been provided. The CWE Team prepares the content for inclusion in the next CWE version, whether as a new CWE entry, a modification to an existing entry/entries, or both. The CWE Team works with the submitter and/or the community to address any small errors or omissions that might not have been addressed during earlier stages.

#### Phase 12: Production

The CWE Team begins to integrate appropriate details into its internal repository of CWE content, which is used to generate new CWE versions.

#### Phase 13: CWE-Assigned

For any new entry/entries, the CWE Team assigns a CWE identifier and translates the full submission's content into XML format.

#### Phase 14: CWE-Modified

For any entry/entries requiring modification, the CWE Team integrates any modifications into XML format.

#### Phase 15: Final-Coordination

The CWE Team performs final coordination with the submitter before the content is published, such as confirming credits to the submitter, final review of the changes, etc.

### STAGE 4: Publication
The changes are included in a new CWE version, whether as a new CWE entry, a modification to an existing entry/entries, or both.

#### Phase 16: CWE-Published

The CWE changes and/or new entries are published in a new CWE version.

#### Phase 17: Post-Publication

The CWE Team notifies the submitter of the publication and
determines if any additional changes are necessary.

#### Phase 18: Closed

The CWE Team closes the external submission, and no more action
is necessary. Any future changes, if needed, would apply to the
relevant CWE entry/entries.

# Common Problems with Integrating Content Suggestions Into CWE

The CWE Program has identified the following factors from previous content suggestions that may delay or ultimately affect whether your content suggestion is integrated into CWE.

- __Submission is not Weakness-focused.__ Weaknesses are sometimes more easily understood based on their attacks, or when expressed as a lack of a particular protection mechanism. This is not how CWE entries are defined. It may require additional effort to conduct the root-cause analysis to identify the underlying weakness.
- __Submission requires additional reorganization within CWE.__ While weaknesses related to numeric calculation, buffer overflows, injection, etc. have been researched extensively and have a stable organizational scheme within CWE, other portions of CWE are less mature. Submissions related to these parts of CWE might require broader reorganization of associated relationships across multiple views, possibly forcing the creation or deprecation of multiple entries, not just the original submission.
- __Submission requires additional research to include.__ This is especially the case with newly discovered weaknesses. In some cases, if original research is needed, it may be too resource-intensive to conduct the original research to address the submission quickly, or when highly specialized knowledge is required to understand the issue.
- __Not all requested information is provided.__
- __Descriptions are not clearly written.__
- __Submission elements are missing or do not follow guidelines.__

# Additional Supporting Information

Supplementary guidance on the submission process can be found on the CWE website [here](https://cwe.mitre.org/community/submissions/guidelines.html#other)
