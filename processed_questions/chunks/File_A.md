# Questions 1-15

## Scenario 1
Josh has discovered that an organized hacking ring in China has been targeting his company's research and development department. If these hackers have been able to uncover his company's research findings, this means they probably have access to his company's intellectual property. Josh thinks that an e-mail server in his company's DMZ may have been successfully compromised and a rootkit loaded.

### Questions
[Q1-3 are part of above scenario]

1. Based upon this scenario, what is most likely the biggest risk Josh's company needs to be concerned with?
A. Market share drop if the attackers are able to bring the specific product to market more quickly than Josh's company.
B. Confidentiality of e-mail messages. Attackers may post all captured e-mail messages to the Internet.
C. Impact on reputation if the customer base finds out about the attack.
D. Depth of infiltration of attackers. If attackers have compromised other systems, more confidential data could be at risk.

2. The attackers in this situation would be seen as which of the following?
A. Vulnerability
B. Threat
C. Risk
D. Threat agent

3. If Josh is correct in his assumptions, which of the following best describes the vulnerability, threat, and exposure, respectively?
A. E-mail server is hardened, an entity could exploit programming code flaw, server is compromised and leaking data.
B. E-mail server is not patched, an entity could exploit a vulnerability, server is hardened.
C. E-mail server misconfiguration, an entity could exploit misconfiguration, server is compromised and leaking data.
D. DMZ firewall misconfiguration, an entity could exploit misconfiguration, internal e-mail server is compromised.

4. Aaron is a security manager who needs to develop a solution to allow his company's mobile devices to be authenticated in a standardized and centralized manner using digital certificates. The applications these mobile clients use require a TCP connection. Which of the following is the best solution for Aaron to implement?
A. TACACS+
B. RADIUS
C. Diameter
D. Mobile IP

5. Terry is a security manager for a credit card processing company. His company uses internal DNS servers, which are placed within the LAN, and external DNS servers, which are placed in the DMZ. The company also relies on DNS servers provided by its service provider. Terry has found out that attackers have been able to manipulate several DNS server caches to point employee traffic to malicious websites. Which of the following best describes the solution this company should implement?
A. IPSec
B. PKI
C. DNSSEC
D. MAC-based security

6. Which of the following is not a key provision of the GDPR?
A. Requirement for consent from data subjects
B. Right to be informed
C. Exclusion for temporary workers
D. Right to be forgotten

7. Jane is suspicious that an employee is sending sensitive data to one of the company's competitors but is unable to confirm this. The employee has to use this data for daily activities, thus it is difficult to properly restrict the employee's access rights. In this scenario, which best describes the company's vulnerability, threat, risk, and necessary control?
A. Vulnerability is employee access rights, threat is internal entities misusing privileged access, risk is the business impact of data loss, and the necessary control is detailed network traffic monitoring.
B. Vulnerability is lack of user monitoring, threat is internal entities misusing privileged access, risk is the business impact of data loss, and the necessary control is detailed user activity logs.
C. Vulnerability is employee access rights, threat is internal employees misusing privileged access, risk is the business impact of confidentiality, and the necessary control is multifactor authentication.
D. Vulnerability is employee access rights, threat is internal users misusing privileged access, risk is the business impact of confidentiality, and the necessary control is CCTV.

8. Which of the following best describes what role-based access control offers organizations in reducing administrative burdens?
A. It allows entities closer to the resources to make decisions about who can and cannot access resources.
B. It provides a centralized approach for access control, which frees up department managers.
C. User membership in roles can be easily revoked and new ones established as job assignments dictate.
D. It enforces an enterprise-wide security policy, standards, and guidelines.

9. Mark works for a large corporation operating in multiple countries worldwide. He is reviewing his company's policies and procedures dealing with data breaches. Which of the following is an issue that he must take into consideration?
A. Each country may or may not have unique notification requirements.
B. All breaches must be announced to affected parties within 24 hours.
C. Breach notification is a "best effort" process and not a guaranteed process.
D. Breach notifications are avoidable if all PII is removed from data stores.

10. A software development company released a product that committed several errors that were not expected once deployed in their customers' environments. All of the software code went through a long list of tests before being released. The team manager found out that after a small change was made to the code, the program was not tested before it was released. Which of the following tests was most likely not conducted?
A. Unit
B. Compiled
C. Integration
D. Regression

11. Which of the following should not be considered as part of the supply chain risk management process for a smartphone manufacturer?
A. Hardware Trojans inserted by downstream partners
B. ISO/IEC 27001
C. Hardware Trojans inserted by upstream partners
D. NIST Special Publication 800-161

