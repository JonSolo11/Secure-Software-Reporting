# Secure-Software-Reporting

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial wants to modernize their operations. As a crucial part of the success of their custom software, they also want to use the most current and effective software security. Artemis Financial has a RESTful web application programming interface (API). They are seeking Global Rain’s expertise about how to protect the organization from external threats.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

For this project, we implemented Maven Dependency Check plugin to scan the system for security vulnerabilities as well as manually scanned the system to for vulnerabilities. Secure coding is of utmost importance especially considering our client provides financial services. The potential damages for this system would include both financial and personal data leakage and a violation of company trust from the users. 

What part of the vulnerability assessment was challenging or helpful to you?

Using a tool to quickly run dependency checks that are repeatable is a fantastic way to maintain the system after deployment. This will help ensure that the system remains free of vulnerabilities now and into the future. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

Security was increased by using hashing and secure coding techniques to ensure data isn’t exposed unnecessarily and encrypted when exposed. The dependency check report was the main tool used to identify vulnerabilities paired with manual code scans and secure coding techniques during development. 

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

To ensure the code was functional and secure without new vulnerabilities, I wrote a CheckSum to ensure the output was what was expected. I also compared the new dependency check report to the one generated prior to code refactor to ensure no new vulnerabilities were added to the system. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

For this assignment, we generated SSL certificates, Maven dependency check reports and incorporated encryption. Dependency checsk and encryption will be a standard addition to my systems in the future as software security is a necessary piece of a system. Generating an SSL cert will likely be handled by a CA on deployed systems but their importance can't be overlooked as it is validation to the users that the system is save to use.
