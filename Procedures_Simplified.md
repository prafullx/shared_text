**Asset Management (AST) Procedures**

This document outlines the procedures and controls for managing technology assets at Authentz Pte Limited. The goal is to ensure assets are properly managed from the time they are acquired until they are disposed of. Here's a simplified breakdown of the key procedures:

1. **Asset Governance**: The IT Asset Management (ITAM) Manager works with asset owners to keep an updated list of all technology assets, who owns them, and their purpose. They review and update processes annually, making sure any changes are communicated to key personnel. If there are issues, they take corrective actions and document the results.

2. **Asset-Service Dependencies**: The ITAM Manager and other specialists identify critical business functions and the technology assets that support them. They assess security controls and report any risks. Assets are classified by data sensitivity and criticality levels.

3. **Stakeholder Involvement**: Key stakeholders for critical systems are identified and involved in managing these assets securely. Processes are reviewed annually, and any necessary changes are communicated.

4. **Standardized Naming Convention**: A consistent naming system for assets is enforced to avoid conflicts. This is reviewed and updated as needed.

5. **Asset Inventories**: Asset owners maintain detailed inventories of all hardware and software, ensuring they are up-to-date and accurate. Software licensing is tracked to protect intellectual property rights.

6. **Data Action Mapping**: A map of where sensitive data is stored, processed, or transmitted is maintained to support data protection assessments.

7. **Asset Ownership Assignment**: Responsibilities for asset management are clearly assigned and tracked. An automated system helps keep the inventory accurate and up-to-date.

8. **Network and Data Flow Diagrams**: Detailed network diagrams are maintained to assess security and document data flows. Assets are categorized to determine applicable security controls.

9. **Security of Assets & Media**: Strict controls are in place for distributing sensitive media, including classification and secure delivery methods.

10. **Unattended Equipment**: Enhanced protection measures are implemented for unattended devices to prevent unauthorized access.

11. **Kiosks & PoI Devices**: Physical security and training are provided to protect devices that handle sensitive data from tampering.

12. **Tamper Detection**: Systems are regularly inspected for signs of tampering, especially after traveling to high-risk areas.

13. **Secure Disposal**: Secure methods are used to dispose of or repurpose system components to prevent data recovery.

14. **Return of Assets**: Procedures ensure all company assets are returned when an employee or third-party user leaves.

15. **Removal of Assets**: Authorization is required for removing assets from company premises, and detailed records are kept.

16. **Use of Personal Devices**: Personal devices are restricted from connecting to company systems, with some exceptions for guest networks.

17. **Tamper Protection**: Anti-tamper measures are integrated throughout the asset lifecycle to protect critical technology assets.

These procedures ensure that all technology assets are managed securely and efficiently, minimizing risks and maintaining compliance with organizational policies.

**Capacity & Performance Planning (CAP) Procedures**

The Capacity & Performance Planning (CAP) procedures are designed to prevent business disruptions due to capacity and performance issues. This involves both technology and business leaders staying aware of current and future performance needs.

1. **Capacity & Performance Management (P-CAP-01):** This involves planning and managing system resources to ensure they meet current and future needs. It includes:
   - Checking if current resources are enough to meet service agreements.
   - Predicting future needs to avoid system overloads.
   - Educating stakeholders on the need for enough processing and storage capacity.
   - Reviewing the process annually and updating it if needed. Changes are communicated to key personnel, and corrective actions are taken if there are any issues.

2. **Capacity Planning (P-CAP-02):** This ensures that there is enough capacity for critical operations during emergencies. It includes:
   - Planning for necessary capacity in information processing, telecommunications, and environmental support during emergencies.
   - Considering the impact of reduced operations during emergencies in the planning.
   - Reviewing the process annually and updating it if needed. Changes are communicated to key personnel, and corrective actions are taken if there are any issues.

Both procedures involve regular reviews and updates, communication of changes to key personnel, and taking corrective actions when necessary to address any deficiencies.


**Change Management (CHG) Procedures**

This document outlines the procedures for managing changes within Authentz Pte Limited to ensure that changes are handled in a way that maintains security and operational integrity. The Change Management Program involves several key steps:

1. **Change Management Program (P-CHG-01):** 
   - A Change Control Manager, along with Systems Security Management and Executive Cybersecurity Leadership, is responsible for creating and overseeing a formal change management program. This program includes processes for implementing changes.
   - Changes must be reviewed and approved by authorized personnel and the Change Control Board (CCB).
   - The process is reviewed annually, and any necessary updates are communicated to key personnel. If issues are found, corrective actions are taken and documented.

