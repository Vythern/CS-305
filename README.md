# CS-305
Repos and assignments from CS-305 class
December 8th, added readme.  

December 14th:  Added Q/A.  

Briefly summarize your client, Artemis Financial, and their software requirements. 
Artemis Financial is a consulting cmpany which helps customers to plan out their finances, and to manage their savings, stocks, and other assets.  Their goal as of the writing of this document is to integrate modern security practices and evaluate their software for threats and loopholes that might be impacting the health of the service.  

Who was the client? What issue did they want you to address?
The client was Artemis Financial, and their goals are listed above.  

What did you do very well when you found your client’s software security vulnerabilities?  
I was sort of lost for a while on how to read and interpret the information I received from the maven tests and dependency checks, but I think that after doing a signficant amount of research I actually genuinely figured out what the problems were.  Intuition was one thing, and my guess was correct, but the research proved it to be true- that is- the software was outdated and needed security updates.  

Why is it important to code securely? What value does software security add to a company’s overall wellbeing?  
Insecure code creates a cascading laundry list of problems that builds up over time the longer the issue is left unchecked, as more and more of the system begins to rely on the continued functionality of the insecure code.  One day it'll be fine, and the next, a full remote access / loss of control due to an overlooked workaround from the early days of the program's development.  

What part of the vulnerability assessment was challenging or helpful to you?
I found it really difficult to read the vulnerability assessment initially.  The links on the page were intuitive enough though that it soon became evident exactly what the dependency check was doing and how it worked.  

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
There were originally a lot more vulnerabilities, but after a quick round of updates and layers of obfuscation, my confidence in the software was significantly higher.  

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
The same way you initially check for issues- just run through the tests again.  

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I suppose the only real answer is the same ones I always do?  I'm not really sure specifically what they are, but I know them when I see them.  If you asked me over a decade ago when I learned to code and how to format things and what was bad I might be able to give a better answer but right now it's mostly just instinctual.  

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?  
The part of this course that I am taking away the most is without a doubt the vulnerability checks.  I've done plenty of programming on my own time, but it's all been applications that aren't really possible to attack, I guess.  Singleplayer videogames, made my own calculator for calculus problems, etcetera- you can't really have a whole lot of vulnerabilities there.  So when I ran the tests it was a whole new can of worms, daunting at first, but not so much that I felt lost, and I immediately picked up on it and enjoyed learning more about it.  I'll definitely be showing off the tests and experience I gained from this course as it pertains to dependency and vulnerability tests.  
