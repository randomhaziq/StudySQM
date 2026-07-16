## What Are Software Quality Characteristics?
Software Quality Characteristics describe how good a software product is from the perspectives of users, developers, and stakeholders — not just whether it works, but how well it works.


## The 8 Core Software Quality Characteristics (ISO/IEC 25010)
https://iso25000.com/en/iso-25000-standards/iso-25010

#### 1. Functional Suitability
Does the software do what it is supposed to do?
- Functional completeness
- Functional correctness
- Functional appropriateness

📌 Example:
An e-commerce system correctly calculates total price, tax, and discounts.


#### 2. Performance Efficiency
How fast and resource-efficient is the system?
- Response time
- Throughput
- Resource utilization

📌 Example:
API responds within 2 seconds for 10,000 users.


#### 3. Compatibility
Can the software work with other systems?
- Co-existence
- Interoperability

📌 Example:
Your Spring Boot API integrates smoothly with an Angular frontend and third-party payment gateway.


#### 4. Usability
How easy is the software to learn and use?
- Learnability
- Operability
- User error protection
- Accessibility

📌 Example:
First-time users can submit a paper in a CMS without training.


#### 5. Reliability
Does the system work consistently over time?
- Maturity
- Availability
- Fault tolerance
- Recoverability

📌 Example:
System auto-recovers after server crash without data loss.


#### 6. Security
How well does the system protect data and access?
- Confidentiality
- Integrity
- Accountability
- Authenticity

📌 Example:
JWT authentication, role-based access (Admin, Reviewer, Author).


#### 7. Maintainability
How easy is it to modify and fix the system?
- Modularity
- Reusability
- Analysability
- Modifiability
- Testability

📌 Example:
Bug fix in one module does not break the entire system.


#### 8. Portability
How easily can the software move across environments?
- Adaptability
- Installability
- Replaceability

📌 Example:
Application runs the same on local machine, Docker, and cloud.


#### Why These Characteristics Matter?
| Stakeholder   | Cares Most About                    |
| ------------- | ----------------------------------- |
| Users         | Usability, Reliability, Performance |
| Developers    | Maintainability, Testability        |
| Security Team | Security                            |
| Management    | Reliability, Cost efficiency        |
| DevOps        | Portability, Performance            |


#### Mapping to SQA Activities
| Quality Characteristic | SQA Activity                            |
| ---------------------- | --------------------------------------- |
| Functional Suitability | Requirement reviews, functional testing |
| Performance Efficiency | Load & stress testing                   |
| Usability              | User testing, UI reviews                |
| Reliability            | Fault injection, recovery testing       |
| Security               | Penetration testing, access control     |
| Maintainability        | Code reviews, unit tests                |
| Portability            | Dockerization, CI/CD pipelines          |
