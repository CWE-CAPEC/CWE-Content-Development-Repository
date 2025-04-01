# Table of Contents
- [CWE Content Development Repository (CDR)](#cwe-content-development-repository)
  - [Content Submission and Participation](#content-submission-and-participation)
    - [External Content Submission Phases](#external-content-submission-phases)
    - [Scope Exclusions](#scope-exclusions)
    - [Submission Problems](#submission-problems)
    - [GitHub Issues](#github-issues)
- [How to Collaborate](#how-to-collaborate)

# CWE Content Development Repository (CDR)

The Common Weakness Enumeration (CWE) Program has launched the CWE Content Development Repository, a public GitHub repository aimed at enhancing transparency and fostering collaborative input from third parties in the CWE content development process. The community can engage in three primary roles: Content Submitter, Content Participant, and Content Screener  , which are detailed below.

+ **Content Submitter:** This individual aims to propose new content changes or additions to CWE. They need to track the progress of their submissions, understand their next steps, and respond to any questions from the CDR Team or other community members.
+ **Content Participant:** This person wishes to engage with the CDR by commenting on submissions without making their own submissions. They may want to track the progress of specific submissions and participate in related discussions.
+ **Content Observer:** This individual seeks a general understanding of what the CDR is and how it operates, but is unlikely to actively participate in content development.

## Content Submission and Participation

Anyone  interested in contributing content to CWE, exploring various content suggestions or contributing ideas for improvements, please consult the [Guidelines for Content Submissions](https://github.com/CWE-CAPEC/CWE-Content-Development-Repository/blob/main/documentation/submission-guidelines.md) to understand the process in detail. In addition to submitting new content or proposing updates to the current content, the Content Submitter plays a crucial role in promptly and correctly addressing feedback from the CWE Team and the community regarding their entries. Their responsiveness is essential for advancing content through various phases efficiently.

Content suggestions are initially received through the [CWE Submission Form](https://cwesubmission.mitre.org/). Once processed by the CWE Team, these submissions are transferred to the CDR public repository here, allowing the entire CWE community to view and comment on them as they progress through various stages.

All CWE content submissions must adhere to the [CWE Terms of Use](https://cwe.mitre.org/about/termsofuse.html).

### External Content Submission Phases 

Once a submission is provided, it needs to be reviewed by the CWE Team to determine if it is suitable for being included as new CWE content. The External Submission review process can be thought of in 4 different stages, described in the table below.

| Stage   | Name                | Description|
|---------|---------------------|------------|
| Stage 1 | Initial Submission  | The CWE Team works with the submitter to ensure that the submitted change is clearly described and should be integrated into CWE content. |
| Stage 2 | Detailed Submission | The CWE Team asks the submitter to provide full details for the submission. |
| Stage 3 | Content Generation  | The CWE Team prepares the content for inclusion in the next CWE version. |
| Stage 4 | Publication         | The change is published in a new CWE version. |

These stages, as well as the more granular phases within each stage are described in detail below.

![Submission Phases Diagram](https://github.com/CWE-CAPEC/CWE-Content-Development-Repository/blob/main/documentation/resources/submission-phases.png)

Refer to [Submission-phases.md](https://github.com/CWE-CAPEC/CWE-Content-Development-Repository/blob/main/documentation/submission-phases.md) for more details, which explains the different phase labels that indicate the current stage of a submission in the review process. There are currently 18 possible phases, each representing a specific point in the review timeline.

### Scope Exclusions

[Scope-exclusions.md](https://github.com/CWE-CAPEC/CWE-Content-Development-Repository/blob/main/documentation/scope-exclusions.md): This document details the labels that begin with "SCOPE." These labels identify various issues related to the scope of a submission, known as scope exclusions. They are assigned during the initial review and are removed once the scope exclusion has been addressed.

### Submission Problems

[Submission-problems.md](https://github.com/CWE-CAPEC/CWE-Content-Development-Repository/blob/main/documentation/submission-problems.md): This file describes labels that start with "SUB." These labels denote various submission problems that a submission may have. Similar to scope exclusions, these labels are assigned during the initial review and are removed once the submission problem has been resolved.

### GitHub Issues

Each content submission is assigned to a unique GitHub issue within the repository. The GitHub issue is titled with the unique submission ID followed by the submission name. Each GitHub issue includes a description of the submission and a link to the detailed submission file located in the repository's *submissions* folder.

The CWE Team encourages the community to interact with each submission by posting comments directly on the respective GitHub issue. The team will consider all comments and discussions during the review process.

When searching for submission issues, filters can be set for various of these issue labels:

+ External-Submission: Identifies issues specifically related to a submission.
+ Feedback: Created by the community to provide feedback on the CDR as a whole. Submission-related feedback should be commented on under the submission issue.
+ Phase: Indicates the submission's stage in the review process, with 18 possible phases.
+ SCOPE: Denotes scope-related problems in a submission, assigned during initial review and removed once resolved.
+ SUB: Denotes submission-related problems, assigned during initial review and removed once resolved.

# How to Collaborate

The main collaboration on the CDR should be through issue comments. The CWE Team will use issue comments to communicate with the content submitter, and the community can use issue comments to provide feedback and thoughts on the submission.

**Code of Conduct:** It is important that anyone contributing to the CDR is respectful in their feedback and follows the [code of conduct](https://github.com/CWE-CAPEC/CWE-Content-Development-Repository/blob/main/CODE_OF_CONDUCT.md). The CWE Team reserves the right to restrict access to anyone who is in violation of the code of conduct.

**Issue Management:** Issues are given various labels that are directly managed by MITRE. These should not be modified by CDR users.

**Reviews:** It is important that members of the community do not attempt to do their own reviews or tell submitters what they should do with their submissions. This will cause confusion as MITRE team members are the only ones who will direct changes to a submission or move the submission through different phases.

**New Submissions:** Please do not create new content submissions as issues on the CDR, instead use the [CWE Submission Form](https://cwesubmission.mitre.org/). We have opened up the ability for community members to create issues for the purpose of giving feedback on the CDR as a whole, but any issues created to submit content will be closed. Please only create issues by using one of the issue templates provided.