2. **Configuration Change Control (P-CHG-02):**
   - Similar to the Change Management Program, this involves tracking, reviewing, approving, or disapproving changes, and documenting them.
   - The process is reviewed annually, and updates are communicated. Corrective actions are taken if needed, and results are documented.

3. **Configuration Change Control | Test, Validate & Document Changes (P-CHG-02.1):**
   - Before changes are made in the live environment, they must be tested and validated in a non-production setting to ensure they do not negatively impact operations or security.
   - If testing is not feasible, alternative measures like system images, configuration backups, or after-hours implementation are used to minimize risks.
   - Changes made in the production environment are documented, and the process is reviewed annually. Updates are communicated, and corrective actions are taken and documented if necessary.

These procedures ensure that changes are managed systematically to prevent security breaches or operational disruptions.


**Cloud Security (CLD) Procedures**

This document outlines the procedures and controls for managing cloud security at Authentz Pte Limited. It covers various aspects of cloud services, security architecture, API security, multi-tenant environments, and geolocation requirements.

1. **Cloud Services**: The company maintains a list of cloud service providers and ensures they comply with security standards and laws. They regularly review these services to ensure they meet required service levels and conduct risk assessments. If issues are found, corrective actions are taken and documented.

2. **Cloud Security Architecture**: The organization designs and implements cloud applications and infrastructure following best practices. This includes using secure configurations, ensuring data encryption, and employing firewalls for security. They also integrate cloud security monitoring with existing tools and review processes annually to address any deficiencies.

3. **API Security**: The company uses secure settings and practices for APIs to ensure they are open and published, facilitating secure interoperability and application migration. Regular reviews are conducted to update processes and address any issues.

4. **Multi-Tenant Environments**: The organization ensures that multi-tenant systems are designed to keep user access separate and secure. They follow established policies and best practices to protect sensitive data and comply with legal obligations. A Customer Responsibility Matrix (CRM) is used to clarify responsibilities between the company and cloud service providers.

5. **Geolocation Requirements**: The company controls where data is processed and stored to meet business and legal requirements. This includes specifying storage locations to aid in incident response if needed. Processes are reviewed annually to ensure compliance and address any changes.

Overall, these procedures ensure that cloud environments are secure, compliant, and aligned with the company's technology strategy. Regular reviews and updates help maintain security and address any evolving conditions.


**Cryptographic Protections (CRY) Procedures**

This document outlines the procedures and controls for using cryptographic technologies to protect data at Authentz Pte Limited. The goal is to ensure data confidentiality by implementing secure encryption methods.

1. **Use of Cryptographic Controls**: The company uses industry-standard encryption protocols like AES-256 and TLS 1.3 to protect sensitive data. Encryption is applied to data both in transit and at rest, ensuring it remains unreadable without proper authorization. Key management is separated from key usage to enhance security.

2. **Export-Controlled Technology**: The company maintains an inventory of cryptographic software or hardware that is subject to export controls. It ensures these technologies are not distributed or installed without proper authorization, following legal requirements.

3. **Transmission Confidentiality**: Strong encryption protocols are used to protect data during transmission over networks, such as the Internet or VPNs. The company ensures only secure configurations are used, and any non-compliance is reviewed and corrected annually.

4. **Transmission Integrity**: To prevent unauthorized data modification during transmission, protocols like SSH and HTTPS are used. The company regularly reviews and updates processes to address any deficiencies.

5. **Encrypting Data At Rest**: Data stored on devices like USBs and laptops is encrypted to prevent unauthorized access. The company uses additional authentication mechanisms to access encrypted data, ensuring it remains secure.

6. **Cryptographic Key Management**: The company follows best practices for managing cryptographic keys, including secure storage and distribution. Keys are changed regularly and replaced if compromised. Key management processes are documented and reviewed annually.

7. **Cryptographic Key Loss or Change**: Procedures are in place to handle the loss or change of cryptographic keys, ensuring data remains accessible. Keys are retired or replaced if their integrity is compromised.

8. **Control & Distribution of Cryptographic Keys**: The company uses secure methods to distribute cryptographic keys, preventing unauthorized substitution. Key custodians are required to acknowledge their responsibilities.

Overall, these procedures ensure that cryptographic protections are effectively implemented and maintained, safeguarding the company's sensitive data.


**Data Classification & Handling (DCH) Procedures**

This document outlines the procedures and controls for managing and protecting data at Authentz Pte Limited. The goal is to ensure data is classified correctly and protected from unauthorized access, whether it's being stored or transmitted. Here's a simplified breakdown of the key procedures:

