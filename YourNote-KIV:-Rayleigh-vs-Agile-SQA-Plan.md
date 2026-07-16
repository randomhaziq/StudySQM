## Rayleigh vs Agile SQA Plan
A Rayleigh-based SQA Plan uses defect-trend prediction to control quality, while an Agile SQA Plan relies on continuous testing and sprint-based quality feedback.

#### 1. SQA Philosophy
| Aspect           | **Rayleigh-Based SQA Plan** | **Agile-Based SQA Plan** |
| ---------------- | --------------------------- | ------------------------ |
| Quality view     | Predictive                  | Adaptive                 |
| Defect handling  | Planned distribution        | Continuous discovery     |
| QA timing        | Late-phase intensive        | Shift-left & continuous  |
| Change tolerance | Low                         | High                     |


#### 2. Quality Objectives
| Rayleigh SQA                                   | Agile SQA                         |
| ---------------------------------------------- | --------------------------------- |
| Achieve defect peak and decline before release | Maintain low defects every sprint |
| Predict defect trend                           | React to real-time metrics        |
| Release after stabilization                    | Release when sprint quality met   |


#### 3. SQA Activities by SDLC Phase
| Phase        | Rayleigh SQA Plan       | Agile SQA Plan                     |
| ------------ | ----------------------- | ---------------------------------- |
| Requirements | Formal reviews          | User stories & acceptance criteria |
| Design       | Inspections             | Incremental design                 |
| Development  | Unit testing            | TDD / pair programming             |
| Testing      | Dedicated testing phase | Continuous testing                 |
| Release      | Single major release    | Frequent releases                  |


#### 4. Defect Discovery Pattern
| Aspect        | Rayleigh          | Agile               |
| ------------- | ----------------- | ------------------- |
| Shape         | Single bell curve | Multiple mini-peaks |
| Defect peak   | System testing    | Each sprint         |
| Defect fixing | Batch-oriented    | Immediate           |


#### 5. Quality Metrics
| Metric                | Rayleigh SQA        | Agile SQA          |
| --------------------- | ------------------- | ------------------ |
| Defect discovery rate | Tracked vs curve    | Tracked per sprint |
| Defect density        | Release readiness   | Sprint quality     |
| Defect leakage        | Post-release metric | Sprint spillover   |
| Test coverage         | Final assessment    | Continuous         |


#### 6. Quality Gates
| Gate             | Rayleigh SQA       | Agile SQA              |
| ---------------- | ------------------ | ---------------------- |
| Entry criteria   | Phase completion   | Sprint backlog ready   |
| Exit criteria    | Defect decline     | Definition of Done     |
| Release decision | Curve tail reached | Sprint review approval |


#### 7. Roles & Responsibilities
| Role       | Rayleigh             | Agile           |
| ---------- | -------------------- | --------------- |
| QA Manager | Curve monitoring     | Quality coach   |
| Test Lead  | Peak detection       | Sprint quality  |
| Developers | Fix assigned defects | Own quality     |
| Management | Long-term planning   | Sprint steering |


#### 8. Risk Management
| Risk Indicator     | Rayleigh      | Agile          |
| ------------------ | ------------- | -------------- |
| Late defects       | High risk     | Early exposure |
| Requirement change | Disruptive    | Expected       |
| Process deviation  | Detected late | Detected early |


#### 9. Tools & Reporting
| Area            | Rayleigh        | Agile             |
| --------------- | --------------- | ----------------- |
| Defect tracking | Trend charts    | Sprint dashboards |
| Reporting       | Milestone-based | Real-time         |
| Automation      | Optional        | Mandatory         |


#### 10. Release Readiness
| Decision Basis    | Rayleigh       | Agile             |
| ----------------- | -------------- | ----------------- |
| Stability         | Defect decline | Sprint acceptance |
| Confidence        | Statistical    | Empirical         |
| Release frequency | Low            | High              |


#### When to Use?
| Scenario                   | Best Choice              |
| -------------------------- | ------------------------ |
| Government / regulated     | Rayleigh                 |
| Student Waterfall projects | Rayleigh                 |
| Startup / CI-CD            | Agile                    |
| Hybrid organizations       | Agile + Rayleigh metrics |
