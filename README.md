<h1>Mini Compliance Program</h1>

<h2>Video Demonstration</h2>
 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
This project presents a mini GRC program developed for a fictional healthcare organization called SaveRecords Health Clinic. The purpose of the project was to simulate how a healthcare environment can identify, assess, and manage cybersecurity and compliance risks related to sensitive patient information stored within cloud-based systems.  The overall objective of this project was to demonstrate foundational knowledge of governance, risk management, compliance processes, control selection, and risk-based security decision-making within a healthcare compliance environment.
<br/>

<h2>Framework Used</h2>

<ul> <li>ISO 27001 Annex A</li>

</ul>

<h2>Task To Complete</h2>

<ul>
 <li>Choose a fictional company (for example, a SaaS startup or healthcare clinic)</li>
 <li>Identify and document critical organizational assets, systems, users, and data types requiring protection.</li>
 <li>Write a scope summary for the organization</li>
 <li>Developed Risk Assessment Methodology</li>
 <li>Determine potential cybersecurity threats and vulnerabilities affecting healthcare systems and patient data.</li>
 <li>Create realistic risk scenarios demonstrating how threats could exploit vulnerabilities.</li>
 <li>Develop a structured risk register to document identified risks and remediation efforts.</li>
 <li>Map identified risks to 15-20 relevant ISO/IEC 27001 Annex A controls.</li>
 <li>Create Control Mapping Table</li>
 <li>Create Compliance Matrix</li>
 <li>Gap Assessment & Remediation Summary (One Page)</li>
 <li>Write Executive Summary & Compliance Program Overview (One Page)</li>
</ul>

<h2>Program walk-through:</h2>

<p align="center">
  <strong>Step One: Define The Fictional Organization</strong> <br/>

 I needed a clear story for the compliance environment so first, I identified from personal experience of the type of jobs I worked. Healthcare came to mind. Healthcare is naturally high of compliance relevance (HIPAA, ISO 27001, etc), electronic records and data types like PII and PHI. I created a healthcare clinic called SaveRecords that stores and manages electronic patient records in a cloud environment.
  <ul>
  <img src="https://i.imgur.com/OgEUlUn.png" height="80%" width="80%" alt="SaveRecords"/></li>
 </ul>

<strong>Why This Step Was Important</strong><br>
Before implementing security controls or assessing risks, I needed to understand the organization I was protecting. Defining the organization provided the business context necessary to determine:
What systems needed protection
What sensitive data was being handled
Who would be using the systems
Which risks and compliance requirements were most relevant
Without a clearly defined organization, it would be difficult to build an effective ISO 27001 compliance program.

<p align="center">
 <strong>Step Two: Identify Assets, Systems, Users & Data Types</strong> <br/>

 From there, I define the full compliance scope including:

<strong>Assets & Systems</strong>
 <ul>
  <li>EMR Systems (EMR Application & Platform)<img src="https://i.imgur.com/bGSYZMf.png" height="80%" width="80%" alt="SaveRecords"/></li>
  <li>Cloud Database:<br/><img src="https://i.imgur.com/NTzHrhE.png" height="80%" width="80%" alt="SaveRecords"/></li>
   <li>Staff Laptops<br/><img src="https://i.imgur.com/79JdHm3.png" height="80%" width="80%" alt="SaveRecords"/></li>
   <li>Staff Email</li>
   <li>Servers</li>
   <li>Network Devices</li>
   <li>Security Cameras</li>
 </ul>

<strong>Users</strong>
<ul>
   <li>Doctors, Admin Staff, Nurses, IT Support</strong><br/><img src="https://i.imgur.com/4mf0V0q.png" height="80%" width="80%" alt="SaveRecords"/></li>
 </ul>

<strong>Sensitive Data Types</strong>
<ul>
   <li>PII and PHI<br/><img src="https://i.imgur.com/6yKDBji.png" height="80%" width="80%" alt="SaveRecords"/><br/><img src="https://i.imgur.com/APxuRxJ.png" height="80%" width="80%" alt="SaveRecords"/></li>
</ul>
  
<strong>Why This Step Was Important</strong><br>
This step is critical because it helps me know what this health clinic (Save Records) owns, who uses it and where sensitive data lives. Also as well, it helps me identify what could be attacked, what needs stronger protection and which systems are most important.

