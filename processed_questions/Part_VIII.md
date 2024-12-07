# Part VIII: Software Development Security

## Chapter 24: Software Development

### Scenario 1
Francisca is the new manager of the in-house software designers and programmers. She has been telling her team that before design and programming on a new product begins, a formal architecture needs to be developed. She also needs this team to understand security issues as they pertain to software design. Francisca has shown the team how to follow a systematic approach that allows them to understand different ways in which the software products they develop could be compromised by specific threat actors.

### Questions

10. A software development company released a product that committed several errors that were not expected once deployed in their customers' environments. All of the software code went through a long list of tests before being released. The team manager found out that after a small change was made to the code, the program was not tested before it was released. Which of the following tests was most likely not conducted?
A. Unit
B. Compiled
C. Integration
D. Regression

48. Which of the following best describes what an architecture is in the context of this scenario?
A. Tool used to conceptually understand the structure and behavior of a complex entity through different views
B. Formal description and representation of a system and the components that make it up
C. Framework used to create individual architectures with specific views
D. Framework that is necessary to identify needs and meet all of the stakeholder requirements

49. Which of the following best describes the approach Francisca has shown her team as outlined in the scenario?
A. Attack surface analysis
B. Threat modeling
C. Penetration testing
D. Double-blind penetration testing

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

106. Khadijah is leading a software development team for her company. She knows the importance of conducting an attack surface analysis and developing a threat model. During which phase of the software development life cycle should she perform these actions?
A. Requirements gathering
B. Testing and validation
C. Release and maintenance
D. Design

108. Applications may not work on systems with specific processors. Which of the following best describes why an application may work on an Intel processor but not on an AMD processor?
A. The application was not compiled to machine language that is compatible with the AMD architecture.
B. It is not possible for the same application to run on both Intel and AMD processors.
C. The application was not compiled to machine language that is compatible with the Windows architecture.
D. Only applications written in high-level languages will work on different processor architectures.

109. Which of the following is not true about software libraries?
A. They make software development more efficient through code reuse.
B. They are typically accessed through an application programming interface (API).
C. They almost never introduce vulnerabilities into programs that use them.
D. They are used in most major software development projects.

110. Kim is tasked with testing the security of an application but has no access to its source code. Which of the following tests could she use in this scenario?
A. Dynamic application security testing
B. Static application security testing
C. Regression testing
D. Code review

### Answers

10. D. Regression testing should take place after a change to a system takes place, retesting to ensure functionality, performance, and protection.

48. A. An architecture is a tool used to conceptually understand the structure and behavior of a complex entity through different views. An architecture provides different views of the system, based upon the needs of the stakeholders of that system.

49. B. Threat modeling is a systematic approach used to understand how different threats could be realized and how a successful compromise could take place. A threat model is a description of a set of security aspects that can help define a threat and a set of possible attacks to consider.

64. A. The aim of an attack surface analysis is to identify and reduce the amount of code accessible to untrusted users. The basic strategies of attack surface reduction are to reduce the amount of code running, reduce entry points available to untrusted users, reduce privilege levels as much as possible, and eliminate unnecessary services.

65. B. The Capability Maturity Model Integration (CMMI) model outlines the necessary characteristics of an organization's security engineering process. It can be used to evaluate security engineering practices and identify ways to improve them. It can also be used by customers in the evaluation process of a software vendor.

106. D. Attack surface analysis and threat modeling should be performed during the design phase, before coding begins. This allows security considerations to be built into the architecture and design of the software.

108. A. Applications must be compiled into machine language that is compatible with the target processor architecture. While Intel and AMD processors are both x86 compatible, there can be specific architectural differences that require different machine code optimizations.

109. C. Software libraries can and often do introduce vulnerabilities into programs that use them. This is why it's important to carefully vet third-party libraries and keep them updated with security patches.

110. A. Dynamic application security testing (DAST) is a type of security testing that examines an application while it is running, without access to source code. This is in contrast to static application security testing (SAST) which requires access to source code.

## Chapter 25: Secure Software

### Questions

37. Which of the following is not considered a secure coding practice?
A. Validate user inputs
B. Default deny
C. Defense in depth
D. High (tight) coupling

111. Hanna is a security manager of a company that relies heavily on one specific operating system. The operating system is used in the employee workstations and is embedded within devices that support the automated production line software. She has uncovered a vulnerability in the operating system that could allow an attacker to force applications to not release memory segments after execution. Which of the following best describes the type of threat this vulnerability introduces?
A. Injection attacks
B. Memory corruption
C. Denial of service
D. Software locking

### Answers

37. D. High (tight) coupling is not considered a secure coding practice. Coupling is a measurement that indicates how much interaction one module requires to carry out its tasks. High coupling means a module depends upon many other modules, which increases complexity and the potential for security vulnerabilities.

111. B. The scenario describes a memory corruption vulnerability where applications fail to properly release memory segments after execution. This can lead to memory leaks and potential security vulnerabilities.
