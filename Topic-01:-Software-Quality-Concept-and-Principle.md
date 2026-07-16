### Goal
To introduce the fundamental ideas, characteristics, and factors that define software quality. Students will learn why quality is challenging to achieve and how quality principles guide the software engineering process.


### 🎯 Learning Objectives
Students should be able to:
1. Define software quality from technical and customer perspectives.
1. Explain the main challenges in achieving software quality.
1. Identify and describe software quality characteristics based on international models such as ISO 9126 and ISO/IEC 25010.
1. Discuss quality concepts and software quality factors that influence product and process quality.

### 📌 Topics to Cover                               
1. Defining Software Quality
   - Meaning of “quality” in the context of software.
   - The difference between the quality of the product and the quality of the process.
   - Views of quality:
     * __User-based__: fitness for purpose.
     * __Developer-based__: conformance to requirements.
     * __Manufacturing-based__: defect prevention and process consistency.
   - Common definitions (ISO 9000, IEEE, etc).
   - Example: comparing “working” vs “high-quality” mobile applications.

2. Challenges of Software Quality
   - Intangibility: Software cannot be physically inspected.
   - Complexity: millions of interacting components.
   - Changing requirements: evolving user needs and technologies.
   - Time and cost constraints: pressure to deliver quickly.
   - Human factors: developer skill, communication, and team coordination.
   - Testing limitations: exhaustive testing is impossible.
   - Maintenance and evolution: quality degradation over time.
   - Discussion Example: Why do software defects still occur even after extensive testing?

3. Software Quality Characteristics
(Based on ISO/IEC 25010 model)
   - Functional Suitability – correctness, appropriateness.
   - Performance Efficiency – response time, resource use.
   - Compatibility – co-existence, interoperability.
   - Usability – learnability, accessibility, satisfaction.
   - Reliability – availability, fault tolerance, recoverability.
   - Security – confidentiality, integrity, authenticity.
   - Maintainability – modularity, reusability, analyzability.
   - Portability – adaptability, installability, replaceability.
   - Class Exercise: Match each characteristic with an example (e.g., usability → clear navigation).

4. Software Quality Factors  
(From McCall, Boehm, and Dromey models)

Category | Example Factors | Description
-- | -- | --
Product Operation | Correctness, Reliability, Efficiency, Integrity, Usability | Affects how well the software performs for users.
Product Revision | Maintainability, Flexibility, Testability | Influence how easily software can be changed or repaired.
Product Transition | Portability, Reusability, Interoperability | Affect adaptability to new environments.

Modern frameworks integrate these factors into Agile quality metrics (e.g., code coverage, defect density)

5. Quality Concepts and Principles
   - Quality Assurance (QA) vs. Quality Control (QC) vs. Testing
   - Prevention over inspection: build quality in early.
   - Continuous improvement: use feedback loops (PDCA Cycle).
   - Process orientation: quality depends on the development process quality.
   - Management responsibility: leadership commitment is crucial.
   - Customer focus: satisfaction and fitness for purpose.
   - Measurement and analysis: metrics drive improvement.
   - Example Concepts:
     * Defect density = defects / KLOC
     * Mean Time Between Failures (MTBF)
     * Continuous Integration/Continuous Delivery (CI/CD) for quality consistency


### 💪 Hands-on Activity
1. Case Study: Review a failed software project (e.g., healthcare or banking) and identify which quality factors were neglected.
2. Group Discussion: “Can software be considered high-quality if it meets deadlines but users are unhappy?”
3. Mini Exercise: Map ISO 25010 characteristics to an existing web or mobile app.


### 🛠️ Tools to Use
1. N/A


### 📚 Suggested Readings / Videos
1. ISO/IEC 25010: System and Software Quality Models.
1. Boehm, B. (1978). Characteristics of Software Quality.
1. IEEE 730: Standard for Software Quality Assurance Plans.


