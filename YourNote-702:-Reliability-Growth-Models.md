## Introduction
Reliability Growth Models are mathematical models used to measure, estimate, and predict how software reliability improves as defects are found and fixed during testing.
>Reliability Growth Models show how software becomes more reliable over time through defect removal.

## Why Reliability Growth Models Are Important in QMS
Reliability models support:

1. Quality Planning
   - Estimate how many defects remain
   - Schedule testing effort
   - Predict reliability trends

2. Quality Control
   - Monitor defect detection rates
   - Identify if testing is effective
   - Check whether reliability is improving

3. Quality Assurance
   - Support decision-making (when to release)
   - Validate if quality targets are met
   - Identify high-risk periods

## What Reliability Growth Models Measure
- Number of defects remaining
- Failure rate over time
- Mean Time To Failure (MTTF)
- Reliability growth curve
- When the system becomes stable
- If defect fixes are improving or worsening quality

## Popular Reliability Growth Models
1. Musa-Okumoto (Logarithmic Poisson Model)
   - Assumes failures decrease logarithmically over time
   - Used for online or real-time systems
   - Good for reliability prediction in operational environments

2. Goel-Okumoto (NHPP — Non-Homogeneous Poisson Process)
   - Defect arrival rate decreases over time
   - Very popular because it fits real testing patterns
   - Models “failure intensity” reduction as testing continues

3. Jelinski–Moranda Model
   - One of the earliest models
   - Assumes fixing each defect reduces failure rate
   - Simple but less accurate for large systems

4. Rayleigh / Putnam Model
   - Based on Rayleigh curve
   - Predicts defect discovery rate (rise → peak → fall)
   - Used for manpower planning and schedule prediction
   - Supports reliability growth indirectly

5. Duane Model
   - Uses empirical failure data
   - Reliability increases following a power-law curve
   - Widely used in hardware but also applied to software


## Common Features of Reliability Growth Models
All reliability models share these concepts:
1. Failure Intensity
   - How frequently failures are detected.
2. Reliability Growth
   - Failures drop as defects are removed.
3. Expected Remaining Defects
   - Model predicts how many bugs are still inside.
4. Trend Curves
   - Visual patterns used to judge testing effectiveness.

## How Reliability Models Help QMS
1. Decision Making
   - “Is the software reliable enough to release?”
   - “Should testing continue?”
   - “How many defects remain?”

2. Improve Testing Strategy
   - If failure intensity is not dropping → testing is ineffective
   - Peak testing periods can be planned
   - Resources can be allocated based on expected defect arrivals

3. Identify Process Weaknesses
   - If reliability is NOT growing → defect introduction is higher than removal
   - Indicates quality problems in requirements, design, or coding

4. Predict Release Reliability
   - Used for:
     - SQA Plan
     - Reliability goals (e.g., 99.9%)
     - Customer acceptance criteria

## Reliability Metrics Associated with These Models
These metrics help QMS teams monitor and predict quality.
- MTTF (Mean Time To Failure)
- MTBF (Mean Time Between Failures)
- Failure Intensity (λ)
- Defect Discovery Rate
- Residual Defects
- Reliability Growth Rate

## Limitations of Reliability Growth Models
- Require historical or real failure data
- Incorrect assumptions → misleading predictions
- Fixing defects may introduce new defects
- Not suitable for very small or extremely agile teams
- Assumes constant or similar testing conditions
