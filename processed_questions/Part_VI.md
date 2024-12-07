# Part VI: Security Assessment and Testing

## Chapter 18: Security Assessments

### Questions

22. Juan needs to assess the performance of a critical web application that his company recently upgraded. Some of the new features are very profitable, but not frequently used. He wants to ensure that the user experience is positive, but doesn't want to wait for the users to report problems. Which of the following techniques should Juan use?
A. Real user monitoring
B. Synthetic transactions
C. Log reviews
D. Management review

51. Bringing in third-party auditors has advantages over using an internal team. Which of the following is not true about using external auditors?
A. They are required by certain governmental regulations.
B. They bring experience gained by working in many other organizations.
C. They know the organization's processes and technology better than anyone else.
D. They are less influenced by internal culture and politics.

54. Rebecca is an internal auditor for a large retail company. The company has a number of web applications that run critical business processes with customers and partners around the world. Her company would like to ensure the security of technical controls on these processes. Which of the following would not be a good approach to auditing these technical controls?
A. Log reviews
B. Code reviews
C. Personnel background checks
D. Misuse case testing

### Answers

22. B. Synthetic transactions are scripted events that mimic the behaviors of real users and allow security professionals to systematically test the performance of critical services. They are the best approach, because they can detect problems before users notice them. Real user monitoring (RUM) would rely on users encountering the problem, whereupon the system would automatically report it.

51. C. External auditors have certain advantages over in-house teams, but they will almost certainly not be as knowledgeable of internal processes and technology as the folks who deal with them on a daily basis.

54. C. Personnel background checks are a common administrative (not technical) control. This type of audit would have nothing to do with the web applications themselves. The other three options (log reviews, code reviews, misuse case testing) are typical ways to verify the effectiveness of technical controls.

## Chapter 19: Measuring Security

### Questions

43. When classifying an information asset, which of the following is true concerning its sensitivity?
A. It is commensurate with how its loss would impact the fundamental business processes of the organization.
B. It is determined by its replacement cost.
C. It is determined by the product of its replacement cost and the probability of its compromise.
D. It is commensurate with the losses to an organization if it were revealed to unauthorized individuals.

46. When conducting a quantitative risk analysis, items are gathered and assigned numeric values so that cost/benefit analysis can be carried out. Which of the following formulas could be used to understand the value of a safeguard?
A. (ALE before implementing safeguard) – (ALE after implementing safeguard) – (annual cost of safeguard) = value of safeguard to the organization
B. (ALE before implementing safeguard) – (ALE during implementing safeguard) – (annual cost of safeguard) = value of safeguard to the organization
C. (ALE before implementing safeguard) – (ALE while implementing safeguard) – (annual cost of safeguard) = value of safeguard to the organization
D. (ALE before implementing safeguard) – (ALE after implementing safeguard) – (annual cost of asset) = value of safeguard to the organization

68. If the annualized loss expectancy (ALE) for a specific asset is $100,000, and after implementation of a control to safeguard the asset the new ALE is $45,000 and the annual cost of the control is $30,000, should the company implement this control?
A. Yes
B. No
C. Not enough information
D. Depends on the annualized rate of occurrence (ARO)

86. It is important that organizations ensure that their security efforts are effective and measurable. Which of the following is not a common method used to track the effectiveness of security efforts?
A. Service level agreement
B. Return on investment
C. Balanced scorecard system
D. Provisioning system

### Answers

43. D. The sensitivity of information is commensurate with the losses to an organization if that information were revealed to unauthorized individuals. Its criticality, on the other hand, is an indicator of how the loss of the information would impact the fundamental business processes of the organization. While replacement costs could factor into a determination of criticality, they almost never do when it comes to sensitivity.

46. A. The correct answer for cost/benefit analysis is the formula: (ALE before implementing safeguard) – (ALE after implementing safeguard) – (annual cost of safeguard) = value of safeguard to the organization.

68. A. Yes, the company should implement the control, as the value would be $25,000. The cost/benefit calculation is (ALE before implementing safeguard) – (ALE after implementing safeguard) – (annual cost of safeguard) = value of safeguard to the organization, which in this case is $100,000 – $45,000 – $30,000 = $25,000.

86. D. A provisioning system is not typically used to track the effectiveness of security efforts. Service level agreements (SLAs), return on investment (ROI) calculations, and balanced scorecard systems are all common methods for measuring security effectiveness.
