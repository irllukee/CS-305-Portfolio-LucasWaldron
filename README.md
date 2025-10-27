# CS 305 Project Two – Practices for Secure Software

## Client and Software Requirements
Artemis Financial is a financial consulting company that creates personalized financial plans for its clients. They wanted to modernize their software and strengthen security for transferring client data. My job was to refactor their existing application to include encryption, certificate validation, and checksum verification so data would stay protected during communication.

## Secure Coding and Encryption
I added a SHA-256 checksum and AES encryption to verify data integrity. I also generated a self-signed certificate with Java Keytool to make sure HTTPS communication was working on port 8443. Writing secure code is important because it protects client data and builds trust. Security adds real value to a company by reducing risks and keeping sensitive information safe.

## Challenges and Lessons Learned
The hardest part was setting up the certificate and getting HTTPS to run properly. Once I understood how to generate, export, and apply the certificate, the process made a lot more sense. It taught me how these steps come together in real-world security work.

## Layers of Security
I added multiple layers of protection including encrypted data transmission, file verification through SHA-256, and static vulnerability testing with OWASP Dependency Check. After refactoring, I made sure the application was still functional and that no new vulnerabilities were added.

## Tools and Best Practices
I used Java Keytool, Maven, OWASP Dependency Check, and Eclipse. I followed secure coding practices like using encryption for data in transit and validating certificates. These are all tools and methods I’d use again for future projects.

## What I Can Show Employers
This project shows I can find vulnerabilities, fix them, and prove the software is secure. It also shows I understand how encryption, certificates, and dependency scanning work together to keep data safe.
