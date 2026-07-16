### Goal
To explain the major software quality models and standards used in the software industry, focusing on how these models define, categorise, and measure software quality from both product-oriented and process-oriented perspectives.


### 🎯 Learning Objectives
Students should be able to:
1. Describe and compare the Boehm, FURPS, and McCall quality models.
1. Differentiate between product-oriented and process-oriented quality approaches.

### 📌 Topics to Cover                               
1. Boehm, FURPS, and McCall Models
   - Boehm Model (1978)
     * One of the earliest software quality frameworks.
     * Defines three main levels:
       - High-level characteristics (Utility, Maintainability, Portability)
       - Intermediate-level characteristics (Reliability, Efficiency, Human Engineering, Testability, etc.)
       - Primitive-level metrics (quantifiable measures such as response time, defects per KLOC).
     * Focuses on both user satisfaction and developer needs.
     * Example: “Ease of understanding” and “Modularity” improve maintainability.

    - FURPS Model (by Hewlett-Packard)
      * Acronym:
        - F – Functionality (features, capability, security)
        - U – Usability (human factors, aesthetics, documentation)
        - R – Reliability (availability, failure frequency, accuracy)
        - P – Performance (speed, efficiency, response time)
        - S – Supportability (maintainability, adaptability, serviceability)
      * Useful for organising non-functional requirements in software projects.
      * Example: In a mobile banking app, Usability → intuitive interface; Reliability → zero transaction errors.

    - McCall Model (1977)
      * Divides quality into three main categories:
        - Product Operation: Correctness, Reliability, Efficiency, Integrity, Usability
        - Product Revision: Maintainability, Flexibility, Testability
        - Product Transition: Portability, Reusability, Interoperability
      * Links quality factors to quality criteria (user expectations) and metrics (quantifiable measures).
      * Emphasises bridging the gap between user and developer views of quality.
      * Practical Application: Used to evaluate system design documentation and testing results.

2. Product-Oriented Approach of Software Quality
   - Focuses on attributes of the software product itself.
   - Measures what the software does and how well it performs.
   - Involves metrics such as:
     * Correctness (accuracy of outputs)
     * Reliability (frequency of failures)
     * Efficiency (use of resources)
     * Usability (ease of learning and use)
   - Supported by product-based models such as McCall, Boehm, FURPS, and ISO/IEC 25010.
   - Tools used: static analysers, test coverage tools, and defect tracking systems.
   - Example: Using SonarQube to assess maintainability and complexity metrics in code.

3. Process-Oriented Approach of Software Quality
   - Focuses on the processes and activities involved in producing the software.
   - Assumes “a good process produces a good product.”
   - Supported by process standards and frameworks such as:
     * ISO 9001: Quality management systems.
     * CMMI (Capability Maturity Model Integration): Maturity levels of software organisations.
     * IEEE 730: Standard for Software Quality Assurance Plans.
   - Involves process improvement techniques (PDCA, Six Sigma, Total Quality Management).
   - Encourages continuous improvement and quality culture across the organisation.
   - Example: Adopting Agile practices like CI/CD pipelines to improve process quality.

### 💪 Hands-on Activity
1. Model Comparison Table: Students compare Boehm, FURPS, and McCall models side by side.
1. Case Analysis: Identify whether a given quality issue is product-oriented or process-oriented.
1. Mini Project: Evaluate a sample software product using at least one quality model.


### 🛠️ Tools to Use
1. SonarQube
1. JMeter


### 📚 Suggested Readings / Videos
1. Boehm, B. (1978). Characteristics of Software Quality. TRW Software.
1. McCall, J. A. (1977). Factors in Software Quality. U.S. Air Force.
1. Hewlett-Packard. (1992). FURPS Model for Software Quality Requirements.
1. ISO/IEC 25010: Systems and Software Quality Models.
1. ISO 9001: Quality Management Systems — Requirements.
1. SEI. (2010). CMMI for Development, Version 1.3.

