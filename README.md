# CS-305


Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a financial consultant looking to modernize their operations. They have started development on a RESTful API and would like Global Rain to consult on software security throughout this process. In a later project, a checksum hash algorithm was introduced as a way to verify file integrity.  

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

In these projects, I did a good job at manually reviewing the code for vulnerabilities or opportunities to improve security. This takes a careful attention to detail and the ability to interpret the code from different perspectives. With so much data in our world today, it's important to stay current with regulations should an organization choose to take possession of personal data. They must be constantly making strides to implement secure practices to stay current. By keeping security at such a high level of importance, an organization can show they respect their customers and develop a solid reputation.

What about the process of working through the vulnerability assessment did you find challenging or helpful?

When starting this course, the results returned from the vulnerability report felt overwhelming. I was not familiar with all of the depenencies, and some of the descriptions felt highly technical and unapproachable. After familiarizing myself with the common results, learning how to upgrade or suppress depenencies, and the like, I now feel more comfortable woring with Maven and the depenency check reports.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

Security needs to be approached from many different angles. First, it starts with the code I myself produce. This must follow best practices and use secure patterns. Next, I need to use static testing tools to help me check code that I did not create myself. By scanning the depenencies and referencing a database of known vulnerabilities, I'm able to quickly understand what needs to be done to improve security on this level. 

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

I found a manual review of code that I introduced to be an effective way to check for new vulnerabilities. In a team setting, I would also appreciate a peer review on my code.

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

I'm sure that I will use the Maven depenency check report tool again in the future. As I continute to learn, I will keep integrating the secure practices I learn about into my everyday work. With experience comes wisdom.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

I would showcase the dynamic endpoint that accepted a parameter for name to use when generating the SHA-256 checkcode. This made it possible to easily use a web browser to try many different inputs instead of hardcoding the string into the code.
