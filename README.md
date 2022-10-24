# CS305
Software Security 22EW1

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
        Data breaches and security breakdowns are amongst every company’s largest fears; in lieu of waiting until an attack targets Artemis Financial, some proactivity has the company looking to start encrypting data sooner rather than later. The value of secure communications to Artemis financial is imperative as the firm develops individualized financial plans for their clients, which include savings, retirement, investments, and insurance. The individualized plans include a lot of sensitive data, which the company would not want to be transferred through an unsecure process, and potentially end up in the wrong hands.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
        I believe that one of my strengths when finding my client’s software security vulnerabilities is detailed research, allowing for a competent proposal of mitigations due to confidence in my understanding of the results; in adjunct this allows clear and concise documenting of known vulnerabilities. Secure coding practices are imperative to creating scalable and user-trusted projects, while also keeping company data secure. If secure coding practices are enabled from the beginning of the project, the cost of maintaining becomes considerably less than attempting to tackle security issues as they arise. Through delivering secure software both the company and the user can breathe a bit of a sigh of relief, as the deployed software will be less susceptible to security vulnerabilities; however, if a vulnerability were to appear the company will be better equipped to roll out a timely patch. 

What part of the vulnerability assessment was challenging or helpful to you?
    	The parts of the vulnerability assessment that was helpful for me was generating an OWASP Dependency Check Report via Maven, this allowed a clear breakdown of current vulnerabilities, including descriptions, mitigation possibilities, and CVSS severity. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
    	I increased layers of security by implementing a SHA-256 cipher algorithm to encrypt data, rather than storing plaintext as source code. In the future I would continue to use Maven to assess for vulnerabilities as I am familiar with its functionality, and it appears to be a seamless integration via an Eclipse plug-in. 
        
How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
    	I ensured that the refactored code was secure by generating a secure webpage, which checked to ensure that the cipher algorithm was correct. After the security check was complete I ran another Maven dependency check to see if there were additional, un-suppressed vulnerabilities.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
        Some resources I used that will be useful in future tasks are Maven, which was implemented via OWASP and used to generate a Vulnerability Report. I believe this tool will be imperative when it comes to checking for potential weaknesses in coding practices, which could result in a data breach, or DDoS. 

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
        If future employers were to ask for examples to show my knowledge, I would show the Vulnerability Assessment Report, as this highlights a manual review of each individual CPE, this report also highlights mitigations and practices of Static Testing.

