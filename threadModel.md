#Summarized Reading and Video Part: 
## Threat modeling manifesto (Braiterman et al 2020)
#### What is the Threat model:
In short way threat model estimates problems in an expensive way which means identifying the problem before writing a proper code and installing any chip or concrete method of eliminating the threat. The threat model is a set of methods that allow us to think about security at that point so that we can build the security that needs to be. 
#### Who should use the Threat Model:
Anyone who is concerned about privacy, safety, and security. 
#### How anyone uses threat modeling Manifesto:  
Like the Agile Manifesto format threat modeling also follows by identifying two guidelines: 
•	Value: Value is something that is very important or relevant for a person or a company. 
•	Principles: The principle describes the fundamental truth such as fundamental, primary, or general truths, patterns that are highly recommended, and anti-patterns that should be avoided. 

## Welcome to the Worlds Shortest Threat Modeling Course (Shostack 2022):
In this short course, the author explains the threat model and four key questions to follow up model. 
According to the threat modeling manifesto threat modeling process should answer the following four questions. 
1.	What are we working on? 
1st Identify what needs to protect for example customer information, ID, Banking information etc. 
Then System Overview means mapping how the system works as well as data flow and components. 
Finally, prioritization to find out the most important asset. 
2.	What can go wrong?
Identify threats using mostly like STRIDE (Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege) to discover potential risks. 
Analyze every threat and impact.
Imagine who might target the system, their tactics, techniques, and procedures (TTPs).

3.	What are we going to do about it?
               Addressing each threat - mitigate, eliminate, transfer, or accept (META).
Security control by implementing measure like access controls, encryption, and monitoring to reduce risk.

4.	Did We Do a Good Enough Job?
Conduct regular audits, penetration testing, and updates to the threat model.
Finally, the threat model is a continuous process it is not a one-time task. It moves on as the system and threat landscape change.

# Threat Modeling Cheat Sheet (OWASP CheatSheets Series Team 2021): 
Threat model cheat sheet at first explain what is thread model and the four key questions that are already summarised above. Then mention below things: 
### Advantages of Threat Model: 
The threat Model has many advantages some of the main advantages are given below. 
#### Identify Risk Early-On: From the design phase threat model looks to identify potential security issues. This model allows security to be “build-into” in  a system than “bolted on”. It is a more effective way to identify and fix risk after a system is in production. 
#### Prioritization of Security Efforts:
Understanding different kinds of risk matters organizations could ensure where time and budget should be spent most effectively. 
#### Help to reach the business goal: Threat model integrating security into the business context based on the value of the asset and  overall impact of potential threats on the business. That basically ensures business security more and helps to reach company goals.  
### Identifying and Ranking threat:  Analyzing  the question this time will break the threat model  into four basic steps: application decomposition, threat identification and ranking, mitigations, and review and validation. 
Method: STRIDE is a mature and popular threat modeling technique that is. Each STRIDE threat is considered a violation of certain security  attributes. The attributes are given below: 

•	Spoofing – Authenticity – attract to steal authentication to a legitimate user.
•	Tampering – integrity  - abuses the application to perform unintended updates to a database.
•	Repudiation - Non-repudiability – Attract to manipulates log. 
•	Information Disclosure -Confidentiality - Hack to extract data from the database.
•	Denial of Service – Availability – By performing many failed authentication attempts an attacker locks a legitimate user out of their account.
•	Elevation of Privileges ¬ - Authorization - (e.g., tampered JWT).







