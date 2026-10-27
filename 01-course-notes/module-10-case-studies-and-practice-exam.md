# Module 10: Case Studies and Practice Exam
 
## 1. Introduction
 
This module applies ISO/IEC 27001 concepts to practical implementation scenarios. It also highlights common implementation mistakes and reviews important concepts for the Lead Implementer examination.
 
## 2. Case Study: CloudFirst Solutions
 
### 2.1 Background
 
CloudFirst Solutions implemented an Information Security Management System (ISMS) covering its SaaS hosting operations.
 
The Lead Implementer completed a risk assessment and prepared a Statement of Applicability (SoA). However, physical security controls were excluded because the organisation used AWS to host its production infrastructure.
 
During an internal audit, the auditor discovered several physical security weaknesses at the company's London office:
 
 
- Office access was not properly controlled.
 
- Developers left laptops unlocked on desks.
 
- Printed architectural diagrams were left exposed.
 

 
### 2.2 What Went Wrong?
 
The Lead Implementer assumed that because AWS managed the production data centres, physical security controls were unnecessary for the entire organisation.
 
This was an incorrect assumption.
 
Although a cloud provider manages the physical security of its data centres, the organisation must still consider risks affecting its own offices, devices, documents, and other information assets within the ISMS scope.
 
### 2.3 Corrective Actions
 
CloudFirst took the following steps:
 
 
1. **Immediate response:** Introduced physical security measures, including security personnel and badge readers.
 
2. **Root cause analysis:** Identified the failure to properly assess physical security risks across the ISMS scope.
 
3. **Corrective action:** Reassessed the applicability of physical security controls, introduced a Clear Desk policy, and provided physical security awareness training.
 
4. **Documentation:** Updated the Statement of Applicability and related documentation where necessary.
 

 
### 2.4 Lessons Learned
 
 
- Using a cloud provider does not automatically eliminate an organisation's physical security responsibilities.
 
- The ISMS scope must account for relevant information assets and activities.
 
- Annex A control decisions should be supported by appropriate risk assessments and documented justifications.
 
- Correcting an immediate problem is not enough; the organisation should address the underlying cause and review the effectiveness of corrective action.
 

 
## 3. Practice Exam Questions
 
### Question 1: Cloud Services
 
A marketing agency uses a third-party cloud HR platform to store employee information. How should it handle Annex A Control 5.23 in its Statement of Applicability?
 
A. Exclude the control because a third party manages the platform. B. Consider and include the control because the organisation uses a cloud service within the ISMS scope. C. Leave the control off the SoA. D. Include the control and automatically mark it as failed.
 
**Correct answer: B.**
 
**Explanation:** The organisation should assess the relevance of cloud service security requirements. Outsourcing a service does not automatically remove the organisation's responsibilities for managing associated information security risks.
 
### Question 2: Information Security Policy
 
Which document must top management establish under Clause 5.2?
 
A. The Risk Treatment Plan. B. The Information Security Policy. C. The Statement of Applicability. D. The Internal Audit Schedule.
 
**Correct answer: B.**
 
**Explanation:** Clause 5.2 requires the Information Security Policy to be established by top management.
 
### Question 3: Corrective Action
 
A web server is compromised because a critical security patch was not applied. After taking the server offline and applying the patch, what should the organisation do next?
 
A. Automatically dismiss the IT administrator. B. Evaluate the root cause and determine the corrective action needed to prevent recurrence. C. Immediately notify the certification body in every case. D. Rewrite the entire Information Security Policy.
 
**Correct answer: B.**
 
**Explanation:** Correcting the immediate problem is only the first step. The organisation must evaluate the cause and determine whether corrective action is needed to prevent recurrence or similar problems elsewhere.
 
### Question 4: Annex A Control Categories
 
Which category focuses on employees and contractors, including screening, training, and security responsibilities?
 
A. Organisational Controls. B. People Controls. C. Physical Controls. D. Technological Controls.
 
**Correct answer: B.**
 
**Explanation:** People Controls address information security considerations relating to individuals working for or on behalf of an organisation.
 
### Question 5: Statement of Applicability
 
What is the primary purpose of the Statement of Applicability (SoA)?
 
A. To list employees who completed security training. B. To document applicable Annex A controls, their implementation status, and the justifications for inclusion or exclusion. C. To calculate the ISMS budget. D. To serve as a marketing document.
 
**Correct answer: B.**
 
**Explanation:** The SoA documents control decisions, including which controls are applicable, why they are included or excluded, and the implementation status of applicable controls.
 
## 4. Key Learning Points
 
 
- Cloud services introduce security responsibilities that must be managed, even when infrastructure is outsourced.
 
- Physical security risks must be considered across the ISMS scope.
 
- Top management establishes the Information Security Policy.
 
- Corrective action should address the underlying cause of a nonconformity.
 
- People Controls address human-related information security measures.
 
- The SoA documents control applicability, justifications, and implementation status.
 

 
## Conclusion
 
Effective ISMS implementation requires a clear understanding of organisational boundaries, risk-based control selection, management responsibilities, and continual improvement. Practical case studies help demonstrate how ISO/IEC 27001 principles can be applied to real organisational challenges.
 
*These notes document my learning progress in the ICDFA ISO/IEC 27001 Lead Implementer course and are intended for educational purposes.*