1. **Data Protection**: Systems Security Management, along with Cybersecurity teams, ensures sensitive information is protected during all stages of system development. This includes controlling media storage and access, maintaining inventory logs, and updating processes as needed.

2. **Data & Asset Classification**: Systems are categorized based on statutory and regulatory requirements. This involves documenting security categorizations and reviewing processes annually to address any deficiencies.

3. **Media Access**: Access to media is restricted to authorized individuals using role-based access controls. Media inventories are conducted annually, and access is monitored using both technical and physical safeguards.

4. **Media Access | Masking Displayed Data**: Sensitive information displayed or printed is masked, showing only partial data like the first six and last four digits of account numbers.

5. **Media Marking**: Media is marked according to data protection standards to alert personnel about handling and distribution limitations.

6. **Media Storage**: Sensitive media is securely stored and controlled until it is destroyed or sanitized. Storage locations are reviewed annually for security.

7. **Media Transportation**: Media is protected during transport using encryption for digital media and locked containers for non-digital media. Transport activities are restricted to authorized personnel.

8. **Media Transportation | Custodians**: A dedicated custodian is identified for media transport, ensuring secure handling throughout the process.

9. **Media Transportation | Encrypting Data In Storage Media**: Strong encryption is used to protect data on digital media during transport, ensuring confidentiality and integrity.

10. **Physical Media Disposal**: Media is securely disposed of when no longer needed, using methods like shredding or incineration to prevent data reconstruction.

11. **System Media Sanitization**: Media is sanitized before disposal or reuse, ensuring data cannot be reconstructed. This includes securely deleting files or overwriting data.

12. **System Media Sanitization | Documentation**: Media sanitization and disposal actions are tracked and documented to ensure compliance and security.

13. **System Media Sanitization | Personal Data**: Personal data is de-identified or removed from media before disposal, ensuring privacy protection.

14. **Media Use**: The use of digital media is restricted based on data classification guidelines, prohibiting unauthorized use and ensuring secure handling.

15. **Media Use | Limitations on Use**: Sensitive data use is restricted to intended purposes, and third-party service providers must comply with security requirements.

16. **Removable Media Security**: Removable media use is controlled to comply with data handling requirements, ensuring secure usage.

17. **Information Sharing**: Information sharing decisions are guided by a process to ensure data is protected and only shared with authorized parties.

18. **Ad-Hoc Transfers**: Secure protocols are used for unscheduled file transfers, ensuring sensitive data is protected during digital and non-digital exchanges.

19. **Media & Data Retention**: Data retention is managed according to legal and business requirements, with secure deletion processes for data no longer needed.

20. **Information Disposal**: Data is securely disposed of when no longer necessary, including originals and copies, to prevent unauthorized access.

21. **De-Identification (Anonymization)**: Personal data is removed from datasets using techniques like masking, encryption, or replacement to protect privacy.

These procedures ensure that data is handled securely and in compliance with relevant regulations, protecting the confidentiality, integrity, and availability of information at Authentz Pte Limited.


**Data Privacy (PRI) Procedures**

This document outlines the procedures and controls for managing data privacy at Authentz Pte Limited. The main goal is to protect sensitive personal data through various mechanisms and activities.

1. **Data Privacy Program**: The company has a structured program to manage data privacy, which includes setting objectives, strategies, and resource requirements. It involves regular reviews and updates to ensure compliance and address any deficiencies.

2. **Dissemination of Privacy Program Information**: Information about the company's data privacy activities is made accessible to the public. This includes using websites, emails, and phone lines for communication and feedback. Changes to privacy notices are communicated to data subjects.

3. **Security of Personal Data**: Personal data is protected through administrative, physical, and technical safeguards. Regular risk assessments are conducted, and staff receive training on data protection.

4. **Data Privacy Notice**: Clear and understandable privacy notices are provided to individuals, detailing how their data is processed. These notices are reviewed and updated regularly to ensure compliance with legal obligations.

5. **Purpose Specification**: The purposes for collecting and using personal data are clearly documented in privacy notices. This ensures transparency and compliance with data protection laws.

6. **Choice & Consent**: Individuals are informed about the potential risks of data processing and have the option to decline consent. Consent mechanisms are tailored to operational needs and updated regularly.

7. **Restrict Collection to Identified Purpose**: Personal data is collected only for specified purposes, with protections in place to prevent unauthorized collection, especially from minors.

8. **Personal Data Retention & Disposal**: Data is retained only for as long as necessary and disposed of securely. Internal use of data for testing and research is minimized and controlled.

9. **Data Masking**: Sensitive information is protected through techniques like anonymization and pseudonymization to prevent unauthorized access.

