# Questions 16-30

### Questions

16. You just received an e-mail from one of your hardware manufacturers notifying you that it will no longer manufacture a certain product and, after the end of the year, you won't be able to send it in for repairs, buy spare parts, or get technical assistance from that manufacturer. What term describes this?
A. End-of-support (EOS)
B. End-of-service-life (EOSL)
C. Deprecation
D. End-of-life (EOL)

17. The confidentiality of sensitive data is protected in different ways depending on the state of the data. Which of the following is the best approach to protecting data in transit?
A. SSL
B. VPN
C. IEEE 802.1X
D. Whole-disk encryption

18. Your boss asks you to put together a report describing probable adverse effects on your assets caused by specific threat sources. What term describes this?
A. Risk analysis
B. Threat modeling
C. Attack trees
D. MITRE ATT&CK

19. A(n) __________ is the graphical representation of data commonly used on websites. It is a skewed representation of characteristics a person must enter to prove that the subject is a human and not an automated tool, as in a software robot.
A. anti-spoofing symbol
B. CAPTCHA
C. spam anti-spoofing symbol
D. CAPCHAT

20. Mark has been asked to interview individuals to fulfill a new position in his company, chief privacy officer (CPO). What is the function of this type of position?
A. Ensuring that company financial information is correct and secure
B. Ensuring that customer, company, and employee data is protected
C. Ensuring that security policies are defined and enforced
D. Ensuring that partner information is kept safe

21. A risk management program must be developed properly and in the right sequence. Which of the following provides the correct sequence for the steps listed?
i. Develop a risk management team.
ii. Calculate the value of each asset.
iii. Identify the vulnerabilities and threats that can affect the identified assets.
iv. Identify company assets to be assessed.
A. i, iii, ii, iv
B. ii, i, iv, iii
C. iii, i, iv, ii
D. i, iv, ii, iii

22. Juan needs to assess the performance of a critical web application that his company recently upgraded. Some of the new features are very profitable, but not frequently used. He wants to ensure that the user experience is positive, but doesn't want to wait for the users to report problems. Which of the following techniques should Juan use?
A. Real user monitoring
B. Synthetic transactions
C. Log reviews
D. Management review

23. Which of the following best describes a technical control for dealing with the risks presented by data remanence?
A. Encryption
B. Data retention policies
C. File deletion
D. Using solid-state drives (SSDs)

24. George is the security manager of a large bank, which provides online banking and other online services to its customers. George has recently found out that some of the bank's customers have complained about changes to their bank accounts that they did not make. George worked with the security team and found out that all changes took place after proper authentication steps were completed. Which of the following describes what most likely took place in this situation?
A. Web servers were compromised through cross-scripting attacks.
B. TLS connections were decrypted through a man-in-the-middle attack.
C. Personal computers were compromised with malware that installed keyloggers.
D. Web servers were compromised and masquerading attacks were carried out.

25. Internet Protocol Security (IPSec) is actually a suite of protocols. Each protocol within the suite provides different functionality. Which of the following is not a function or characteristic of IPSec?
A. Encryption
B. Link layer protection
C. Authentication
D. Protection of packet payloads and the headers

26. In what order would a typical PKI perform the following transactions?
i. Receiver decrypts and obtains session key.
ii. Public key is verified.
iii. Public key is sent from a public directory.
iv. Sender sends a session key encrypted with receiver's public key.
A. iv, iii, ii, i
B. ii, i, iii, iv
C. iii, ii, iv, i
D. ii, iv, iii, i

## Scenario
Tim is the CISO for a large distributed financial investment organization. The company's network is made up of different network devices and software applications, which generate their own proprietary logs and audit data. Tim and his security team have become overwhelmed with trying to review all of the log files when attempting to identify if anything suspicious is taking place within the network. Another issue Tim's team needs to deal with is that many of the network devices have automated IPv6-to-IPv4 tunneling enabled by default, which is not what the organization needs.

### Questions
[Q27-28 are part of above scenario]

27. Which of the following is the best solution to Tim's difficulties handling the quantity and diversity of logs and audit data?
A. Event correlation tools
B. Intrusion detection systems
C. Security information and event management
D. Hire more analysts

28. How could Tim best address the IP version issue described in the scenario?
A. Change management
B. Zero trust
C. Converged protocols
D. Configuration management

29. Which of the following is not a concern of a security professional considering adoption of Internet of Things (IoT) devices?
A. Weak or nonexistent authentication mechanisms
B. Vulnerability of data at rest and data in motion
C. Difficulty of deploying patches and updates
D. High costs associated with connectivity

30. What is an advantage of microservices compared to traditional server-based architectures?
A. Web services support
B. Security
C. Scalability
D. Database connectivity

### Answers

16. D. End-of-life (EOL) for an asset is that point in time when its manufacturer is neither manufacturing nor sustaining it. In other words, you can't send it in for repairs, buy spare parts, or get technical assistance from the manufacturer.

17. B. A virtual private network (VPN) provides confidentiality for data being exchanged between two endpoints. While the use of VPNs may not be sufficient in every case, it is the only answer among those provided that addresses the question.

18. B. Threat modeling is the process of describing probable adverse effects on an organization's assets caused by specific threat sources. This modeling can use a variety of approaches, including attack trees and the MITRE ATT&CK framework.

19. B. A CAPTCHA is a skewed representation of characteristics a person must enter to prove that the subject is a human and not an automated tool, as in a software robot.

20. B. The CPO position was created mainly because of the increasing demands on organizations to protect customer, organizational, and employee data secure and kept secret, which keeps the organization out of criminal and civil courts.

21. D. The correct sequence is: i. Develop a risk management team. ii. Identify company assets to be assessed. iii. Calculate the value of each asset. iv. Identify the vulnerabilities and threats that can affect the identified assets.

22. B. Synthetic transactions are scripted events that mimic the behaviors of real users and allow security professionals to systematically test the performance of critical services. They can detect problems before users notice them.

23. A. Data remanence refers to the persistence of data on storage media after it has been deleted. Encrypting this data is the best of the listed choices because the recoverable data will be meaningless to an adversary without the decryption key.

24. C. While all of these situations could have taken place, the most likely attack type in this scenario is the use of a keylogger. Attackers commonly compromise personal computers by tricking the users into installing Trojan horses that have the capability to install keystroke loggers.

25. B. IPSec is a suite of protocols used to provide VPNs that use strong encryption and authentication functionality. It works at the network layer, not the data link layer.

26. C. In a typical PKI, the sender first needs to obtain the receiver's public key from a public directory, then verify it. The sender encrypts the session key with the receiver's public key. The receiver decrypts the session key with their private key.

27. C. Today, more organizations are implementing security information and event management (SIEM) systems. These products gather logs from various devices and attempt to correlate the log data and provide analysis capabilities.

28. D. Configuration management is a process aimed at ensuring that systems and controls are configured correctly and are responsive to the current threat and operational environments.

29. D. IoT devices run the gamut of cost, from very cheap to very expensive. Cost is the least likely to be a direct concern for a security professional. Lack of authentication, encryption, and update mechanisms are much more significant issues.

30. C. Each microservice lives in its own container and gets called as needed. If you see a spike in orders, you can automatically deploy a new container in seconds and destroy it when no longer needed. This contrasts with traditional servers that have fixed resources available.