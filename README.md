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
 <li>Download the ISO 27001 Annex A control list or NIST 800-53 catalog to use as your baseline requirements.</li>
 <li>Identify and document critical organizational assets, systems, users, and data types requiring protection.</li>
 <li>Determine potential cybersecurity threats and vulnerabilities affecting healthcare systems and patient data.</li>
 <li>Create realistic risk scenarios demonstrating how threats could exploit vulnerabilities.</li>
 <li>Perform a risk assessment using likelihood and impact scoring to prioritize risks.</li>
 <li>Develop a structured risk register to document identified risks and remediation efforts.</li>
 <li>Identify existing security controls currently protecting organizational assets.</li>
 <li>Recommend additional security controls to reduce the likelihood or impact of identified risks.</li>
 <li>Assign ownership and treatment strategies for each identified risk.</li>
 <li>Map identified risks to 15-20 relevant ISO/IEC 27001 Annex A controls.</li>
 <li>Identify examples of audit evidence used to validate control implementation and effectiveness.</li>
 <li>Demonstrate foundational governance, risk management, and compliance (GRC) practices within a healthcare environment.</li>
</ul>

<h2>Program walk-through:</h2>

<p align="center">
  <strong>Phase One: Define The Fictional Organization</strong> <br/>

 I needed a clear story for the compliance environment so first, I identify from personal experience of the type of jobs I worked. Healthcare came to mind. Healthcare is naturally high compliance relevance (HIPAA, ISO 27001, etc), electronic records and data types like PII and PHI. 

 I created a healthcare clinic called SaveRecords that stores and manages electronic patient records in a cloud environment.
  <ul>
  <img src="https://i.imgur.com/OgEUlUn.png" height="80%" width="80%" alt="SaveRecords"/></li>
 </ul>
     
<p align="center">
 <strong>Phase Two: Define Assets, Systems, Users & Data Types</strong> <br/>

 From there, I define the full compliance scope including assets like: 
 <ul>
  <li><strong>EMR Systems (EMR Application & Platform)</strong><img src="https://i.imgur.com/bGSYZMf.png" height="80%" width="80%" alt="SaveRecords"/></li>
  <li><strong>Cloud Database:</strong><br/><img src="https://i.imgur.com/NTzHrhE.png" height="80%" width="80%" alt="SaveRecords"/></li>
   <li><strong>Users (Doctors, Admin Staff, Nurses, IT Support):</strong><br/><img src="https://i.imgur.com/4mf0V0q.png" height="80%" width="80%" alt="SaveRecords"/></li>
    <li><strong>Sensitive Data Types (Like PII and PHI):</strong><br/><img src="https://i.imgur.com/6yKDBji.png" height="80%" width="80%" alt="SaveRecords"/><br/><img src="https://i.imgur.com/APxuRxJ.png" height="80%" width="80%" alt="SaveRecords"/></li>
 </ul>

You cannot protect what you do not know exists. This process provides the visibility needed to apply appropriate security controls and meet compliance mandates.

<p align="center">
 <strong>Phase Three: Write out the Scope Summary </strong> <br/>

 I basically reviewed Phase Two and wrote a quick scope summary around this fictional company (SaveRecords Health Clinic) This defines what's in scope (systems, assets, data) and who interacts with them.

<strong>Scope Summary:</strong>
SaveRecords Health Clinic operates an internal patient management system where doctors, nurses, and admin staff access patient records stored in a secure cloud environment. The scope of this compliance program includes the clinics information systems, electronic medical record (EMR) platforms, staff laptops and patient data stored in the cloud.

<p align="center">
 <strong>Phase Four: Perform Risk Assessment (Create Risk Register)</strong> <br/>

I built a structured risk assessment process where my risk register documents important assets, the threats affecting them, associated vulnerabilities, and how those risks are managed. I provide risk scenarios to connect assets, threats, and vulnerabilities into realistic business situations so risks could be clearly understood and prioritized. I used likelihood and impact scoring to prioritize risks.

<strong>Risk Register Table</strong>
 <ul>
  <img src="https://i.imgur.com/SHImMIl.png" height="80%" width="80%" alt="Risk Register Table"/></li>
 </ul>

