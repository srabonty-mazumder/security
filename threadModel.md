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

## Threat Modeling Cheat Sheet (OWASP CheatSheets Series Team 2021): 
Threat model cheat sheet at first explain what is thread model and the four key questions that are already summarised above. Then mention below things: 
### Advantages of Threat Model: 
The threat Model has many advantages some of the main advantages are given below. 
#### Identify Risk Early-On: 
From the design phase threat model looks to identify potential security issues. This model allows security to be “build-into” in  a system than “bolted on”. It is a more effective way to identify and fix risk after a system is in production. 
#### Prioritization of Security Efforts:
Understanding different kinds of risk matters organizations could ensure where time and budget should be spent most effectively. 
#### Help to reach the business goal: 
Threat model integrating security into the business context based on the value of the asset and  overall impact of potential threats on the business. That basically ensures business security more and helps to reach company goals.  
### Identifying and Ranking threat:  
Analyzing  the question this time will break the threat model  into four basic steps: application decomposition, threat identification and ranking, mitigations, and review and validation. 
Method: STRIDE is a mature and popular threat modeling technique that is. Each STRIDE threat is considered a violation of certain security  attributes. The attributes are given below: 

•	Spoofing – Authenticity – attract to steal authentication to a legitimate user.
•	Tampering – integrity  - abuses the application to perform unintended updates to a database.
•	Repudiation - Non-repudiability – Attract to manipulates log. 
•	Information Disclosure -Confidentiality - Hack to extract data from the database.
•	Denial of Service – Availability – By performing many failed authentication attempts an attacker locks a legitimate user out of their account.
•	Elevation of Privileges ¬ - Authorization - (e.g., tampered JWT).

### Challenge of Threat Model: 
•	Lack of sufficient knowledge and experience in the field of security could hinder to implement threat model effectively. Without proper training, experience and understanding of basic security principles, developer might overlook potential threats.

•	Another challenge is Threat model could be complex and time-consuming. With a tight schedule, it is difficult to follow this model's systematic approach and in-depth analysis. 

•	Finally challenge lack of communication. Without proper communication among the security team, development team, and other stakeholders, the threat model can be incomplete or misdirected.  

#  a) Security hygiene:
### What basic security practices should everyone follow?
To protect ourselves from unwanted accidents or hazards everyone should follow some basic security practices for example for daily life in winter time in Finland everyone should ware good winter clothes, a cap, and a boot to protect themselves from extreme cold weather. In this way, it’s very important to follow basic security practices to protect our personal information and digital devices from various threats like hacking, data breaches, and identity theft. Some basic security practices that everyone should practice are listed below: 
•	Use strong and unique passwords in our email and social media accounts. 

•	To ensure extra protection of our device, mobile, and different accounts we could use Multi-Factor Authentication (MFA).

•	Regularly update operating systems, applications, and devices to fix security vulnerabilities

•	Use biometrics lock such as face or fingerprint in our device to prevent device hacks or another security hazards. 

•	Regularly back up important files to cloud or one drive service. 

•	Avoid visiting suspicious (scam page) websites from devices and enable device auto-fill-up password. 

•	for sensitive files, emails, and communications operate encryption to protect against unauthorized access.

•	More conscious of using public Wifi networks unless using a Virtual Private Network (VPN).

•	More conscious of sharing email password, bank info, and ID info through social media or email. 

### Security practices companies should follow:  
When it comes to a company perspective hygienic security practices are more important and every company or average Joe should practices this. Some basic security practices that the company should practice are listed below: 
•	Maintain a strong and complex password policy and regular bae change of that.

•	To reduce risk, unauthorized access, and hack company should enable Multi-Factor Authentication (MFA). 

•	Apply automated patch management systems to ensure that all devices and software are up to date across the organization.

•	Every company should maintain automated and encrypted backups with regular testing to recover any accidental situation. 

•	Giving employees regular training regarding security issues, educated them regarding different scam and threat issue. 

•	Apply various monitoring tools as well security Operations Center (SOC)  to identify and action against potential threats in real time.

•	Regularly conduct security audits and penetration testing to identify possible actions to prevent potential vulnerability.

•	Encrypt sensitive data both rest and in transit among all employee's devices and communication channels. 

•	Use antivirus, firewall, and intrusion detection systems on all devices of the company.

•	Overall company should have a clear plan and procedure to respond to any data breaches, ransomware attacks, and other incidents. 

#  b) Make-belief boogie-man - Imaginary Company Name: WhatIf Insurance 
Business Description: WhatIf is a mid-sized insurance company that offers life, health, and property insurance for individuals and small companies. They have an online platform where customers can apply, claim, and interact with customer support. For risk assessment and claim processing company uses an AI-driven algorithm. 

#### Threat model for WhatIf Insurance: 

#### 1. What Are We Working On?
Our Assets: (key Asset)

•	Personal data: Most sensitive asset is customer personal identification information such as name, address, Social security number, property information and medical history. 

•	Policy data: Detail records of every policy, instalments database and claim history. 

•	Claim processing system: Proprietary algorithms and data pipelines used to process claims and assess risks.

Other Asset 

•	Employee data: HR record, all payroll, and internal communication documents. 

