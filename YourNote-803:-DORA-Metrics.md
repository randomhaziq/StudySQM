## DORA Metrics

DORA Metrics are a set of software delivery and DevOps performance metrics developed by the DevOps Research and Assessment (DORA) team, now part of Google Cloud. These metrics are widely used to evaluate the effectiveness of software development, deployment, and operational processes.

## Why DORA Metrics?
1. Provide objective measurements of DevOps performance.
1. Identify bottlenecks in the CI/CD pipeline.
1. Evaluate the effectiveness of automation tools such as GitHub Actions and Docker.
1. Serve as industry-recognised engineering performance indicators.
1. Help teams continuously improve software delivery quality and speed.

## The Four Key DORA Metrics

| Metric                      | What It Measures                               | Goal             |
| --------------------------- | ---------------------------------------------- | ---------------- |
| Deployment Frequency (DF)   | How often software is deployed to production   | Higher is better |
| Lead Time for Changes (LT)  | Time from code commit to production deployment | Lower is better  |
| Change Failure Rate (CFR)   | Percentage of deployments causing failures     | Lower is better  |
| Mean Time to Restore (MTTR) | Time required to recover from a failure        | Lower is better  |


## 1. Deployment Frequency (DF)

Question: How often does the team deploy software to production?

### Formula:
```
Deployment Frequency = Number of Deployments / Time Period
```

### Example
- 20 deployments per week
- 80 deployments per month

A higher deployment frequency indicates that the team can deliver new features and improvements to users more rapidly.

### In an Angular + Spring Boot Project

Examples of deployments include:
- Pushing code to GitHub
- Building Docker images through GitHub Actions
- Deploying applications to a cloud server such as DigitalOcean

>Each successful production deployment contributes to the Deployment Frequency metric.

## 2. Lead Time for Changes (LT)

Question: How long does it take for a code change to reach production?
>Time to implement, test, and deliver code for a feature (measured from first commit to deployment)

### Formula:
```
Lead Time = Deployment Date − First Commit Date
```

### Example

| Activity                 | Date   |
| ------------------------ | ------ |
| Developer first commits code   | June 1 |
| Deployment to production | June 2 |

Lead Time = 1 day

>A shorter lead time indicates a more efficient software delivery process.

## 3. Change Failure Rate (CFR)

Question: What percentage of deployments result in failures?

### Formula:
```
Change Failure Rate = (Failed Deployments / Total Deployments) × 100%
```

### Example
- 100 deployments
- 5 deployments caused production issues
- Therefore, CFR = 5%

>A lower Change Failure Rate indicates higher software quality and deployment reliability.

## 4. Mean Time to Restore (MTTR)

Question: If a failure occurs, how quickly can the team restore service?

### Formula:
```
MTTR = Total Recovery Time / Number of Incidents
```

### Example

| Incident         | Recovery Time |
| ---------------- | ------------- |
| Server outage    | 30 minutes    |
| Database failure | 15 minutes    |
| API crash        | 45 minutes    |

MTTR = (30 + 15 + 45) / 3 = 30 minutes

>A lower MTTR reflects an effective incident response and recovery process.

## The Fifth DORA Metric: Reliability

More recent DORA research also emphasizes Reliability as an additional performance measure.

### Examples include:
- System uptime (e.g., 99.9%)
- API response time
- Error rate
- SLA compliance

>Reliability focuses on the end-user experience and system dependability.

## Relationship Between DORA Metrics and DevOps Tools

| Technology           | Related DORA Metric   |
| -------------------- | --------------------- |
| GitHub               | Lead Time for Changes |
| GitHub Actions       | Deployment Frequency  |
| JUnit / Mockito      | Change Failure Rate   |
| Docker               | Deployment Frequency  |
| Prometheus / Grafana | MTTR                  |
| SonarQube            | Change Failure Rate   |


## Example `Class Project` Case Study
Suppose a student team develops:
- Angular Frontend
- Spring Boot Backend
- MySQL Database
- GitHub Actions CI/CD Pipeline
- Docker Containers
- DigitalOcean Deployment

During one month:
1. 40 deployments were performed
1. 2 deployments failed
1. Average commit-to-production time = 4 hours
1. Average recovery time = 20 minutes

The DORA metrics would be:

| Metric                | Value                |
| --------------------- | -------------------- |
| Deployment Frequency  | 40 deployments/month |
| Lead Time for Changes | 4 hours              |
| Change Failure Rate   | 5%                   |
| MTTR                  | 20 minutes           |

>These values indicate a relatively mature and efficient DevOps process.

## References:
1. https://en.wikipedia.org/wiki/DevOps_Research_and_Assessment
1. https://dora.dev/guides/dora-metrics/
1. https://www.atlassian.com/devops/frameworks/dora-metrics