10. **Usage Restrictions of Sensitive Personal Data**: Personal data is used only for authorized purposes, with monitoring and auditing to ensure compliance.

11. **Information Sharing with Third Parties**: Data is shared with third parties only for authorized purposes, with consent from individuals. Contracts with third parties include data privacy requirements.

12. **Testing, Training & Monitoring**: Regular testing, training, and monitoring activities are conducted to ensure data privacy principles are operationalized effectively.

These procedures ensure that Authentz Pte Limited maintains a high standard of data privacy and complies with relevant laws and regulations. Regular reviews and updates are conducted to address any changes or deficiencies in the processes.


**Endpoint Security Procedures for Authentz Pte Limited**

This document outlines the procedures and controls for ensuring the security of technology assets at Authentz Pte Limited. The goal is to protect data from unauthorized access, whether it's being transmitted or stored, and to comply with legal and contractual obligations.

1. **Endpoint Security (P-END-01):** 
   - Use recommended settings and secure practices to protect user computing devices from threats.
   - Ensure systems are updated and secure, disabling inactive sessions after 15 minutes.
   - Protect physical workspaces by restricting access, securing sensitive data, and sanitizing shared areas.
   - Annually review and update processes, distributing changes to key personnel and addressing any deficiencies.

2. **Endpoint Protection Measures (P-END-02):**
   - Implement the "least functionality" principle by removing unnecessary services and enabling only secure ones.
   - Configure antimalware and firewall settings to be unchangeable by regular users and always active.
   - Use encryption to protect sensitive data, ensuring access is independent of the operating system.
   - Annually review and update processes, addressing any deficiencies as needed.

3. **Prohibit Installation Without Privileged Status (P-END-03):**
   - Restrict software installations to authorized administrators using secure settings.
   - Annually review and update processes, ensuring only authorized changes are made and addressing any deficiencies.

4. **Malicious Code Protection (Anti-Malware) (P-END-04):**
   - Deploy approved antimalware software on all capable systems, documenting exceptions and compensating controls.
   - Regularly update and run antimalware software, performing weekly scans and real-time file checks.
   - Generate and retain audit logs for at least 12 months, ensuring situational awareness of malware activities.
   - Annually review and update processes, addressing any deficiencies as needed.

These procedures ensure that all endpoint devices are secure, minimizing the risk of unauthorized access and data breaches.


**Human Resources Security (HRS) Procedures**

This document outlines the procedures and controls for managing human resources security at Authentz Pte Limited. The aim is to create a secure environment that encourages innovation while protecting sensitive data and ensuring compliance with cybersecurity standards.

1. **Personnel Security Management**: The organization has a program to manage cybersecurity risks associated with job positions. This includes assigning risk levels to jobs, ensuring only qualified individuals handle sensitive data, and requiring annual reviews of these assignments. Managers must ensure that employees with special access take regular vacations to prevent fraud and stress.

2. **Position Categorization**: Each job is assigned a risk level, and criteria are set for screening individuals for these roles. This ensures that only those with the necessary skills and training handle sensitive information. The process is reviewed annually to adapt to changes.

3. **Roles & Responsibilities**: The roles and responsibilities related to cybersecurity are clearly defined for all employees and third-party users. This includes documenting procedures for employment changes and ensuring everyone is aware of their duties. Regular reviews and updates ensure these roles remain relevant.

4. **User Awareness**: Employees and third-party users are informed about their security responsibilities and must report any incidents promptly. Training is provided to ensure everyone understands their roles in maintaining security.

5. **Competency Requirements**: Only individuals with the necessary skills are allowed to perform security-related tasks. Regular assessments and training help maintain a skilled workforce.

6. **Personnel Screening**: Before granting access to sensitive data, individuals undergo thorough background checks. This includes verifying employment history, criminal records, and references. Regular re-screening is conducted as needed.

7. **Terms of Employment**: Employees must agree to follow cybersecurity and data privacy principles. This includes understanding acceptable behavior and the consequences of violations. Social media and technology use are also regulated to prevent misuse.

8. **Access Agreements**: Before accessing sensitive information, users must sign agreements acknowledging their responsibilities. These agreements are reviewed and updated regularly.

9. **Personnel Sanctions**: There are processes to handle violations of security policies. Sanctions are applied based on the severity of the violation, and employees are informed of their rights and responsibilities during investigations.

10. **Personnel Transfer and Termination**: Access rights are adjusted promptly when employees change roles or leave the company. This includes revoking access and ensuring all company property is returned.

11. **Separation of Duties**: To prevent conflicts of interest, duties are separated among different roles. Where full separation isn't possible, compensating controls like dual authorization are implemented.

