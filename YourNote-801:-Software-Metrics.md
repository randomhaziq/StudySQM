## Introduction
Software metrics are quantitative measurements used to evaluate the quality, performance, and efficiency of software products and development processes.
>Software metrics help you measure, control, improve, and predict software quality.

## Why Software Metrics Are Important
Metrics help to:
- Detect defects early
- Monitor progress
- Improve development processes
- Predict project effort and cost
- Measure product quality
- Support decision-making
- Improve reliability, maintainability, and usability
>Metrics turn assumptions into measurable facts.

## Types of Software Metrics

### A. Product Metrics
Measure the quality of the software itself. Examples:
- Defect density (defects per KLOC or per function point)
- Cyclomatic complexity
- Code coverage
- Response time/throughput
- Reliability metrics (MTTF, MTBF)
- Usability metrics (task success rate)

### B. Process Metrics
Measure the effectiveness of the development process. Examples:
- Defect arrival rate
- Review efficiency
- Test case effectiveness
- Mean time to detect defects (MTTD)
- Mean time to repair (MTTR)

### C. Project Metrics
Measure project progress and productivity. Examples:
- Effort (person-hours/person-days)
- Schedule variance
- Cost variance
- Team productivity
- Resource allocation efficiency

## Key Software Quality Metrics (Common in Industry)
1. Defect Density
```
Defects / KLOC or Defects per Function Point
```

2. Code Coverage
   - Percentage of code executed by automated tests.
3. Cyclomatic Complexity
   - Measures how complex the code logic is.
   - High complexity = harder to maintain + more defects.
4. Customer-Reported Defects
   - Number of issues found by users after release.
5. Reliability Metrics
   - MTTF (Mean Time to Failure)
   - MTBF (Mean Time Between Failures)
   - Failure rate
6. Test Effectiveness
   - How well testing finds defects early.
7. Requirement Stability Index
   - Measures how often requirements change.

## Metrics Used in SQA Plan
An SQA Plan usually defines metrics such as:
- Number of defects found in each testing phase
- Review coverage (percentage of modules reviewed)
- Regression defects
- Code review defects per hour
- Test pass/fail ratio
- Configuration management errors
>Metrics in SQA help track whether quality goals are met.

## Characteristics of Good Metrics
A good metric should be:
- Measurable (quantitative, not subjective)
- Repeatable (consistent results)
- Relevant (useful for decision-making)
- Low-cost to collect
- Simple to understand
- Actionable (leads to improvements)

## Tools Used for Software Metrics
- SonarQube (code quality, complexity, duplication)
- JIRA (defect metrics, burndown charts)
- Jenkins / GitHub Actions (CI/CD metrics)
- JMeter (performance metrics)
- Postman (API performance)
- TestRail (test metrics)

## Common Metric Problems
- Measuring the wrong thing
- Misinterpreting data
- Collecting too many metrics
- Metrics used to blame people instead of improving process
- Not linking metrics to business goals