# CS310Project2

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a financial services company that requires enhanced software secuirty measures to protect sensitive financial data. The primary issue their code base had was lack of encryption and vulnerability to common cyber threats.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I was able to identify mupltiple vulnerabilties like a lack of HTTPS enforcement and input validation. I was thorough with my analysis and used the dependency checker to document vulnerabilities. 

Which part of the vulnerability assessment was challenging or helpful to you?
Secure coding is critical becuase it protects user data, maintains system integrity and reduces risk of breaches. Secure coding practices also promote trust and compliance with industry regulations. Doing the dependency check on the code was helpful to identify what aspects need to be updated like the Spring Boot framework could have an updated version. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I added the encryption and implemented the SHA-256 hash and used the checksum verfication for the integrity of the project. I would like to learn how to implement MFA.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
After refactoring I ran automated tests to confirm functionality and used OWASP to senure no new vulnerabilities were added. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I used OWASP dependency check, SHA-256 hash, and Java keytool for a certificate generation, I also used a maven plug for management. Best practices include input validation and strong secure libraries. 

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
This project demonstrates my ability to identify and fix secuirty vulnerabilities in a real-world scenario. It shows cases my understanding of coding, encryption, and knowledge of industry tools. 