12. **Incompatible Roles**: Developer privileges are limited to prevent unauthorized changes to systems. Regular reviews ensure that roles remain compatible with security policies.

These procedures ensure that human resources practices align with cybersecurity requirements, protecting both the organization and its employees.


**Identification & Authentication (IAC) Procedures**

This document outlines the procedures and controls for managing user and system access at Authentz Pte Limited, ensuring that only authorized individuals can access systems and data. The main goal is to apply the "least privilege" principle, meaning users get only the access they need to perform their jobs.

1. **Identity & Access Management (IAM):** This involves setting up systems to manage who can access what. It includes using strong authentication methods like passwords, tokens, or biometrics, and regularly reviewing and updating access controls.

2. **User Identification & Authentication:** Every user, including employees and contractors, must have a unique ID and use secure methods to log in. This is reviewed annually to ensure compliance and address any issues.

3. **Third-Party User Access:** Third-party users, like vendors, must also be uniquely identified and authenticated. Their access needs are assessed based on risk and practicality.

4. **Device Authentication:** Devices connecting to the network must be authenticated using secure methods like cryptographic protocols.

5. **User Provisioning & De-Provisioning:** This process manages how users are given access and how it's revoked when they leave or change roles. It ensures that access is granted based on job roles and is removed promptly when no longer needed.

6. **Role-Based Access Control (RBAC):** Access is controlled based on user roles, ensuring that users only have access to the information necessary for their job.

7. **Password Management:** Passwords must be strong, regularly changed, and not reused. Users are prohibited from sharing passwords and must report any suspected compromises immediately.

8. **Account Management:** This involves creating, modifying, and disabling user accounts as needed. It includes regular reviews to ensure accounts are still necessary and secure.

9. **Privileged Account Management (PAM):** Special accounts with elevated privileges are tightly controlled and monitored to prevent misuse.

10. **Access Enforcement:** Access to sensitive data is restricted to those who need it for their job, and systems are in place to enforce these restrictions.

11. **Account Lockout:** Systems automatically lock accounts after a set number of failed login attempts to prevent unauthorized access.

These procedures are reviewed regularly to ensure they remain effective and compliant with industry standards. Any changes are communicated to relevant personnel, and corrective actions are taken as needed to address any deficiencies.


**Incident Response (IRO) Procedures**

This document outlines the procedures and controls for handling security-related incidents at Authentz Pte Limited. The main goal is to ensure the organization is prepared to respond effectively to such incidents.

1. **Incident Response Operations**: The company uses recommended settings and best practices to manage incidents. An Incident Response Plan (IRP) is in place, which is reviewed annually. Changes are communicated to key personnel, and corrective actions are taken if needed.

2. **Incident Handling**: The team investigates alerts, assesses incidents, and takes appropriate actions to minimize impact. The IRP covers preparation, detection, analysis, containment, eradication, and recovery. The process is reviewed annually, and updates are communicated to key personnel.

3. **Incident Response Plan (IRP)**: The IRP is maintained and tested annually. It includes roles, responsibilities, communication strategies, and specific procedures for incident response, business recovery, and data backup. Training is provided to staff, and the plan is updated based on lessons learned.

4. **Data Breach Response**: Specific procedures are in place for handling data breaches, including maintaining records of unauthorized disclosures and notifying affected parties. The process is reviewed annually, and updates are communicated to key personnel.

5. **Incident Response Training**: Training is provided to personnel based on their roles, with privileged users trained within 10 days and others within 30 days. Training content is reviewed annually and after significant incidents.

6. **Incident Response Testing**: The effectiveness of the IRP is tested every six months through realistic exercises. Any deficiencies found are corrected, and the process is reviewed annually.

7. **Integrated Security Incident Response Team (ISIRT)**: A team is established to handle incidents, with members available 24/7. The team is trained to respond to realistic scenarios, and incidents are assessed for their financial impact.

8. **Chain of Custody & Forensics**: Proper forensic procedures are followed to maintain evidence integrity. Only forensic images are used for analysis, and the process is reviewed annually.

9. **Situational Awareness for Incidents**: The team monitors for incidents using various tools and documents all incidents. The process is reviewed annually, and updates are communicated to key personnel.

10. **Incident Stakeholder Reporting**: Incidents are reported internally and externally as needed. The process includes tracking incidents, documenting them, and notifying relevant authorities. The process is reviewed annually.

11. **Root Cause Analysis & Lessons Learned**: After each incident, a root cause analysis is performed, and lessons learned are incorporated into the IRP. The process is reviewed annually, and updates are communicated to key personnel.