You cannot protect what you do not know exists. 

<p align="center">
 <strong>Step Three: The Scope Summary </strong> <br/>
 
<strong>Scope Summary:</strong>
SaveRecords Health Clinic operates an internal patient management system where doctors, nurses, and admin staff access patient records stored in a secure cloud environment. The scope of this compliance program includes the clinics information systems, electronic medical record (EMR) platforms, staff laptops and patient data stored in the cloud.

<strong>Why This Step Was Important</strong><br>
This scope summary defines what's in scope (systems, assets, data) and who interacts with them. Without a scope summary, the compliance program becomes unclear and difficult to manage. Having a scope summary avoids confusion.

<p align="center">
 <strong>Step Four: Develop Risk Assessment Methodology</strong> <br/>
<img src="https://i.imgur.com/6RnJrEI.png" height="80%" width="80%" alt="SaveRecords"/>

To ensure risks were evaluated consistently, I developed a risk assessment methodology that measures risk using likelihood and impact scores.
The methodology uses a 1-to-5 rating scale for both likelihood and impact.
The likelihood scale measures how probable it is that a threat could occur.
The impact scale measures the severity of the consequences if a risk event occurs.
The overall risk score is calculated using the following formula:
Risk Score = Likelihood × Impact
Once calculated, risks are categorized into Low, Medium, High, or Critical risk levels to help prioritize remediation efforts.

<strong>Why This Step Was Important</strong><br>
A risk assessment methodology provides a consistent way to evaluate and prioritize risks across the organization.
Without a defined methodology: 
Risk ratings may be subjective
Risks may be prioritized inconsistently
Security resources may be focused on the wrong issues
Using likelihood and impact scoring helps ensure that the most significant risks receive attention first. This methodology became the foundation for scoring risks within the risk register and determining which risks required remediation.

<p align="center">
 <strong>Step Five: Identify Assets, Threat & Vulnerabilities </strong> <br/>

 After establishing the compliance scope and risk assessment methodology, I identified eight assets, eight potential threats and eight vulnerabilities affecting the organization's critical assets.

 <strong>Identified Assets (What the organization owns):</strong><br>
1. EMR System
2. Cloud DB
3. Staff Laptop
4. Staff Email
5. Patient Data
6. Servers
7. Network Devices (Routers & Firewalls)
8. Security Cameras

 <strong>Identified Threats (What bad thing could happen):</strong><br>
1. Unauthorized access to patient records
2. Data breach
3. Device theft leadibg to data exposure
4. Phishing attack
5. Unauthorized data disclosure
6. Ransomware attack
7. Network intrusion / unauthorized access
8. Unauthorized access to surveillance systems

 <strong>Identified Vulnerabilities (Why it could happen):</strong><br>
1. No Multi-Factor Authentication (MFA)
2. Misconfigured access permissions
3. No disk encryption
4. Lack of security awareness training
5. Weak access controls or excessive permissions
6. Unpatched software or outdated systems
7. Default credentials or weak configurations
8. Default passwords and outdated firmware

<strong>Why This Step Was Important</strong><br>
The purpose of this step was to understand what could negatively impact the confidentiality, integrity, and availability of systems and sensitive patient information. By understanding both threats and vulnerabilities, I was able to determine which assets were most at risk, how attacks could occur, which controls would be needed to reduce risk, what risks should be documented in the risk register.


<p align="center">
 <strong>Step Six: Create Risk Scenarios</strong><br/>

 After identifying the organization's assets, threats, and vulnerabilities, I developed realistic risk scenarios to demonstrate how a threat could exploit a vulnerability and negatively impact the organization.  These scenarios help translate technical risks into real-world business situations that management and stakeholders can easily understand.
 
1. A hacker guesses a doctor's password and gains unauthorized access to patient records stored within the EMR system.
2. Patient records stored in the cloud become publicly accessible due to incorrect permission settings.
3. A stolen laptop contains patient information that can be viewed because the device is not encrypted.
4. An employee clicks a malicious email and unknowingly provides their login credentials to an attacker.
5. An employee accesses or shares patient information they were not authorized to view.
6. Attackers exploit a known software vulnerability and deploy ransomware, disrupting operations.
7. A hacker gains access to network equipment using default credentials and compromises internal systems.
8. An attacker accesses the camera system remotely and views surveillance footage without authorization.
 