<strong>Risk Assessment Scoring Framework</strong>
 <ul>
  <img src="https://i.imgur.com/tP9S8qC.png" height="80%" width="80%" alt="Risk Assessment Scoring Framework"/></li>
 </ul>

 
<p align="center">
 <strong>Phase Five: Choose A Framework and Select 20 Controls </strong> <br/>

 <strong>ISO 27001 Annex A Framework Information:</strong><br>
https://www.isms.online/iso-27001/annex-a-2022/
 
 I chose <strong>(ISO 27001 Annex A framework)</strong> for my healthcare clinic scenario because it's globally recognized, risk based, and structured for exactly what SaveRecords needs, which is protecting PII and PHI in a systematic way. 
 
 <strong>ISO 27001 (Annex A)</strong> has 93 controls grouped under four themes:
<ul>
 <li>Organization (A.5 - A.8 - 37 Controls): Policies, procedures, and governance.</li>
 <li>People (A.6 - 8 Controls): Background checks, training, and awareness.</li>
 <li>Physical (A.7 - 14 Controls): Secure areas, equipment, and surveillance.</li>
 <li>Technological (A.8 - 34 Controls): Network security, encryption, and access management.</li>
</ul>

I mapped each identified risk to 20 relevant specific IS0 270001 Annex A controls. These controls were chosen to reduce the chance or impact of each risk happening.

<strong>EMR System (Unauthorized Access)</strong><br/>
 Electronic Medical Records contain sensitive patient information. If the wrong person gets access, patient privacy, trust, and legal compliance are affected. <br/>
<strong>Controls</strong>: 
<ul>
 <li><strong>ISO 27001 A.5.15 — Access Control:</strong> This matters because it ensures only authorized staff can access the EMR system. Doctors, nurses, and admins should only see the information needed for their jobs. Without access control, anyone inside the organization could view or misuse patient records.</li>
 <li><strong>ISO 27001 A.8.2 — Privileged Access Rights:</strong> This matters because administrator accounts have powerful permissions. If admin access is not tightly controlled, a single compromised account could expose or alter thousands of patient records.</li>
 <li><strong>ISO 27001 A.8.3 — Information Access Restriction:</strong> This matters because it limits access to sensitive medical data based on role or department. For example, billing staff should not have the same access as medical providers. This reduces insider threats and accidental exposure.</li>
</ul>

<strong>Cloud Database (Data Breach)</strong><br/>
Cloud databases often store patient information, appointments, and billing data. A breach could expose large amounts of confidential information. <br/>
 <strong>Controls</strong>:
<ul>
 <li><strong>ISO 27001 A.8.5 — Secure Authentication:</strong> This matters because weak passwords or poor login protection make it easier for attackers to break into the database. Strong authentication helps stop unauthorized access.</li>
 <li><strong>ISO 27001 A.8.24 — Use of Cryptography:</strong> This matters because encryption protects sensitive data even if attackers steal it. Encrypted patient records are much harder to read or misuse.</li>
 <li><strong>ISO 27001 A.8.9 — Configuration Management:</strong> This matters because misconfigured cloud settings are one of the biggest causes of data breaches. Proper configuration ensures security settings are correct and continuously maintained.</li>
</ul>

<strong>Staff Laptop (Device Theft)</strong><br/>
Healthcare workers often use laptops containing patient records, emails, and internal systems. A stolen laptop can become a major security incident. <br/>
 <strong>Controls</strong>:
<ul>
 <li><strong>ISO 27001 A.7.10 — Storage Media:</strong> This matters because sensitive information stored on laptops or removable drives must be protected. Encryption and secure storage reduce the damage if the laptop is stolen.</li>
 <li><strong>ISO 27001 A.8.1 — User Endpoint Devices:</strong> This matters because laptops are endpoint devices frequently targeted by attackers. Security controls like device locking, antivirus software, and remote wipe help protect data.</li>
</ul>

<strong>Staff Email (Phishing)</strong><br/>
Phishing emails trick employees into clicking malicious links or giving away passwords. Healthcare organizations are common targets because of valuable patient data. <br/>
 <strong>Controls</strong>:
