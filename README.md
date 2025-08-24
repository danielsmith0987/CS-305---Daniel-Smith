# CS-305---Daniel-Smith
Module eight Journal
Portfolio Artifact – Artemis Financial Security Project
Artifact Chosen
Artemis Financial Secure Software Report 

Client Summary
Artemis Financial is a financial services company specializing in personalized investment portfolios and secure client transactions. Their software requirements centered on ensuring confidentiality, integrity, and availability of sensitive financial data. The company engaged me to identify and address potential security vulnerabilities in their existing web application, with a focus on secure communications, dependency management, and compliance with industry best practices.

What I Did Well
I conducted a thorough vulnerability assessment using OWASP Dependency‑Check and manual code review, identifying outdated dependencies and insecure configurations. I documented each finding with clear remediation steps. I also implemented secure coding practices such as input validation, HTTPS enforcement, and cryptographic hashing for sensitive data. Coding securely is essential because it protects client trust, prevents costly breaches, and ensures compliance with regulations. Strong software security directly supports a company’s reputation, operational stability, and long‑term success.

Challenges and Helpful Aspects
The most challenging part was distinguishing false positives from legitimate vulnerabilities in automated scan results. This required researching CVE entries, cross‑checking vendor advisories, and applying suppression files for non‑exploitable issues. This process was also one of the most helpful learning experiences, as it deepened my understanding of real‑world vulnerability triage.

Increasing Layers of Security
I applied defense‑in‑depth by:

Enforcing HTTPS with a self‑signed certificate during development.

Updating vulnerable dependencies.

Validating all user inputs.

Configuring secure headers and disabling unnecessary services.

In the future, I would continue using OWASP tools, static code analysis, and penetration testing frameworks to assess vulnerabilities, combined with risk‑based prioritization to choose mitigation techniques.

Ensuring Functionality and Security
After refactoring, I re‑ran the full test suite and repeated vulnerability scans to confirm no new issues were introduced. I also performed regression testing to ensure existing features still worked as intended.

Resources, Tools, and Practices
OWASP Dependency‑Check for automated vulnerability scanning.

Java/Spring Boot secure configuration best practices.

Maven for dependency management.

HTTPS/TLS setup for encrypted communication.

Secure coding guidelines from OWASP and NIST.

These tools and practices will be valuable in future secure software development and DevSecOps workflows.

Portfolio Value
For future employers, this artifact demonstrates:

My ability to conduct a professional vulnerability assessment.

My skill in applying secure coding practices.

My capability to document findings and remediation steps clearly.

My understanding of compliance and industry security standards.