•	Employees all work-station and laptops for day-to-day customer support. 

•	Cloud infrastructure: Company’s all application webpage and app hosting, databases and backup system. 

Among these assets most prioritized assets is customer information, personal data, policy data,  the claims processing system, and customer interface ( website and app).

### Security Supports Business: 

If the Insurance business model depends on customer trust? Protecting sensitive personal data is critical for compliance (e.g., GDPR, HIPAA) and maintaining the reputation needed to attract and retain customers. Ensuring the availability and integrity of the claims processing system is also crucial for continuous business operations.

### System Diagram:

                  [Customer Web Portal]

                           |
                    
             [Claims & Policy Management System]
            
                          |
                    
                [Core Backend Infrastructure]
          
               /         |          |         \
        
         [Database] [AI Models] [Cloud Backup] [APIs]
              |                 |                |     
       [PII Data]   [Risk Assessment]    [Third-party Integrations]


### Customer Perspective: 

Customer touchpoint: Customers primarily use websites and apps to apply for insurance reviews, pay installments and claim policies etc. It’s the main touch point.

Customer expectation: Customers want fast, reliable, secure, and easy-to-claim policy service from our company.  

### 2. What can go wrong?

Identify risk using  STRIDE:

• Spoofing: Gaining access to customer accounts or policy data an attacker impersonates a legitimate user, 

• Tampering: Hack policy information or claims records, leading to fraudulent payouts or denial of legitimate claims.

• Repudiation: A customer or attacker denies making certain actions (e.g., submitting a fraudulent claim), making it difficult to resolve disputes.

• Information Disclosure: Sensitive medical history is leaked due to a data breach, leading to regulatory fines and reputational damage.

• Denial of Service (DoS): An attack could interrupt access to the customer portal, preventing users from managing policies or filing claims.

• Elevation of Privilege: A low-level user or attacker gains admin-level access, enabling widespread data theft or system compromise.

Examples of Risk: 
 
• Phishing Attacks (High Risk): Employees or customers might be trapped to revealing login credentials, leading to unauthorized access to sensitive data.

• Ransomware (High Risk): This this hack, attackers might encrypt key systems or databases.

• API Exploits (Medium Risk): APIs that are used for third-party integrations could be exploited to access sensitive customer data.

• Insider Threat (Medium Risk): A disgruntled employee with access to sensitive data could leak or manipulate customer information.

### Prioritized risk: 
Phishing attacks and ransomware are high valued risks for our company. It would cause huge financial damage, operational disruption, and lost of company good well. 

### Specific threat actor: 
The financial and insurance sectors are targeted by cybercriminals because they have sensitive property information, personal and health information that might be easy to do frauded activities. Especially the insurance sector that’s why targeted by attracters. 
Business Continuity Concerns: If WhatIf insurance faces many times downtime or a significant data breach, our company could face customer churn, legal liabilities, and regulatory fines. Trust is essential in this industry, and even a single very low financial hacking incident could lead to irreversible damage.

### 3. What Are We Going to Do About It?

#### Mitigation Strategies: 

Some strategies that our company should follow to reduce any attract or hack from entry point such as:  

•	Reduce Attack Surface: Implementing very strict access controls, enforce the principle of least privilege, and regularly audit system permissions.

•	Strengthen Authentication and Access Control: Require multi-factor authentication (MFA) such as an authentication app  for all customer and employee accounts as well as regularly monitor for unauthorized access attempts 

•	Employee Training: Security awareness training  should be conducted regularly to reduce the risk of phishing attacks and social engineering.

•	Ransomware Protection:   It is necessary to implement robust backup strategies with offline backups and test recovery procedures regularly. To detect and block ransomware attacks using endpoint detection and response (EDR) tools 

•	API Security: Perform regular security assessments on all APIs, ensuring they are properly authenticated, rate-limited, and secured against common attacks (e.g., injection attacks).

### META: Mitigate, Eliminate, Transfer, Accept
•	Mitigate: Implementing MFA and security training by reducing the likelihood of phishing 

•	Eliminate: Decommission outdated or unused systems that could be exploited.

•	Transfer: To cover any future financial losses from incidents like data breaches or ransomware, purchase cybersecurity insurance.

•	Accept: Some low-impact risks for example minimal service disruptions in the website or app may be accepted if the cost of mitigation is too high.

### 4. Did We Do a Good Enough Job?
Ongoing Security Measures:

•	Security Audits and Penetration Testing: Regularly for example quarterly both internal and third-party security assessments to identify and patch vulnerabilities.

•	Continuous Threat Modeling: Review and update threat model whenever new features, integrations, or business processes are introduced.

•	Monitoring and Incident Response: built-up continuous monitoring with alerting systems that track suspicious activity, failed login attempts, and data access patterns. Ensure that an incident response plan is in place and regularly tested.

•	Customer Feedback Loop: Regularly survey customers to understand their experience and any potential security concerns they may have faced.

Security is a Process: Threat modeling at WhatIf  is treated as an ongoing process. In the advanced world, new threats constantly emerge every day and the company must continuously adapt its defense policy. Regular updates, assessments, and stakeholder engagement are critical to maintaining a strong security posture while supporting business growth.