<ul>
 <li><strong>ISO 27001 A.6.3 — Information Security Awareness, Education and Training:</strong> This matters because employees are the first line of defense. Training helps staff recognize suspicious emails, fake login pages, and social engineering attacks.</li>
 <li><strong>ISO 27001 A.8.7 — Protection Against Malware:</strong> This matters because phishing emails often deliver malware or ransomware. Anti-malware tools help detect and block malicious files before they infect systems.</li>
</ul>

<strong>Patient Data (Unauthorized Access)</strong><br/>
Patient information is highly confidential and protected by privacy laws. Unauthorized access can lead to identity theft, lawsuits, and loss of trust. <br/>
 <strong>Controls</strong>:
<ul>
 <li><strong>ISO 27001 A.5.34 — Privacy and Protection of Personally Identifiable Information (PII):</strong> This matters because healthcare organizations must protect patient personal data and comply with privacy regulations. The control ensures patient information is collected, stored, and handled securely.</li>
 <li><strong>ISO 27001 A.8.3 — Information Access Restriction:</strong> This matters because not every employee should have access to all patient records. Restricting access reduces the chance of misuse or accidental disclosure.</li>
</ul>

<strong>Servers (Ransomware)</strong><br/>
Ransomware can encrypt healthcare systems, making patient records and services unavailable. This can disrupt patient care and operations. <br/>
 <strong>Controls</strong>:
<ul>
 <li><strong>ISO 27001 A.8.8 — Management of Technical Vulnerabilities:</strong> This matters because outdated software and unpatched systems are common ransomware entry points. Regular patching closes security weaknesses attackers exploit.</li>
 <li><strong>ISO 27001 A.8.13 — Information Backup:</strong> This matters because backups allow organizations to restore systems after a ransomware attack without paying attackers. Backups are critical for recovery.</li>
 <li><strong>ISO 27001 A.8.16 — Monitoring Activities:</strong> This matters because continuous monitoring helps detect suspicious behavior early, such as unusual file encryption or unauthorized activity on servers.</li>
</ul>

<strong>Network Devices (Intrusion)</strong><br/>
Routers, switches, and firewalls manage network traffic. If attackers compromise these devices, they may gain access to the entire healthcare network. <br/>
 <strong>Controls</strong>:
<ul>
 <li><strong>ISO 27001 A.8.20 — Network Security:</strong> This matters because it protects networks from unauthorized access and attacks. Firewalls, segmentation, and secure configurations help defend healthcare systems.</li>
 <li><strong>ISO 27001 A.8.21 — Security of Network Services:</strong> This matters because network services such as internet access, VPNs, and remote connections must be secured and monitored to prevent intrusions.</li>
</ul>

<strong>Security Cameras (Unauthorized Access)</strong><br/>
Security cameras protect physical areas of the healthcare facility. If compromised, attackers could spy on patients or staff or disable surveillance. <br/>
 <strong>Controls</strong>:
<ul>
 <li><strong>ISO 27001 A.7.4 — Physical Security Monitoring:</strong> This matters because cameras are part of physical security protection. Monitoring helps detect unauthorized physical access and security incidents.</li>
 <li><strong>ISO 27001 A.8.9 — Configuration Management:</strong> This matters because poorly configured cameras often have weak passwords or outdated firmware. Proper configuration reduces the risk of unauthorized access to surveillance systems.</li>
</ul>

<p align="center">
<strong>Phase Six: Control Mapping Table</strong> <br/>

 The purpose of this control mapping table is to:
<ul>
 <li>identified risks within the SaveRecords Health Clinic environment to relevant ISO/IEC 27001 controls</li>
 <li>demonstrate how security controls are selected based on risk and how their effectiveness can be validated through measurable evidence</li>
 <li>corresponding audit evidence.</li>
</ul>

<p align="center">
 <img src="https://i.imgur.com/zJ36ShI.png" height="80%" width="80%" alt="twentyControls"/>

I added existing controls, recommended controls, ownership, treatment decisions, and remediation status to my risk register table to simulate a real-world GRC workflow.

<p align="center">
 <img src="https://i.imgur.com/3LQwOKN.png" height="80%" width="80%" alt="twentyControls"/>


   
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