<strong>Why This Step Was Important</strong><br>
Risk scenarios help explain how a threat could take advantage of a vulnerability to impact an organization's assets, operations, or sensitive data. Risk scenarios turn threats and vulnerabilities into realistic stories that explain how a security incident could occur.

<p align="center">
 <strong>Step Seven: Create Risk Register</strong><br/>
 <img src="https://i.imgur.com/LUj8mbz.png" height="80%" width="80%" alt="SaveRecords"/>

After identifying the organization's assets, threats, vulnerabilities, and risk scenarios, I created a risk register to document and assess the risks affecting SaveRecords Health Clinic.

<strong>Why This Step Was Important</strong><br>
The risk register provides a structured way to document, evaluate, prioritize, and manage organizational risks.  It helps the organization understand its most significant risks, prioritize remediation activities, assign accountability through risk ownership and track risk treatment decision as well as monitor progress toward risk reduction.  Without a risk register, risks may be identified but not consistently managed or monitored.

<p align="center">
 <strong>Step Eight: Select ISO 27001 Based on Risk Controls</strong><br/>
  <img src="https://i.imgur.com/H6RJW2z.png" height="80%" width="80%" alt="SaveRecords"/>

 <strong>ISO 27001 Annex A Framework Information:</strong><br>
https://www.isms.online/iso-27001/annex-a-2022/

 <strong>ISO 27001 (Annex A)</strong> has 93 controls grouped under four themes:
<ul>
 <li>Organization (A.5 - A.8 - 37 Controls): Policies, procedures, and governance.</li>
 <li>People (A.6 - 8 Controls): Background checks, training, and awareness.</li>
 <li>Physical (A.7 - 14 Controls): Secure areas, equipment, and surveillance.</li>
 <li>Technological (A.8 - 34 Controls): Network security, encryption, and access management.</li>
</ul>

 After completing the risk assessment and risk register, I selected relevant controls from ISO 27001 Annex A to address the risks identified within SaveRecords Health Clinic.
I chose ISO 27001 because it is a globally recognized information security framework that uses a risk-based approach (controls that are selected based on their specific risks, system and business requirements). 

From the 93 Annex A controls, I selected 20 controls that were most relevant to the healthcare environment and mapped them to the organization's critical assets and identified risks.

<strong>Why This Step Was Important</strong><br>
The goal of these controls was to reduce the likelihood and impact of cybersecurity incidents while protecting sensitive patient information, including Personally Identifiable Information (PII) and Protected Health Information (PHI).
Selecting controls based on risk helps organizations protect critical assets, reduce security vulnerabilities, improve compliance readiness, support regulatory requirements, prioritize security investments and establish a defensible security program. Without security controls, identified risks remain unresolved and continue to expose the organization to potential harm.


<p align="center">
 <strong>Step Nine: Explain Why Those Controls Were Chosen</strong><br/>

 I explain why each of those controls was chosen.

<strong>1. EMR System (Unauthorized Access)</strong><br/>

https://github.com/user-attachments/assets/522722d8-2b9c-4e15-bc0f-4f91f44e6fd6

 Electronic Medical Records contain sensitive patient information. If the wrong person gets access, patient privacy, trust, and legal compliance are affected. <br/>
<strong>Controls</strong>: 
<ul>
 <li><strong>ISO 27001 A.5.15 — Access Control:</strong> This matters because it ensures only authorized staff can access the EMR system. Doctors, nurses, and admins should only see the information needed for their jobs. Without access control, anyone inside the organization could view or misuse patient records.</li>
 <li><strong>ISO 27001 A.8.2 — Privileged Access Rights:</strong> This matters because administrator accounts have powerful permissions. If admin access is not tightly controlled, a single compromised account could expose or alter thousands of patient records.</li>
 <li><strong>ISO 27001 A.8.3 — Information Access Restriction:</strong> This matters because it limits access to sensitive medical data based on role or department. For example, billing staff should not have the same access as medical providers. This reduces insider threats and accidental exposure.</li>
</ul>

<strong>2. Cloud Database (Data Breach)</strong><br/>

https://github.com/user-attachments/assets/003c73d4-e647-409d-bc65-2843a926f7c7

