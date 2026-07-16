## 1. EPIC (BIG BUSINESS PROCESS)
Represents a major module or workflow in AgroKedah

Examples:
- Aid Application
- Investigation & Verification
- Approval & Decision
- Monitoring
>These reflect the `real system workflow`


## 2. STORY (USER REQUIREMENT)
What the user wants to do

Written from the perspective of:
- Farmer
- Officer
- Admin

Examples:
1. “As a farmer, I want to submit an aid application so that I can receive assistance”
1. “As an officer, I want to review applications so that I can conduct investigation”
>Focus = user functionality


## 3. TASK (ACTUAL WORK)
Technical or operational work required to complete a story

Examples:

For the story: `Submit application`
1. Design application form
1. Create submission API
1. Validate input
1. Store data in database
>Focus = implementation


## 4. BUG (PROBLEM / ERROR)
Something that is not working correctly

Examples:
- Application cannot be submitted
- Document upload fails
- Approval status is incorrect
- Mobile app crashes

### Typically found during:
1. Testing (SQA)
2. Real usage (QC)


## COMPARISON

| Type  | Focus       | AgroKedah Example          |
| ----- | ----------- | -------------------------- |
| Epic  | Big process | Aid Application            |
| Story | User need   | Farmer submits application |
| Task  | Work to do  | Create submission API      |
| Bug   | Error       | Submit button not working  |

## Relationship
```
Epic
 ├── Story (user features)
 │     ├── Task (technical work)
 │     └── Bug (issues found)
```

# Sub-task (AgroKedah Example)
### Story:
Farmer submits aid application

### Task:
Create submission API

### Sub-tasks:
1. Define API endpoint
1. Write controller method
1. Validate input data
1. Connect to database
1. Test API using Postman

### Hierarchy

```
Epic
 ├── Story
 │     ├── Task
 │     │     ├── Sub-task
 │     │     └── Sub-task
 │     └── Task
 ```

### When to Use Sub-task
1. Task is too big
1. Work needs to be split among team members
1. You want detailed tracking

### When NOT to Use
1. Don’t create sub-task for everything
1. Avoid too many tiny items (over-fragmentation)