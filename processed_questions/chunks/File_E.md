# Questions 61-75

## Scenario
Jim works for a large energy company. His senior management just conducted a meeting with Jim's team with the purpose of reducing IT costs without degrading their security posture. The senior management decided to move all administrative systems to a cloud provider. These systems are proprietary applications currently running on Linux servers.

### Questions
[Q61-63 are part of above scenario]

61. Which of the following services would allow Jim to transition all administrative custom applications to the cloud while leveraging the service provider for security and patching of the cloud platforms?
A. IaaS
B. PaaS
C. SaaS
D. IDaaS

62. Which of the following would not be an issue that Jim would have to consider in transitioning administrative services to the cloud?
A. Privacy and data breach laws in the country where the cloud servers are located
B. Loss of efficiencies, performance, reliability, scalability, and security
C. Security provisions in the terms of service
D. Total cost of ownership compared to the current systems

63. Which of the following secure design principles would be most important to consider as Jim plans the transition to the cloud?
A. Defense in depth
B. Secure defaults
C. Shared responsibility
D. Zero trust

64. A group of software designers are at a stage in their software development project where they need to reduce the amount of code running, reduce entry points available to untrusted users, reduce privilege levels as much as possible, and eliminate unnecessary services. Which of the following best describes the first step the team needs to carry out to accomplish these tasks?
A. Attack surface analysis
B. Software development life cycle
C. Risk assessment
D. Unit testing

65. Jenny needs to engage a new software development company to create her company's internal banking software. The software needs to be created specifically for her company's environment, so it must be proprietary in nature. Which of the following would be useful for Jenny to use as a gauge to determine how advanced the various software development companies are in their processes?
A. Waterfall methodology
B. Capability Maturity Model Integration level
C. Auditing results
D. Key performance metrics

66. Which type of organization would be likeliest to implement Virtual eXtensible Local Area Network (VxLAN) technology?
A. Organizations that need to support more than 2,048 VLANs
B. Small and medium businesses
C. Organizations with hosts in close proximity to each other
D. Cloud service providers with hundreds of customers

67. Kerberos is a commonly used access control and authentication technology. It is important to understand what the technology can and cannot do and its potential downfalls. Which of the following is not a potential security issue that must be addressed when using Kerberos?
i. The KDC can be a single point of failure.
ii. The KDC must be scalable.
iii. Secret keys are temporarily stored on the users' workstations.
iv. Kerberos is vulnerable to password guessing.
A. i, iv
B. iii
C. All of them
D. None of them

68. If the annualized loss expectancy (ALE) for a specific asset is $100,000, and after implementation of a control to safeguard the asset the new ALE is $45,000 and the annual cost of the control is $30,000, should the company implement this control?
A. Yes
B. No
C. Not enough information
D. Depends on the annualized rate of occurrence (ARO)

69. ISO/IEC 27000 is a growing family of ISO/IEC information security management system (ISMS) standards. Which of the following provides an incorrect mapping of the individual standard number to its description?
A. ISO/IEC 27002: Code of practice for information security controls
B. ISO/IEC 27003: ISMS implementation guidance
C. ISO/IEC 27004: ISMS monitoring, measurement, analysis, and evaluation
D. ISO/IEC 27005: ISMS auditing guidelines

70. Yazan leads the IT help desk at a large manufacturing company. He is concerned about the amount of time his team spends resetting passwords for the various accounts that each of his organizational users has. All of the following would be good approaches to alleviating this help desk load except which one?
A. Single sign-on (SSO)
B. Just-in-time (JIT) access
C. Password managers
D. Self-service password reset

71. Encryption and decryption can take place at different layers of an operating system, application, and network stack. End-to-end encryption happens within the __________. IPSec encryption takes place at the __________ layer. PPTP encryption takes place at the __________ layer. Link encryption takes place at the __________ and __________ layers.
A. applications, transport, data link, data link, physical
B. applications, transport, network, data link, physical
C. applications, network, data link, data link, physical
D. network, transport, data link, data link, physical

72. Which of the following best describes the difference between hierarchical storage management (HSM) and storage area network (SAN) technologies?
A. HSM uses optical or tape jukeboxes, and SAN is a network of connected storage systems.
B. SAN uses optical or tape jukeboxes, and HSM is a network of connected storage systems.
C. HSM and SAN are one and the same. The difference is in the implementation.
D. HSM uses optical or tape jukeboxes, and SAN is a standard of how to develop and implement this technology.

73. Which legal system is characterized by its reliance on previous interpretations of the law?
A. Tort
B. Customary
C. Common
D. Civil (code)

74. In order to be admissible in court, evidence should normally be which of the following?
A. Subpoenaed
B. Relevant
C. Motioned
D. Adjudicated

75. Which type of authorization mechanism can incorporate historical data into its access control decision-making in real time?
A. Rule-based access control
B. Risk-based access control
C. Attribute-based access control
D. Discretionary access control

### Answers

61. B. In a Platform as a Service (PaaS) contract, the service provider normally takes care of all configuration, patches, and updates for the virtual platform. Jim would only have to worry about porting the applications and running them.

62. B. The biggest advantages of cloud computing are enhanced efficiency, performance, reliability, scalability, and security. The other items listed are all valid concerns that need to be carefully considered.

63. C. Shared responsibility addresses situations in which a cloud service provider is responsible for certain security controls, while the customer is responsible for others. It will be critical for Jim to delineate these responsibilities.

64. A. The aim of an attack surface analysis is to identify and reduce the amount of code accessible to untrusted users. This is the first step in reducing entry points, privilege levels, and unnecessary services.

65. B. The CMMI model outlines the necessary characteristics of an organization's security engineering process. It can be used to evaluate security engineering practices and assess a vendor's capabilities.

66. D. VxLANs are designed to overcome traditional VLAN limitations and are mostly used by cloud service providers with hundreds of customers and large organizations with a global presence.

67. D. These are all legitimate security issues that must be addressed when using Kerberos, including KDC being a single point of failure, scalability requirements, temporary key storage, and password guessing vulnerabilities.

68. A. Yes, the company should implement the control. The calculation is: $100,000 - $45,000 - $30,000 = $25,000 positive value to the organization.

69. D. ISO/IEC 27005 is for information security risk management, not ISMS auditing guidelines (which is covered by ISO/IEC 27007).

70. B. JIT access is about privileged access management and would not help reduce password reset requests. The other options would all help reduce help desk password reset load.

71. C. End-to-end encryption happens within applications. IPSec encryption takes place at the network layer. PPTP encryption takes place at the data link layer. Link encryption takes place at the data link and physical layers.

72. A. HSM provides continuous online backup functionality using optical or tape jukeboxes. SAN is a network of connected storage systems.

73. C. The common law system is based on previous interpretations of the law, consisting of both laws and court decisions in specific cases.

74. B. Evidence must be relevant, complete, sufficient, and reliable to the case at hand to be admissible in court.

75. B. Risk-based access control estimates the risk associated with a request in real time using multiple factors, including historical data, before granting access.