# CS305-SoftwareSecurity

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial, a firm specializing in investment management and financial planning, sought a custom software solution to address inefficiencies resulting from fragmented systems and outdated tools. They needed a centralized platform to streamline portfolio tracking, improve internal reporting, and ensure data security. 

What did you do well when you found your client's software security vulnerabilities? Why is it essential to code securely? What value does software security add to a company's overall well-being?

To address the software security vulnerabilities at Artemis Financial, I reviewed the codebase and analyzed the system architecture diagram to understand the data flow and identify potential weak points. I conducted static testing to uncover issues such as hardcoded credentials, insecure APIs, and inadequate input validation. Based on my findings, I documented the vulnerabilities in a comprehensive report, prioritized them by risk level, and provided actionable recommendations. 

Secure coding practices are essential for preventing breaches, protecting client data, and ensuring regulatory compliance. Strong software security not only enhances a company's trustworthiness but also reduces the risk of costly incidents and supports long-term operational stability.

Which part of the vulnerability assessment was challenging or helpful to you?

One of the most challenging yet beneficial aspects of the vulnerability assessment was identifying which Common Vulnerabilities and Exposures (CVEs) were false positives. Automated tools often flag potential issues that do not apply to the specific context or configuration of the software. Therefore, I had to carefully evaluate the flagged CVEs against the actual code, dependencies, and system behavior. This process enhanced my ability to critically interpret scan results, allowing me to avoid wasting time on non-issues and concentrate on real threats. As a result, I sharpened both my technical judgment and my efficiency in conducting security assessments.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?


To enhance security, I implemented input validation methods to verify data before converting it into byte arrays. This approach prevents unsafe or malformed input from reaching critical components. Additionally, I conducted regular code reviews, performed dependency checks, and engaged in static testing. I also upgraded outdated design patterns to more secure and maintainable architectures. In the future, I will continue to use these practices in conjunction with tools like Static Application Security Testing (SAST) and Software Composition Analysis (SCA) to identify vulnerabilities. I plan to apply risk-based analysis and threat modeling to determine the most effective mitigation techniques for each situation.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

To ensure that the code and software application were both functional and secure, I first refactored the code by upgrading the communication protocol from HTTP to HTTPS. I also implemented the stronger SHA3-512 hashing algorithm to enhance data integrity. After making these changes, I conducted a dependency check to identify any vulnerabilities or false positives in third-party libraries. Once the refactoring was complete, I repeated the dependency check to confirm that no new vulnerabilities had been introduced. This combination of code improvements and thorough testing helped maintain both functionality and security throughout the development process.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Since this was only the second time I implemented algorithms in this program, I found it essential to strengthen my problem-solving skills by following a clear learning progression. First, I focused on thoroughly learning core concepts. Next, I practiced through coding exercises to reinforce those ideas. Finally, I applied what I had learned in personal projects. This approach helped me build a deeper understanding and practical experience, which will be invaluable for future assignments. 

Additionally, using tools such as dependency checkers and static analysis software, along with adhering to best practices like thorough code reviews and secure design patterns, proved to be crucial. Together, these resources and habits form a strong foundation for writing safe and reliable code in any future project.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

Through this assignment, I can demonstrate to future employers my ability to identify and address software security vulnerabilities through thorough code reviews and static testing. I will highlight my experience in refactoring code to implement stronger security measures, such as upgrading HTTP connections to HTTPS and integrating advanced hashing algorithms like SHA3-512. Additionally, I can demonstrate my skills in utilizing dependency-checking tools to identify and mitigate vulnerabilities, as well as my disciplined approach to ensuring that changes do not introduce new risks. Overall, this project showcases my problem-solving abilities, attention to secure coding practices, and ability to balance both functionality and security in complex software systems.
