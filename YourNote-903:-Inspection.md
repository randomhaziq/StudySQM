## Introduction
Inspection is the most formal and rigorous type of peer review in software quality assurance. It follows a structured process, involves defined roles, uses checklists, and produces a formal defect report.
>Inspection = A formal, structured, moderator-led review to detect defects early and improve product quality.

## Purpose of Inspection
- Identify defects early (before coding or release)
- Ensure compliance with standards and requirements
- Verify correctness, completeness, consistency
- Reduce cost by detecting errors early in lifecycle
- Ensure documentation, design, and code meet quality expectations
- Improve reliability of the system before implementation

## When Inspections Are Used
Inspections are used for high-value or high-risk artifacts:
- Requirements specification (to remove ambiguities)
- Software design documents (UML diagrams, architecture diagrams)
- Source code
- Test plans and test cases
- User manuals and technical documentation
- Interface specifications
>Because inspections are formal, they are usually applied to critical parts of the software. 

## Characteristics of Inspection
1. Highly formalized – more structured than walkthroughs and technical reviews
1. Strict roles defined
1. Checklist-driven review
1. Documented defects and metrics
1. Requires preparation before the meeting
1. Moderator controls the process
1. Focus solely on defect detection
1. Follow-up is mandatory – ensuring defects are corrected

## Roles in an Inspection
- Moderator
  - Leads the inspection, ensures rules are followed.
- Author
  - Person who wrote the document/code.
- Reader
  - Reads the material aloud to the team.
- Recorder (Scribe)
  - Documents all defects found.
- Reviewer(s)
  - Experts who evaluate the content.
- Manager (optional)
  - Provides resources/support.

## Inspection Process Steps
The typical lifecycle:
1. Planning – select team, schedule meeting
1. Overview – author explains context
1. Preparation – reviewers study the material individually
1. Inspection Meeting – defects are identified (no problem-solving allowed)
1. Recording – scribe documents all defects
1. Rework – author corrects defects
1. Follow-up – moderator verifies resolution

## Benefits of Inspection
- Detects more defects than walkthroughs or reviews
- Reduces rework and development cost
- Ensures high-quality requirements, design, and code
- Improves team understanding and adherence to standards
- Prevents defects from propagating into later stages
- Produces metrics (defect density, review rate)
- Improves maintainability and reliability

## Difference: Inspection vs Walkthrough vs Technical Review
| Feature         | **Inspection**       | **Walkthrough**          | **Technical Review**          |
| --------------- | -------------------- | ------------------------ | ----------------------------- |
| **Formality**   | Very formal          | Least formal             | Medium                        |
| **Leader**      | Moderator            | Author                   | Technical lead                |
| **Focus**       | Defect detection     | Understanding + feedback | Technical correctness         |
| **Preparation** | Mandatory            | Minimal                  | Required                      |
| **Roles**       | Many defined roles   | Few roles                | Several                       |
| **Output**      | Formal defect report | Feedback, suggestions    | Defect list + recommendations |


## Tools Supporting Inspection
- GitHub/GitLab Pull Request with checklist
- Gerrit Code Review
- Crucible
- SonarQube (static analysis before manual inspection)
- JIRA for defect tracking