Cloud databases often store patient information, appointments, and billing data. A breach could expose large amounts of confidential information. <br/>
 <strong>Controls</strong>:
<ul>
 <li><strong>ISO 27001 A.8.5 — Secure Authentication:</strong> This matters because weak passwords or poor login protection make it easier for attackers to break into the database. Strong authentication helps stop unauthorized access.</li>
 <li><strong>ISO 27001 A.8.24 — Use of Cryptography:</strong> This matters because encryption protects sensitive data even if attackers steal it. Encrypted patient records are much harder to read or misuse.</li>
 <li><strong>ISO 27001 A.8.9 — Configuration Management:</strong> This matters because misconfigured cloud settings are one of the biggest causes of data breaches. Proper configuration ensures security settings are correct and continuously maintained.</li>
</ul>

<strong>3. Staff Laptop (Device Theft)</strong><br/>

https://github.com/user-attachments/assets/d13fec72-bf62-413f-8dee-ebcf2f1b6e6d

Healthcare workers often use laptops containing patient records, emails, and internal systems. A stolen laptop can become a major security incident. <br/>
 <strong>Controls</strong>:
<ul>
 <li><strong>ISO 27001 A.7.10 — Storage Media:</strong> This matters because sensitive information stored on laptops or removable drives must be protected. Encryption and secure storage reduce the damage if the laptop is stolen.</li>
 <li><strong>ISO 27001 A.8.1 — User Endpoint Devices:</strong> This matters because laptops are endpoint devices frequently targeted by attackers. Security controls like device locking, antivirus software, and remote wipe help protect data.</li>
</ul>

<strong>4. Staff Email (Phishing)</strong><br/>

https://github.com/user-attachments/assets/8a423d61-a2c1-48a9-a429-7b0e698384a4

Phishing emails trick employees into clicking malicious links or giving away passwords. Healthcare organizations are common targets because of valuable patient data. <br/>
 <strong>Controls</strong>:
<ul>
 <li><strong>ISO 27001 A.6.3 — Information Security Awareness, Education and Training:</strong> This matters because employees are the first line of defense. Training helps staff recognize suspicious emails, fake login pages, and social engineering attacks.</li>
 <li><strong>ISO 27001 A.8.7 — Protection Against Malware:</strong> This matters because phishing emails often deliver malware or ransomware. Anti-malware tools help detect and block malicious files before they infect systems.</li>
</ul>

<strong>5. Patient Data (Unauthorized Access)</strong><br/>

https://github.com/user-attachments/assets/c6ebbe23-bdd4-4fdd-9e9c-83fc5f4be410

Patient information is highly confidential and protected by privacy laws. Unauthorized access can lead to identity theft, lawsuits, and loss of trust. <br/>
 <strong>Controls</strong>:
<ul>
 <li><strong>ISO 27001 A.5.34 — Privacy and Protection of Personally Identifiable Information (PII):</strong> This matters because healthcare organizations must protect patient personal data and comply with privacy regulations. The control ensures patient information is collected, stored, and handled securely.</li>
 <li><strong>ISO 27001 A.8.3 — Information Access Restriction:</strong> This matters because not every employee should have access to all patient records. Restricting access reduces the chance of misuse or accidental disclosure.</li>
</ul>

<strong>6. Servers (Ransomware)</strong><br/>

https://github.com/user-attachments/assets/b1ab0ec7-3e5e-44a4-ad52-65e6a20f3fd1

Ransomware can encrypt healthcare systems, making patient records and services unavailable. This can disrupt patient care and operations. <br/>
 <strong>Controls</strong>:
<ul>
 <li><strong>ISO 27001 A.8.8 — Management of Technical Vulnerabilities:</strong> This matters because outdated software and unpatched systems are common ransomware entry points. Regular patching closes security weaknesses attackers exploit.</li>
 <li><strong>ISO 27001 A.8.13 — Information Backup:</strong> This matters because backups allow organizations to restore systems after a ransomware attack without paying attackers. Backups are critical for recovery.</li>
 <li><strong>ISO 27001 A.8.16 — Monitoring Activities:</strong> This matters because continuous monitoring helps detect suspicious behavior early, such as unusual file encryption or unauthorized activity on servers.</li>
</ul>

