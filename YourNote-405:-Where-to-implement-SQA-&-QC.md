## Option 1: Only Epic for SQA & QC

#### Problem:
1. QA becomes separate from development
1. Developers may ignore quality
1. Hard to link testing to actual features

## Option 2: Only Task/Sub-task

#### Problem:
1. No big picture of quality
2. Difficult for:
   - Reporting
   - Audit


## BEST PRACTICE
### 1. Create SQA & QC as Epics

Examples:
- Testing & QA
- Code Review
- Defect Management
- Data Quality Control

Purpose:
1. High-level planning
2. Reporting


### 2. ALSO Embed SQA/QC in Development Work
This ensures, Quality is built-in, not separate.

Example (AgroKedah)
```
Epic: Permohonan Bantuan
 ├── Story: Farmer submits application
 │     ├── Task: Create API
 │     │     ├── Sub-task: Write unit test   ← SQA
 │     │     ├── Sub-task: Code review       ← SQA
 │     │     └── Sub-task: Validate data     ← QC
 │     └── Bug: Submission fails
```

## Comparison
| Approach                 | Suitable?    | Why             |
| ------------------------ | ------------ | --------------- |
| Only Epic                | ❌ Not enough | Too high-level  |
| Only Task/Sub-task       | ❌ Not enough | No visibility   |
| **Hybrid (Recommended)** | ✅ Best       | Balance of both |
