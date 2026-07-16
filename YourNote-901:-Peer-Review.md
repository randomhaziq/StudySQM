## Introduction
A peer review is an informal or semi-formal evaluation of a software work product by colleagues (peers) to identify defects, improve quality, and provide feedback. It is one of the simplest and most widely used SQA techniques.
>Peer Review = A review done by team members to check quality, find defects, and provide improvements.

## Purpose of Peer Review
- Find defects early before testing
- Improve clarity, correctness, and consistency
- Share knowledge among team members
- Ensure adherence to coding and design standards
- Improve maintainability
- Provide constructive feedback for improvement
- Reduce development time and cost
>Peer reviews serve as the first quality checkpoint before formal reviews.

## When Peer Reviews Are Used
Peer reviews can be applied to almost any work product:
- Requirements
- Design documents
- Source code
- Test cases
- User stories
- API documentation
- UI wireframes
>They are typically applied frequently and early.

## Characteristics of Peer Review
1. Informal or semi-formal
   - Less strict than inspection; no rigid rules.

2. Conducted by peers
   - People with similar roles or skills review each other’s work.

3. Flexible structure
   - May involve a meeting or just offline comments.

4. Focus on improvement
   - Not only defect detection; also helps increase team understanding.

5. Low cost and fast
   - Lightweight and suitable for Agile environments.

## Roles in Peer Review
Usually fewer roles compared to inspections:
- Author — presents or shares the work product
- Reviewer(s) — peers who evaluate the product
- Optional: Scribe, moderator (depending on team practice)
>Most Agile teams use peer review through pull requests (PRs).

## Activities in a Peer Review
Common steps:
- Author shares document/code
- Reviewer(s) read and comment
- Discussion on problems and improvements
- Author fixes issues
- (Optional) Follow-up to confirm corrections
>Often performed via tools such as GitHub/GitLab pull requests.

## Benefits of Peer Reviews
- Detect defects early (before testing)
- Improve code readability and maintainability
- Increase shared understanding and team consistency
- Encourage learning among team members
- Reduce cost by catching issues before integration
- Improve quality of both code and documentation
>Peer reviews are a key practice in Agile, Scrum, and DevOps.

## Difference: Peer Review vs Walkthrough vs Inspection
| Feature           | **Peer Review**    | **Walkthrough**         | **Inspection**                     |
| ----------------- | ------------------ | ----------------------- | ---------------------------------- |
| **Formality**     | Informal           | Semi-formal             | Very formal                        |
| **Leader**        | None or author     | Author                  | Moderator                          |
| **Focus**         | Feedback + defects | Understanding + defects | Defects only                       |
| **Roles**         | Minimal            | Few                     | Many (moderator, reader, recorder) |
| **Documentation** | Optional           | Some notes              | Formal defect report               |
| **Speed**         | Fast               | Medium                  | Slow                               |

## Tools Supporting Peer Review
Common in industry:
- GitHub Pull Requests
- GitLab Merge Requests
- Bitbucket Code Review
- Crucible
- Gerrit
- SonarLint/SonarQube (pre-review static analysis)
>PR-based peer reviewing is standard in most modern software teams.



