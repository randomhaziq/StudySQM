## Introduction
The Rayleigh Model is a mathematical model used to predict effort, defects, and reliability over the software development lifecycle. It is most commonly applied in software project estimation, especially in the Putnam (SLIM) Model.
>Rayleigh Model = A curve that shows how effort or defect discovery increases, peaks, and then decreases throughout a project.

## Rayleigh Curve Shape
The Rayleigh curve shows:
- Slow increase in effort or defect discovery at the start
- Peak (maximum) in the middle of development
- Gradual decline toward the end  

It looks like this:
```
Effort or Defects
       /\
      /  \
     /    \
    /      \
___/        \______
          Time →
```
This curve is essential to predicting stress points, testing needs, and resource allocation.

## What the Rayleigh Model Is Used For
A. Effort Prediction
   - Predicts how manpower will be distributed over time.

B. Defect Discovery Rate
   - Shows when most defects will be found (usually during peak development).

C. Reliability Growth
   - Used to estimate when the system becomes stable.

D. Schedule Estimation
   - Predicts total development duration based on peak effort.

E. Support for Putnam Model (SLIM)
   - Rayleigh is the foundation of the Putnam Software Life Cycle Model.

## How It Helps Software Quality Management
Even though Rayleigh is not a direct QA activity, it supports quality management by:

1. Planning testing effort
   - Testers know when defect discovery will peak.

2. Predicting manpower needs
   - Avoids overloading or understaffing.

3. Identifying defect arrival patterns
   - Helps detect process or quality problems.

4. Supporting reliability estimation
   - Indicates when the product becomes stable enough for release.

## Rayleigh Model Key Assumptions
- Work rate starts slow, increases, peaks, then declines
- Defects follow the same pattern as effort
- Software development effort is smooth and continuous
- Project phases overlap gradually
- Team size is controlled and stable

## Advantages
- Easy to interpret visually
- Helps predict peak workload and defect rate
- Useful in early cost and schedule estimation
- Provides realistic insight into reliability growth

## Limitations
- Assumes smooth, ideal development flow (not always realistic)
- Not accurate for very small or chaotic projects
- Requires historical data to adjust the curve
- Less effective when team size changes frequently
- Agile / DevOps (continuous testing)