Overall, these procedures ensure that Authentz Pte Limited is prepared to handle security incidents effectively, minimizing their impact and ensuring business continuity.


**Network Security (NET) Procedures**

This document outlines the procedures and controls for maintaining network security at Authentz Pte Limited. The goal is to protect the confidentiality and integrity of communications and provide awareness of network activities.

1. **Network Security Controls (NSC):** Regularly update and manage security settings using industry best practices. Review and revise processes annually, distribute updates to key personnel, and take corrective actions if needed.

2. **Layered Defenses:** Implement a multi-layered security approach to separate and protect different network components. Use firewalls, DMZs, and network segmentation to isolate sensitive data and prevent unauthorized access.

3. **Boundary Protection:** Use firewalls and other devices to monitor and control network traffic at external and internal boundaries. Ensure only necessary traffic is allowed and prevent unauthorized data leaks.

4. **Data Flow Enforcement – Access Control Lists (ACLs):** Configure firewalls and routers to restrict network connections. Use a "deny-all" approach by default, allowing exceptions only when justified.

5. **Network Segmentation:** Divide the network into segments to isolate sensitive systems and data. Use DMZs and other techniques to control access and prevent unauthorized interactions between different network areas.

6. **Network Intrusion Detection & Prevention Systems (NIDS/NIPS):** Deploy systems to detect and prevent network intrusions. Keep these systems updated and monitor network traffic for suspicious activities.

7. **Electronic Messaging:** Protect electronic communications like email and instant messaging by setting usage restrictions and guidelines to prevent misuse.

8. **Remote Access:** Define secure methods for remote access, such as VPNs, and prohibit insecure methods. Monitor and control remote connections, ensuring they are authorized and encrypted.

9. **Wireless Networking:** Control and monitor wireless access, ensuring strong encryption and authorization before connections are allowed.

10. **DNS & Content Filtering:** Route internet traffic through filtering systems to block access to dangerous or prohibited sites. Keep filtering services updated and enforce them for all systems, regardless of location.

Each procedure includes an annual review to address non-conformities and update processes as needed. Changes are communicated to key personnel, and corrective actions are taken to resolve any deficiencies.


**PHYSICAL & ENVIRONMENTAL SECURITY (PES) PROCEDURES**

This document outlines the procedures and controls for ensuring physical and environmental security at Authentz Pte Limited. The goal is to protect systems and data by addressing physical security and environmental concerns.

1. **Physical & Environmental Protections**: The leadership team develops a company-wide physical security program, documented in a policy. They ensure that data owners and asset custodians create specific procedures, identify legal obligations, and assign roles. Annually, they review and update processes, distributing changes to key personnel and requesting corrective actions if needed.

2. **Physical Access Authorizations**: The Physical Security Manager maintains a list of people with access to facilities, using secure practices to manage access zones and limit access to necessary personnel. Access lists are reviewed quarterly, and processes are updated annually.

3. **Role-Based Physical Access**: Access to sensitive areas is restricted based on roles, such as employees or contractors. The process is reviewed annually, and changes are communicated to key personnel.

4. **Physical Access Control**: Access to facilities is controlled using fences, guards, and surveillance. Different zones are established, from public areas to high-security zones. Access logs are maintained, and visitor activities are monitored.

5. **Controlled Ingress & Egress Points**: Entry and exit points are monitored using cameras and access controls. Access to network jacks and sensitive equipment is restricted.

6. **Physical Access Logs**: Access control systems log entry details, and visitor logs are maintained for a year. Anomalies are reported according to the incident response plan.

7. **Physical Security of Offices, Rooms & Facilities**: Sensitive areas are secured, and access is based on job functions. Work areas are cleared of sensitive data when not in use, and access is revoked upon termination.

8. **Monitoring Physical Access**: Surveillance equipment monitors access to sensitive areas. Physical access data is retained for three months, and logs are reviewed monthly for anomalies.

9. **Visitor Control**: Visitors are identified, authorized, and monitored. They receive badges that expire and must be surrendered upon leaving. Visitor logs are maintained for three months.

10. **Supporting Utilities**: Power and environmental conditions are managed to protect systems. Automatic voltage controls and emergency power supplies are in place for critical systems.

11. **Delivery & Removal**: Access to delivery areas is restricted, and assets cannot be removed without authorization. Asset details are recorded before removal.

12. **Equipment Siting & Protection**: Equipment is located to minimize damage and unauthorized access. Redundant equipment is placed at a safe distance from threats.

13. **Information Leakage Due To Electromagnetic Signals**: Facilities are secured to prevent information leakage from electromagnetic signals, with proper placement and power settings for wireless access points.

