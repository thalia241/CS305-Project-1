# CS305-Project-2

Artemis Financial Secure Software Project

Client Summary: Artemis Financial required an upgrade to its software security to enhance data integrity and encrypted communication, ensuring sensitive client data remains protected. The company sought to implement robust cryptographic measures and secure communication channels to mitigate vulnerabilities and align with industry standards.

Strengths in Identifying Vulnerabilities: I effectively identified vulnerabilities relating to data integrity and secure communication. Using the SHA-256 hashing algorithm, I implemented checksum verification to ensure data integrity. Secure coding is vital as it prevents unauthorized data access and potential breaches, maintaining trust and compliance within the financial sector.

Challenging Aspect of Assessment: Deploying and configuring secure communications through HTTPS and SSL/TLS was particularly challenging yet beneficial. Generating a self-signed certificate and configuring it within Spring Boot required careful setup to ensure encrypted data transmission without compromising functionality.

Enhanced Security Measures: Security layers were increased by implementing SHA-256 hashing for integrity checks and enabling HTTPS with SSL/TLS encryption via self-signed certificates. In future assessments, techniques such as penetration testing and vulnerability scanning tools like OWASP ZAP or Nessus would further strengthen security posture.

Validation of Security and Functionality: Post-refactoring, I conducted extensive functional and security tests including checksum verification, manual dependency checks for secure libraries, and testing HTTPS connections. This approach ensured the application operated securely without introducing new vulnerabilities.

Resources and Tools Utilized: Key resources included Java’s MessageDigest class for secure hashing, Spring Boot’s SSL configuration, and best practices from OWASP and NIST guidelines. These tools and methods provided a structured approach to securing software effectively and efficiently.

Relevance to Future Employers: Future employers will appreciate the hands-on experience with industry-standard cryptographic algorithms, secure communication protocols, and proactive vulnerability mitigation practices. Demonstrated ability in secure code refactoring, dependency management, and comprehensive testing highlights readiness for addressing real-world cybersecurity challenges.
