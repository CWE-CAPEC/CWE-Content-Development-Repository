**Disclaimer: This page is currently under active development**

# Table of Contents
- [Important Resources](#important-resources)
- [CWE-Content-Development-Repository](#cwe-content-development-repository)
- [Pilot Program - September 12th, 2023 - March 2024](#pilot-program---september-12th-2023---march-2024)
- [Repository Layout](#repository-layout)
  - [Directory Structure](#directory-structure)
  - [Issues](#issues)
    - [Issue labels](#issue-labels)
  - [Submission Files](#submission-files)
    - [Submission File Elements](#submission-file-elements)
  - [Reports](#reports)
    - [sub-index-phases](#sub-index-phases)
    - [sub-index-problems](#sub-index-problems)
- [How to Collaborate](#how-to-collaborate)


# Important Resources

 - [Guidelines for New Content Submissions](documentation/submission-guidelines.md)
 - [Potential Submission Problems](documentation/submission-problems.md)
 - [Potential Scope Exclusions](documentation/scope-exclusions.md)

# CWE-Content-Development-Repository

The CWE Program has created the CWE Content Development Repository, a public GitHub repository to increase transparency and third-party collaborative input into the CWE content development process.  Content Suggestions are received through the [CWE Submission Form](https://cwesubmission.mitre.org/) and, after being processed by the CWE team, are tranferred here for the entire CWE community to view and comment as the submission moves through various stages.

All CWE content submissions must adhere to the [CWE Terms of Use](https://cwe.mitre.org/about/termsofuse.html).

# Pilot Program - September 12th, 2023 - March 2024

- This pilot will remain open for all community members with a current CWE content suggestion (as of September 12) until we are ready for a full release.  The purpose of this is to work through the process in a closed environment to figure out issues and gather feedback before turning the repository public.
- Each submission has been given its own GitHub issue where discussion around that submission should take place.  Feel free to look through all issues with the label “External-Submission” and provide comments as you see fit.
  - Each issue will also have a link to the submission file within the repository.  These files have more detailed process information and information about potential problems with the submission.
- We are very interested in feedback, both good and bad.  Please provide feedback by creating a new issue and choosing the template called “Feedback Template”.  You may also reach out to cwe-submissions@mitre.org with any feedback as well.

# Repository Layout

## Directory Structure

The CDR currently has the following directory structure:

- **documentation/**: contains various documentation files which are linked to in the README
- **reports/**: contains report files on the various statuses for all submissions, including phases and submission problems
- **submissions/**: contains all of the submission files for tracking, which are linked to in each corresponding submission issue

## Issues

Each content submission is assigned its own GitHub issue in the repository.  Each issue is titled with the unique submission ID followed by the name for the submission.  Each issue will also include the description of the submission as well as a link to the more detailed [submission file](#submission-files) contained in this repository.  All submission files will be under the _submissions_ folder.  The CWE team expects the community to interact with each submission by posting comments directly to each issue.  The CWE team will take any comments and discussion into account when reviewing each submission. 

### Issue labels

Each individual submission will be given one of several different labels.  When searching for submission issues, filters can be set for various issue labels.  The following are the different kinds of issue labels:

- **External-Submission**: Indicates that the issue is a submission issue.  We currently allow issues to be created for feedback and may also introduce other issues which are not directly related to a particular submission.  This label helps identify only the issues that are specifically related to a submission.
- **Feedback**: Indicates an issue created by the community to give feedback on the CDR as a whole.  Submission related feedback should be added as a comment under the submission issue.
- **Phase**: There are various phase labels that indicate where the submission is in the [submission review process](documentation/submission-guidelines.md#external-submissions-review-process).  Currently, there are 18 possible phases.
- **SCOPE**: Labels that start with "SCOPE." indicate any number of problems a submission currently has related to it's scope, referred to as [scope exclusions](documentation/scope-exclusions.md).  These labels are assigned during initial review of a submission and are removed once the scope exclusion has been resolved.
- **SUB**: Labels that start with "SUB." indicate any number of [submission problems](documentation/submission-problems.md) that a submission currently has. These labels are assigned during initial review of a submission and are removed once the submission problem has been resolved.

## Submission Files

For each submission, a submission file is created to track the progress of the submission.  While submission issues have the basic information needed to understand a submission, these text files have additional information that is filled out by the CWE team to track the submissions.  These files are not to be edited by the submitter or the community, the CWE team will make the necessary edits as the submission is moved through the process.  

### Submission File Elements
Submission files contain the following elements.  Once the submission moves to a full submission, it will include new elements described [here](documentation/submission-guidelines.md#elements-to-include).

| Element                     | Description                                                                                                                                                                                                                                                                                                                                                                    |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| SUBMISSION COMMUNICATION ID | A unique ID to identify the submission.  It starts with "ES" to indicate "External Submission", followed by the submission date, and then a unique 8 character identifier                                                                                                                                                                                                      |
| ACTION TYPE                 | This identifies what action is needed for this submission.  The options are "New Entry", "Modification", or "Undetermined"                                                                                                                                                                                                                                                     |
| SUBMISSION STATUS           | This indicates what phase the submission is currently in.                                                                                                                                                                                                                                                                                                                      |
| ORIGIN                      | This indicates where the submission originated from.  Moving forward, all submissions should originate from the "sub-server" (the web submission form), but some past submissions may have originated through other means                                                                                                                                                      |
| SUBMISSION DATE             | The date of submission                                                                                                                                                                                                                                                                                                                                                         |
| ISSUES                      | This indicates if there are any current issues with the submission.  Possible values are "yes/active", "no", or "not-analyzed"                                                                                                                                                                                                                                                 |
| ISSUE DETAILS               | The titles of any active issues for the submission                                                                                                                                                                                                                                                                                                                             |
| PUBTRACKER                  | This indicates the public issue ID on the CDR GitHub for the submission, otherwise referred to as the "public tracker"                                                                                                                                                                                                                                                         |
| MTRACKER                    | This indicates the MITRE internal tracker ID.  TODO: should this be scrubbed from the submission file on CDR?                                                                                                                                                                                                                                                                  |
| GITHUBUSER                  | This indicates the GitHub username of the submitter if provided                                                                                                                                                                                                                                                                                                                |
| SUBMISSION TYPE             | This indicates the type of submission in terms of scope.  Currently, the possible values are "Software" and "Hardware", although additional values may be added in the future as needed                                                                                                                                                                                        |
| NAME                        | The proposed name for the submission                                                                                                                                                                                                                                                                                                                                           |
| DESCRIPTION                 | The proposed description for the submission                                                                                                                                                                                                                                                                                                                                    |
| RELATED WEAKNESSES          | Any CWEs which are thought to be related to the current submission                                                                                                                                                                                                                                                                                                             |
| REFERENCES                  | Any relevant references to the submission provided by the submitter                                                                                                                                                                                                                                                                                                            |
| ACTIVE ISSUES               | This section describes all of the currently identified submission problems.  Each problem has a description of the general problem, a comment about why the submission problem applies to this current submission, with a potential action for the submitter to resolve the problem, and a response section where a CWE team member can paste the response from the submitter. |
| RESOLVED ISSUES             | Similar to ACTIVE ISSUES, except this section descibes all of the submission problems which have been resolved                                                                                                                                                                                                                                                                 |
| TIMELINE                    | This section shows the dates at which the submission has progressed to different phases                                                                                                                                                                                                                                                                                        |
| COMMUNICATION LOG           | This section keeps a log of any communication between the CWE team and the submitter |

## Reports

The CDR has various reports to aid with assessing the status of all
current submissions.  These can be found in the top level *reports/*
directory.  The reports are in two formats:

- markdown format, which can be easily viewed directly on the CDR
- html format, which is best viewed if downloaded and viewed with your browser of choice

Currently there are two different reports to view:

### sub-index-phases - Index of Active Submissions by Phase

This report details all of the current submissions grouped by their
phases.  Under each phase is a table containing the submissions for
that phase.  Each row contains the CDR GitHub ID for that submission
(which links to the submission issue), the submitter GitHub username,
submission date, submission ID (which links to the submission file for
that issue), and the submission name.  For submissions with active
issues, you will also see these issues listed below.

- [markdown format](reports/sub-index-phases.md)
- [html format](reports/sub-index-phases.html)

### sub-index-problems - Index of Active Submissions by Problem Type

This report details all of the current submissions grouped by their
submission problems.  Because submissions often have multiple
problems, you will see individual submissions appear more than once in
this report.  Under each submission problem is a table containing the
submissions for that phase.  Each row contains the CDR GitHub ID for
that submission (which links to the submission issue), the submitter
GitHub username, submission date, submission ID (which links to the
submission file for that issue), and the submission name. The active
issues for each submission will also be listed in a following row.

- [markdown format](reports/sub-index-problems.md)
- [html format](reports/sub-index-problems.html)


# How to Collaborate

The main collaboration on the CDR should be through issue comments.
The CWE team will use issue comments to communicate with the content
submitter, and the community can use issue comments to provide
feedback and thoughts on the submission.

**Code of Conduct**.  It is important that anyone contributing to the
CDR is respectful in their feedback and follows the [code of
conduct](CODE_OF_CONDUCT.md).  The CWE team reserves the right to
restrict access to anyone who is in violation of the code of conduct.

**Issue Management**.  Issues are given various labels that are
directly managed by MITRE.  These should not be modified by CDR users.

**Reviews**.  It is important that members of the community do not
attempt to do their own reviews or tell submitters what they should do
with their submissions.  This will cause confusion as MITRE team
members are the only ones who will direct changes to a submission or
move the submission through different phases.

**New Submissions**. Please do not create new content submissions as
issues on the CDR.  We have opened up the ability for community
members to create issues for the purpose of giving feedback on the CDR
as a whole, but any issues created to submit content will be deleted.
Please only create issues by using one of the issue templates
provided.