These procedures ensure that physical and environmental security measures are in place, regularly reviewed, and updated to address any deficiencies.


**Risk Management (RSK) Procedures**

This document outlines the procedures and controls for managing cybersecurity risks at Authentz Pte Limited. The goal is to ensure that risks are visible and understood by the business units responsible for the assets and processes involved. The cybersecurity team helps facilitate and educate, but the business units and stakeholders must actively participate in risk discussions.

1. **Risk Management Program (RMP):** This involves using secure practices to manage risks, including a formal program to address risk categories and measurement criteria. It includes evaluating and monitoring risks regularly, conducting annual risk assessments, and identifying critical assets and safeguards. The process is reviewed annually, and any changes are communicated to key personnel.

2. **Risk Framing:** This involves identifying assumptions, constraints, and organizational risk tolerance. The Risk Specialist works with the Risk Manager to frame risks related to cybersecurity and data privacy, considering compliance obligations, threats, and industry practices. The process is reviewed annually, and changes are communicated to key personnel.

3. **Risk-Based Security Categorization:** Systems and data are categorized according to laws, and the results are documented in a security plan. This involves assessing system criticality and data sensitivity, with annual reviews and updates communicated to key personnel.

4. **Risk Identification:** Risks are identified and documented by the Asset Owner and other teams. The risk profile is updated as needed, with annual reviews and communication of changes to key personnel.

5. **Risk Assessment:** Regular assessments are conducted to evaluate the likelihood and impact of risks, including unauthorized access or data breaches. The results are documented and shared with stakeholders, with annual updates or when significant changes occur.

6. **Risk Remediation:** Risks are mitigated to acceptable levels, with remediation actions taken based on risk criteria. The process is reviewed annually, and changes are communicated to key personnel.

7. **Business Impact Analysis (BIA):** This analysis identifies and assesses risks to business operations, including critical products and services, dependencies, and potential impacts of disruptions. The process is reviewed annually, and changes are communicated to key personnel.

8. **Data Protection Impact Assessment (DPIA):** This assessment evaluates data privacy risks for systems handling personal data. It is required for new systems, significant modifications, or when data privacy concerns arise. The process is reviewed annually, and changes are communicated to key personnel.

Overall, these procedures ensure that risks are managed effectively, with regular reviews and updates to adapt to changing conditions.


**Security Awareness & Training (SAT) Procedures**

This document outlines the procedures for developing a security-conscious workforce at Authentz Pte Limited. The main goal is to ensure that all employees, contractors, and third-party users are well-versed in cybersecurity and data privacy through structured training programs.

1. **Cybersecurity & Data Privacy-Minded Workforce**: The organization provides cybersecurity training to all new users and continues this training annually. Training is also updated when there are significant changes in technology, regulations, or threats. The training includes defining necessary skills, developing role-specific programs, and setting standards for cybersecurity roles. The training program is reviewed annually and updated as needed, with changes communicated to key personnel.

2. **Cybersecurity & Data Privacy Awareness Training**: This involves providing relevant training to all employees and contractors based on their job functions. The training is updated annually and whenever necessary due to system changes or incidents. It covers a wide range of topics, including information security basics, data handling, and incident response. The program includes setting training goals, identifying target audiences, and evaluating training effectiveness. Updates and changes are communicated to key personnel, and corrective actions are taken if deficiencies are found.

3. **Cybersecurity & Data Privacy Role-Based Training**: This training is tailored to specific roles and is required before accessing systems or performing duties. It is updated annually and when system changes occur. The training includes understanding policies, handling sensitive data, and recognizing threats like phishing and social engineering. Lessons from security incidents are incorporated into the training. The program ensures that all personnel are aware of their security responsibilities and are adequately trained to perform their roles. Regular reviews and updates are conducted, and any necessary corrective actions are implemented and documented.

Overall, the document emphasizes the importance of continuous education and adaptation to new security challenges to maintain a secure organizational environment.


**Third-Party Management (TPM) Procedures**

This document outlines the procedures and controls for managing third-party relationships to minimize risks associated with external service providers. Here's a simplified breakdown of the key procedures:

1. **Third-Party Management**: Ensure that all service providers comply with cybersecurity and data privacy requirements. This involves maintaining a list of providers, having written agreements acknowledging their responsibility for data security, and conducting annual compliance reviews.

2. **Third-Party Inventories**: Keep an updated list of all external service providers that could impact the organization's systems and data. Review and update this list annually.

3. **Criticality Assessments**: Identify and assess the importance of suppliers and partners using a risk assessment process. Conduct a Business Impact Analysis (BIA) for each critical third-party and share this with stakeholders for disaster recovery planning.

