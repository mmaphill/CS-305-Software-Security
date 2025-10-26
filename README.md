# CS-305-Software-Security

### Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a financial consulting company that develops investment, insurance, and retirement planning solutions for its clients. The company needed to ensure that their software would securely transmit and store sensitive data for their clients. The company asked for a security assessment followed by implementation of encryption techniques to protect data and confidentiality. 

### What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I did well in finding possible vulnerabilities by conducting a vulnerability assessment and then implementing encryption to secure data in transit. Coding securely is essential because it helps protects sensitive data, maintain customer trust, and prevents extra costs. Strong software security strengthens a company's reputation, compliance, and financial stability. 

### Which part of the vulnerability assessment was challenging or helpful to you?
The part I found most challenging was interpreting the scan results from the OWASP Dependency-Check. I was working to determine what any genuine threats were and what were false positives. Taking the time to read and understand the vulnerability report was challenging but also helpful. This allowed for me to improve my analyzation skills and gave me a better understanding of how third-party libraries can introduce security risks if not updated regularly. 

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased layers of security by ipmlementing data encryption, adding secure hashing for data integrity, and following secure coding standards to prevent attacks and data leaks. I will continue to use OWASP tools and use penetration testing frameworks to assess vulnerabilities. 

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
To ensure the code was functional and secure, I went through code reviews, unit testing, and re-scanning after the code had been refractored. I verified that there was an SSL certificate that had been correctly configured and that application still ran smoothly without breaking the previous functionality. After making changes, I reran the OWASP Dependency-Check and manual tests to confirm that new vulnerabilities had been introduced. 

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The OWASP Dependency-Check for identifying dependancies and SSL/TLS implemenation for securing communication will be helpful in future tasks. The code review to identify weak spots and input validation/sanitzation to prevent attacks will also be helpful in future assignments/tasks.

### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment
From this assignment, I would show the ran vulnerability assessment, both before and after, and the implemented sercurity improvements that were put in place. These items demonstrate my ability to identify and address real-world security issues, implement encryption, and deliver client-focused security solutions. 
