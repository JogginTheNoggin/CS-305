# CS-305
## Software Security

### Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a software company that specializes in financial planning solutions. They sought to enhance the security of their Java-based application, specifically requesting the implementation of secure handling of users data. This is an essential step because confidential information is likely to be trasmitted from client to server at some point. The primary soltuion to this was the utilizations of HTTPs to protect data in transmit. We also employed OSWAPS tools to evalutate our source code for CVE's that could compromised the underlying source code. 

### What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

Upon identifying software security vulnerabilities, I effectively prioritized and remediated the most critical issues, such as insecure storage of credentials and susceptibility to injection attacks. Coding securely is crucial because it protects the system from external threats and internal errors that could lead to data breaches or system failures. For Artemis Financial, robust software security adds immense value by safeguarding client data, maintaining trust, and ensuring compliance with financial regulations.

### What part of the vulnerability assessment was challenging or helpful to you?

The dynamic and static testing were particularly helpful in the vulnerability assessment. These methods allowed for a thorough examination of both running applications and source code, helping to identify and mitigate vulnerabilities effectively.

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I enhanced security by implementing a self-signed RSA key and integrating Maven's OWASP tool for continuous vulnerability assessments. For future projects, I plan to continue using OWASP tools and static testing to ensure comprehensive security coverage and timely mitigation of potential threats.

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

To ensure the functionality and security of the code, I conducted security-specific tests like static and dynamic analysis. After refactoring the code, I reran these tests and also employed regression testing to ensure no new vulnerabilities were introduced. This comprehensive testing approach helped maintain both the stability and security of the software.

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

The integration of Maven's OWASP tool proved invaluable, offering automated vulnerability scanning during the development phase. This tool, along with best practices in secure coding such as regular code reviews and adherence to security guidelines, will be beneficial in future security-centric projects.

### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

From this assignment, I could demonstrate my ability to effectively identify and remediate security vulnerabilities, my understanding of secure coding practices, and my skills in using advanced security tools and techniques. Documented case studies or a detailed report of the security enhancements implemented, along with the results of security audits before and after the changes, would be compelling evidence of my capabilities to future employers.