4. **Supply Chain Protection**: Evaluate security risks in the supply chain. This includes conducting risk assessments, ensuring contracts protect the organization's interests, and performing annual reviews to address any deficiencies.

5. **Acquisition Strategies**: Use tailored strategies for acquiring systems and services, ensuring data integrity throughout the system's lifecycle. Encourage suppliers to implement security safeguards and provide transparency.

6. **Limit Potential Harm**: Implement safeguards to reduce risks from supply chain threats, such as using diverse suppliers and approved vendor lists.

7. **Address Weaknesses**: Report and address any identified weaknesses in the supply chain as cybersecurity incidents.

8. **Third-Party Services**: Manage risks associated with third-party access to systems and data by maintaining a list of service providers, ensuring compliance with security requirements, and conducting risk assessments.

9. **Contract Requirements**: Ensure contracts with third-parties include cybersecurity and data privacy requirements. Contracts should specify data protection responsibilities and breach notification procedures.

10. **Incident Response & Recovery**: Ensure third-party providers conduct incident response and continuity plan testing, reporting results to the organization.

These procedures are reviewed annually, and any necessary changes are communicated to key personnel. Corrective actions are taken to address deficiencies, and results are documented for accountability.


**Vulnerability & Patch Management (VPM) Procedures**

This document outlines the procedures for managing vulnerabilities and patching systems at Authentz Pte Limited. The goal is to proactively handle risks related to technical vulnerabilities.

1. **Vulnerability & Patch Management Program (VPMP):** The security team, along with cybersecurity leadership, ensures that system flaws are identified, reported, and fixed. They use recommended settings and secure practices to manage vulnerabilities across the company. The process is reviewed annually, and any changes are communicated to key personnel. If issues are found, corrective actions are taken and documented.

2. **Attack Surface Scope:** The security team defines the scope of vulnerability management by documenting the company's business model and cybersecurity strategy. They ensure that third parties also manage vulnerabilities properly. The process is reviewed annually, and updates are communicated to key personnel. Corrective actions are taken if needed.

3. **Vulnerability Remediation Process:** The systems administration team, along with other departments, tracks and fixes vulnerabilities using a documented plan. This plan includes all known vulnerabilities, actions to fix them, and timelines. The plan is reviewed quarterly, and updates are communicated to key personnel. Corrective actions are taken if necessary.

4. **Vulnerability Ranking:** The cybersecurity team ranks vulnerabilities based on risk using external sources. They categorize and prioritize vulnerabilities for fixing. The process is reviewed annually, and updates are communicated to key personnel. Corrective actions are taken if needed.

5. **Software & Firmware Patching:** The cybersecurity team ensures that all systems have the latest security patches. Patches are categorized by priority, and timelines are set for applying them. Systems are divided into zones based on their exposure and importance, with specific patching timelines for each. Patches are tested before application to ensure they don't compromise security. The process is reviewed annually, and updates are communicated to key personnel. Corrective actions are taken if necessary.

6. **Vulnerability Scanning:** The vulnerability analysis team performs regular scans to detect vulnerabilities and configuration errors. They use tools that follow industry standards to automate parts of the process. Scans are updated automatically or when new vulnerabilities are found. The team analyzes scan results and fixes legitimate vulnerabilities. Information from scans is shared with relevant personnel to prevent similar issues in other systems. The process is reviewed annually, and updates are communicated to key personnel. Corrective actions are taken if needed.

Overall, these procedures ensure that vulnerabilities are managed effectively, and systems are kept secure through regular updates and patches.


**Web Security Procedures**

The Web Security Procedures document outlines how to manage risks associated with internet-accessible technologies. It includes two main procedures:

1. **Web Security (P-WEB-01):** This procedure involves using recommended settings and secure practices to ensure that systems exposed to the internet are secure and private by default. It includes maintaining these systems to minimize vulnerabilities and regularly reviewing them to fix any known issues. Every year, the process is reviewed, and if needed, updated to address any changes or new conditions. Updates are shared with key personnel, and corrective actions are taken if there are any deficiencies. These actions are validated and documented, and further actions are taken if issues remain unresolved.

2. **Use of Demilitarized Zones (DMZs) (P-WEB-02):** This procedure involves setting up DMZs to control incoming traffic to only allow authorized devices on specific services, protocols, and ports. It includes using secure practices to configure DMZs, separating public system components from internal networks, and only allowing authorized communications based on documented business reasons. All other traffic is denied. Like the first procedure, this is reviewed annually, and updates are communicated to key personnel. Corrective actions are taken and validated if there are deficiencies, and further actions are documented if needed.
