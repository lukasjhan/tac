# Publishing Deliverables in the OpenWallet Foundation Community

## Overview

This document outlines the process for publishing deliverables in the OpenWallet Foundation technical community. These deliverables will be created by either [task forces](./task-force-process.md) or [special interest groups](./special-interest-group-process.md). The types of deliverables they can create depend on their goals, 
objectives, and scope. Here are some examples:

1. **Reports**: Summarize findings or recommendations.  These might be formal or informal.
1. **Action Plans**: Outline the steps necessary to address a particular challenge or problem. These plans might include specific tasks, timelines, and responsible individuals.
1. **Recommendations**: Provide guidance or proposals for solving problems, improving processes, or addressing gaps.
1. **Guidelines**: Outline best practices or procedures for a specific industry, domain, or project.
1. **Templates and Tools**: Serve as a starting point for creating new content and help users complete tasks, solve problems, or achieve specific goals frameworks that can be used by others.
1. **Whitepapers**: Provide detailed analysis, data, or insights to help others understand a particular issue or opportunity. These are typically in-depth reports on complex topics.
1. **Case Studies**: Illustrate the impact of real-world examples or hypothetical scenarios, including recommendations or findings.
1. **Frameworks and Models**: Describe how to approach a particular problem or challange through conceptual frameworks, models, or architectures.
1. **Surveys and Research Reports**: Gather data or validate hypotheses via surveys, interviews, or research studies, culminating in reports summarizing findings.
1. **Best Practices and Playbooks**: Outline best practices for specific scenarios, industries, or processes, providing guidance on how to navigate complex situations.
1. **Metrics and KPIs**: Determine how to measure progress toward goals or track the effectiveness of initiatives.
1. **Process Improvements**: Identify areas for process improvement and develop new procedures, workflows, or tools to streamline operations or enhance efficiency.
1. **Training and Education Materials**: Equip others with the knowledge and skills needed to tackle a specific challenge. Might include items such as curricula, tutorials, or guides.
1. **Scoping Documents**: Outline the scope, objectives, and deliverables of a project, ensuring everyone is on the same page.
1. **Lessons Learned Reports**: Summarize learnings, what worked well, and what didn't.

## Process

There are three stages of an OWF deliverable -- draft, review, and approved.

```mermaid
flowchart
  d[Draft]
  r[Review]
  t{TAC\nDecision}
  a[Approved]

  d -->|Submission| r
  r --> t
  t -->|Request Changes| d
  t -->|Approve| a
```

A deliverable begins as a "draft" and retains this status until submitted to the TAC for review. At this point, the deliverable will be considered to be in the "review" stage and retains this status until the TAC makes a decision. The TAC may reject the deliverable for various reasons. If the deliverable is rejected by the TAC then it will return to a "draft" stage where the community can address the concerns of the TAC. The deliverable may also be accepted by the TAC, in which case it will be published as an "approved" deliverable of the OWF technical community. Only after the deliverable is accepted, may the deliverable use the "OpenWallet Foundation" trademark. See [required contents](#required-contents) for more information on what should be included within an "approved" deliverable.

### Draft

During the "draft" stage, the deliverable is being prepared by the task force or special interest group. This includes writing the technical content and ensuring that it meets the standards of the OWF technical community. If there are any concerns about the technical content that cannot be addressed by consensus of the task force or special interest group members, then the community may address these concerns during the "review" stage.

### Submission

The task force or special interest group lead may submit a version of their deliverable to the Technical Advisory Committee (TAC) for review. They can do this by sending an email to the [TAC mailing list](mailto:tac@lists.openwallet.foundation). The email should include the following information:

- A brief description of the deliverable.
- A link to the deliverable. Ideally, this should be a link to a pull request that contains the version of the deliverable where people in the community and the TAC voting members will be able to provide their feedback.
- A link to the task force or special interest group that submitted the deliverable.

### Review

The applicable period to review a submitted deliverable will be no shorter than four weeks. The TAC will make reasonable efforts to provide feedback on the submitted version during the review period and provide any critical comments or objections, with sufficient specificity for the task force or special interest group members to respond and, if required, to facilitate resolution. 

!!! info

    Comments and feedback can be provided by anyone in the OWF community. The TAC will take into consideration any comments and feedback provided during the review process when making their decision.

### TAC Decision

After the applicable review period has elapsed, the submitted deliverable will be discussed at the next TAC meeting. The TAC will make a decision to approve, reject, or request changes based on the feedback provided during the review period. To be approved, the deliverable must receive a two-thirds supermajority vote of the TAC.

If there is not agreement to recommend approval, the deliverable will return to a "draft" status where the community can address the concerns of the TAC and re-submit for review after the concerns have been addressed.

### Changes

No substantive changes may be made to an "approved" deliverable; substantive changes will require review and approval of a successor version of the deliverable. A **substantive change** refers to a modification that significantly affects the content, meaning, or interpretation of an "approved" deliverable.

## Required Contents

### Copyright Notice

The copyright notice must be included in all versions of the deliverable. The copyright notice should include the OpenWallet Foundation as well as the year of publication.

!!! example

    Copyright (c) 2024 OpenWallet Foundation.

### License Notice

The license notice must be included in all versions of the deliverable. The license notice should include a reference to the CC-BY-4.0 license.

!!! example

    This work is licensed under a Creative Commons Attribution 4.0 International License (CC BY 4.0).

### Terms of Use Notice

The terms of use notice must be included in all versions of the deliverable. The terms of use notice should include the following text:

!!! quote

    These materials are made available under and are subject to the Creative Commons Attribution 4.0 International license (http://creativecommons.org/licenses/by/4.0/legalcode).

    THESE MATERIALS ARE PROVIDED “AS IS.” The OpenWallet Foundation ("OWF") and its members and contributors (each of OWF, its members and contributors, a "OWF Party") expressly disclaim any warranties (express, implied, or otherwise), including implied warranties of merchantability, non-infringement, fitness for a particular purpose, or title, related to the materials. The entire risk as to implementing or otherwise using the materials is assumed by the implementer and user. 

    IN NO EVENT WILL ANY OWF PARTY BE LIABLE TO ANY OTHER PARTY FOR LOST PROFITS OR ANY FORM OF INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES OF ANY CHARACTER FROM ANY CAUSES OF ACTION OF ANY KIND WITH RESPECT TO THESE MATERIALS, ANY DELIVERABLE OR THE OWF GOVERNING AGREEMENT, WHETHER BASED ON BREACH OF CONTRACT, TORT (INCLUDING NEGLIGENCE), OR OTHERWISE, AND WHETHER OR NOT THE OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.