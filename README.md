# CS 305 – Software Security Portfolio

## Artemis Financial

For this course, I worked with Artemis Financial, a financial consulting company that develops individualized financial plans for its customers. The company wanted to improve the security of its software application and protect sensitive information from security vulnerabilities. My responsibility was to evaluate the existing application, identify potential vulnerabilities, and implement security improvements using secure software development practices.

## Identifying Software Security Vulnerabilities

One area I did particularly well was using both manual analysis and automated dependency checking to identify vulnerabilities within the application and its third-party dependencies. I learned that secure coding is important because vulnerabilities can expose sensitive customer and company information or allow an attacker to compromise an application. For a financial organization such as Artemis Financial, strong software security also helps protect customer trust and reduces business, financial, and reputational risk.

## Challenges and Lessons Learned

One of the most challenging parts of the vulnerability assessment was interpreting the results of the OWASP Dependency-Check report. A scan can identify a large number of potential vulnerabilities, but not every result represents the same level of risk. Learning to evaluate severity, CVE information, affected dependencies, and possible false positives helped me better understand how automated security tools should support careful security analysis.

## Increasing Layers of Security

I increased the application's security by applying multiple security controls instead of relying on a single solution. I implemented HTTPS on port 8443 using a PKCS12 keystore and certificate, created SHA-256 checksum functionality for verifying data integrity, and performed dependency analysis to identify vulnerable third-party components. In future projects, I would continue using OWASP Dependency-Check along with resources such as CVE and the National Vulnerability Database to evaluate vulnerabilities and determine appropriate mitigation strategies.

## Ensuring Functionality and Security

After refactoring the application, I tested the Spring Boot application to verify that it continued to run successfully over HTTPS. I also tested the `/hash` endpoint and confirmed that the application generated the expected SHA-256 checksum. Finally, I ran the dependency-check tool against the application to identify vulnerabilities in its dependencies and determine whether additional security issues needed to be addressed.

## Resources, Tools, and Coding Practices

This project gave me experience with Java, Spring Boot, Maven, SHA-256 hashing, HTTPS/TLS, digital certificates, PKCS12 keystores, OWASP Dependency-Check, CVE information, and vulnerability assessment. I also gained experience using Eclipse and reviewing Maven dependencies. These tools and practices will be useful in future software development projects because they provide a structured way to incorporate security throughout the software development lifecycle.

## Value for Future Employers

I would show future employers my completed Artemis Financial secure software project and report because they demonstrate both technical and analytical security skills. The project shows that I can analyze an existing application, identify software vulnerabilities, configure secure communications, implement cryptographic functionality, perform dependency scanning, and document security recommendations. It also demonstrates my understanding that secure software development requires multiple layers of protection and continuous vulnerability assessment.