<strong>7. Network Devices (Intrusion)</strong><br/>

https://github.com/user-attachments/assets/3637f45c-bc21-4585-82cc-42e347c4144b

Routers, switches, and firewalls manage network traffic. If attackers compromise these devices, they may gain access to the entire healthcare network. <br/>
 <strong>Controls</strong>:
<ul>
 <li><strong>ISO 27001 A.8.20 — Network Security:</strong> This matters because it protects networks from unauthorized access and attacks. Firewalls, segmentation, and secure configurations help defend healthcare systems.</li>
 <li><strong>ISO 27001 A.8.21 — Security of Network Services:</strong> This matters because network services such as internet access, VPNs, and remote connections must be secured and monitored to prevent intrusions.</li>
</ul>

<strong>8. Security Cameras (Unauthorized Access)</strong><br/>

https://github.com/user-attachments/assets/d75d12ee-5bad-4c5d-acd7-6a71a633a49a

Security cameras protect physical areas of the healthcare facility. If compromised, attackers could spy on patients or staff or disable surveillance. <br/>
 <strong>Controls</strong>:
<ul>
 <li><strong>ISO 27001 A.7.4 — Physical Security Monitoring:</strong> This matters because cameras are part of physical security protection. Monitoring helps detect unauthorized physical access and security incidents.</li>
 <li><strong>ISO 27001 A.8.9 — Configuration Management:</strong> This matters because poorly configured cameras often have weak passwords or outdated firmware. Proper configuration reduces the risk of unauthorized access to surveillance systems.</li>
</ul>

<p align="center">
 <strong>Step Ten: Create Control Mapping Table</strong><br/>
 <img src="https://i.imgur.com/CsrJJLR.png" height="80%" width="80%" alt="SaveRecords"/>

The Control Mapping Table connects risks to controls and controls to evidence.

I like to think of the Control Mapping Table as a checklist that matches security problems to security solutions. Step 10 answers: "Which controls address which risks?"

<strong>Why This Step Was Important</strong><br>
Without a Control Mapping Table, it would be difficult to demonstrate how security controls address identified risks or how compliance requirements are being met.

<p align="center">
 <strong>Step Eleven: Create Compliance Matrix</strong><br/>
  <img src="https://i.imgur.com/gIy9rKK.png" height="80%" width="80%" alt="SaveRecords"/><br>

 The Compliance Matrix evaluates the implementation status of the selected ISO 27001 controls within the SaveRecords Health Clinic environment.
This answers: "What is the current compliance status of each control?"The matrix documents each control, its implementation status, responsible owner, supporting evidence, identified gaps, and remediation actions required to improve compliance.

<strong>Why This Step Was Important</strong><br>
The Compliance Matrix helps measure the organization's current compliance posture and identify areas requiring improvement.
It provides visibility into:
<ul>
 <li>Implemented controls</li>
 <li>Partially implemented controls</li>
 <li>Missing controls</li>
 <li>Compliance gaps</li>
 <li>Remediation priorities</li>
 <li>Ownership and accountability</li>
</ul>
This information supports audit readiness and continuous improvement efforts.


<p align="center">
 <strong>Step Twelve: Gap Assessment & Remediation Summary (One Page) </strong><br/>
  <img src="https://i.imgur.com/LuAHnB1.png" height="80%" width="80%" alt="SaveRecords"/>
  <img src="https://i.imgur.com/x9iJo1P.png" height="80%" width="80%" alt="SaveRecords"/>
  <img src="https://i.imgur.com/c7hAa4D.png" height="80%" width="80%" alt="SaveRecords"/>

<strong>Why This Step Was Important</strong><br>
This one page was written for management, not auditors. The goal is to summarize the most important compliance weaknesses discovered during the assessment and explain what the organization should do next.


<p align="center">
 <strong>Step Thirteen: Write Executive Summary & Compliance Program Overview (One Page)</strong><br/>
  <img src="" height="80%" width="80%" alt="SaveRecords"/>

<strong>Why This Step Was Important</strong><br>
This one page summarizes what the organization is, what was assessed, what was found, and what should happen next. This is an overview of the entire project.

   
<h2>Lessons Learned:</h2>
This project helped me understand how gaps in controls directly translate into operational and compliance risk, especially in environments handling sensitive data like PHI.


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