12. Data sovereignty is increasingly becoming an issue that most of us in cybersecurity should address within our organizations. What does the term data sovereignty mean?
A. Certain types of data concerning a country's citizens must be stored and processed in that country.
B. Data on a country's citizens must be stored and processed according to that country's laws, regardless of where the storing/processing takes place.
C. Certain types of data concerning a country's citizens are the sovereign property of that data subject.
D. Data on a country's citizens must never cross the sovereign borders of another country.

## Scenario 2
Jack has just been hired as the security officer for a large hospital system. The organization develops some of its own proprietary applications. The organization does not have as many layers of controls when it comes to the data processed by these applications, since it is assumed that external entities will not understand the internal logic of the applications. One of the first things that Jack wants to carry out is a risk assessment to determine the organization's current risk profile. He also tells his boss that the hospital should become ISO certified to bolster its customers' and partners' confidence in its risk management processes.

### Questions
[Q13-15 are part of above scenario]

13. Which of the following approaches has been implemented in this scenario?
A. Defense-in-depth
B. Security through obscurity
C. Information security management system
D. ISO/IEC 27001

14. Which ISO/IEC standard would be best for Jack to follow to meet his goals?
A. ISO/IEC 27001
B. ISO/IEC 27004
C. ISO/IEC 27005
D. ISO/IEC 27006

15. Which standard should Jack suggest to his boss for compliance with best practices regarding storing and processing sensitive medical information?
A. ISO/IEC 27004
B. ISO/IEC 27001
C. ISO/IEC 27799
D. ISO/IEC 27006

### Answers

1. D. While they are all issues to be concerned with, risk is a combination of probability and business impact. The largest business impact out of this list and in this situation is the fact that intellectual property for product development has been lost. If a competitor can produce the product and bring it to market quickly, this can have a long-lasting financial impact on the company.

2. D. The attackers are the entities that have exploited a vulnerability; thus, they are the threat agent.

3. C. In this situation the e-mail server most likely is misconfigured or has a programming flaw that can be exploited. Either of these would be considered a vulnerability. The threat is that someone would find out about this vulnerability and exploit it. The exposure is allowing sensitive data to be accessed in an unauthorized manner.

4. C. Diameter is a protocol that has been developed to build upon the functionality of RADIUS and TACACS+ while overcoming some of their limitations, particularly with regard to mobile clients. RADIUS uses UDP and cannot effectively deal well with remote access, IP mobility, and policy control. Mobile IP is not an authentication and authorization protocol, but rather a technology that allows users to move from one network to another and still use the same IP address.

5. C. DNS Security Extensions (DNSSEC, which is part of the many current implementations of DNS server software) works within a PKI and uses digital signatures, which allows DNS servers to validate the origin of a message to ensure that it is not spoofed and potentially malicious. DNSSEC allows DNS servers to send and receive only authenticated and authorized messages between themselves and thwarts the attacker's goal of poisoning a DNS cache table.

6. C. The General Data Protection Regulation (GDPR) impacts every organization that holds or uses European personal data both inside and outside of Europe. There is no exclusion based on the nature of the relations between the data subjects and the data controllers and processors.

7. B. A vulnerability is a lack or weakness of a control. The vulnerability is that the user, who must be given access to the sensitive data, is not properly monitored to deter and detect a willful breach of security. The threat is that any internal entity might misuse given access. The risk is the business impact of losing sensitive data. One control that could be put into place is monitoring so that access activities can be closely watched.

8. C. A role-based access control (RBAC) model uses a centrally administrated set of controls to determine how subjects and objects interact. An administrator does not need to revoke and reassign permissions to individual users as they change jobs. Instead, the administrator assigns permissions and rights to a role, and users are plugged into those roles.

9. A. Many (but not all) countries have data breach notification requirements, and these vary greatly in their specifics. While some countries have very strict requirements, others have laxer requirement, or lack them altogether. This requires the security professional to ensure compliance in the appropriate territory.

10. D. Regression testing should take place after a change to a system takes place, retesting to ensure functionality, performance, and protection.

11. B. ISO/IEC 27001 is a standard covering information security management systems (ISMSs), which is a much broader topic than supply chain risk management. The other three options are better answers because they are directly tied to this process: NIST Special Publication 800-161 directly addresses supply chain risk, and the insertion of hardware Trojans could happen at any point in the chain.

12. B. Various countries have data sovereignty laws that stipulate that anyone who stores or processes certain types of data (typically personal data on their citizens), whether or not they do so locally, must comply with those countries' laws. Data localization laws, on the other hand, require certain types of data to be stored and processed in that country.

13. B. Security through obscurity depends upon complexity or secrecy as a protection method. Some organizations feel that since their proprietary code is not standards based, outsiders will not know how to compromise its components. This is an insecure approach. Defense-in-depth is a better approach.

14. C. ISO/IEC 27005 is the international standard for risk assessments and analysis.

15. C. ISO/IEC 27799 is a guideline for information security management in health organizations. It deals with how organizations that store and process sensitive medical information should protect it.