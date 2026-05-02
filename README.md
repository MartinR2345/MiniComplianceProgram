<h1>Mini Compliance Program</h1>

<h2>Video Demonstration</h2>
 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
This repository demonstrates how I built a mini compliance program by selecting a framework (ISO 27001 Annex A) and creating a fictional healthcare clinic called SaveRecords that stores electronic patient records.
<br />

<h2>Framework Used</h2>

<ul> <li>ISO 27001 Annex A</li>

</ul>

<h2>Task To Complete</h2>

<ul>
  <li>Choose a fictional company (for example, a SaaS startup or healthcare clinic) and define its scope: assets, systems, users, and data types.</li>
  <li>Download the ISO 27001 Annex A control list or NIST 800-53 catalog to use as your baseline requirements.</li>
  <li>Create a spreadsheet with columns such as Control ID, Requirement, Current Status, Owner, and Needed Actions.</li>
 <li>Select at least 15–20 controls that apply to your environment and document whether they are implemented, partially implemented, or missing.</li>
 <li>Write a brief one-page “Compliance Program Overview” describing your chosen scope, goals, and current level of maturity.</li>
 <li>Highlight 3–5 gaps and propose realistic remediation steps that an organization could take to improve compliance readiness.</li>
 <li>Store all evidence (matrix, notes, document drafts) as part of your growing portfolio.</li>
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
 <strong>Phase Two: Define Assets, Systems, Users & Data Types with ChatGPT Assistance</strong> <br/>

 From there, I define the full compliance scope including assets like: 
 <ul>
  <li><strong>EMR Systems (EMR Application & Platform)</strong><img src="https://i.imgur.com/bGSYZMf.png" height="80%" width="80%" alt="SaveRecords"/></li>
  <li><strong>Cloud Database:</strong><br/><img src="https://i.imgur.com/NTzHrhE.png" height="80%" width="80%" alt="SaveRecords"/></li>
   <li><strong>Users (Doctors, Admin Staff, Nurses, IT Support):</strong><br/><img src="https://i.imgur.com/4mf0V0q.png" height="80%" width="80%" alt="SaveRecords"/></li>
    <li><strong>Sensitive Data Types (Like PII and PHI):</strong><br/><img src="https://i.imgur.com/6yKDBji.png" height="80%" width="80%" alt="SaveRecords"/><br/><img src="https://i.imgur.com/APxuRxJ.png" height="80%" width="80%" alt="SaveRecords"/></li>
 </ul>

<p align="center">
 <strong>Phase Three: Write out the Scope Summary </strong> <br/>

 I basically reviewed Phase Two and wrote a quick scope summary around this fictional company (SaveRecords Health Clinic) This defines what's in scope (systems, assets, data) and who interacts with them.

<strong>Scope Summary:</strong>
SaveRecords Health Clinic operates an internal patient management system where doctors, nurses, and admin staff access patient records stored in a secure cloud environment. The scope of this compliance program includs the clinics information systems, electronic medical record (EMR) platforms, staff laptops and patient data store in the cloud.

<p align="center">
 <strong>Phase Four: Perform Risk Assessment (Create Risk Register)</strong> <br/>

My risk register documents important assets, the threats affecting them, associated vulnerabilities, and how those risks are managed. I used likelihood and impact scoring to prioritize risks, then added existing controls, recommended controls, ownership, treatment decisions, and remediation status to simulate a real-world GRC workflow.

<strong>Risk Register Table</strong>
 <ul>
  <img src="https://i.imgur.com/KzQKg9Y.png" height="80%" width="80%" alt="Risk Register Table"/></li>
 </ul>

<strong>Risk Assessment Scoring Framework</strong>
 <ul>
  <img src="https://i.imgur.com/tP9S8qC.png" height="80%" width="80%" alt="Risk Assessment Scoring Framework"/></li>
 </ul>

 
<p align="center">
 <strong>Phase Five: Choose A Framework and Select 20 Controls </strong> <br/>

 <strong>ISO 27001 Annex A Framework Information:</strong><br>
https://www.isms.online/iso-27001/annex-a-2022/
 
 I chose <strong>(ISO 27001 Annex A framework)</strong> for my healthcare clinic scenario because it's globally recognized, risk based, and structured for exactly what SaveRecords needs which is protecting PII and PHI in a systematic way. 
 
 <strong>ISO 27001 (Annex A)</strong> has 93 controls group under four themes:
<ul>
 <li>Organization (A.5 - A.8 - 37 Controls): Policies, procedures, and governance.</li>
 <li>People (A.6 - 8 Controls): Background checks, training, and awareness.</li>
 <li>Physical (A.7 - 14 Controls): Secure areas, equipment, and surveilance.</li>
 <li>Technological (A.8 - 34 Controls): Network security, encryption, and access management.</li>
</ul>

I selected 20 relevant controls out of 93 controls across organizational, physical, and technical domains and added it on a spreadsheet. On this spreadsheet I have three columns:
 
Column 1 is <strong>Control ID</strong> <br/>
Column 2 is the <strong>Control Name</strong> <br/>
Column 3 is <strong>Why It Matters to Save Records Healthclinic</strong> <br/>    

<p align="center">
 <img src="https://i.imgur.com/JubBivS.png" height="80%" width="80%" alt="twentyControls"/>
<br />

<p align="center">
 <strong>Phase Six:  Build Control Matrix </strong> <br/>

To put this into practice, I built a mini control matrix.  This mini control matrix is essential for mitigating risks, ensuring regulatory compliance, optimizing processes, and encouraging accountability within an organization.

On the spreadsheet display, I have:

Column 1 is <strong>Control ID</strong> <br/>
Column 2 is the <strong>Requirements (What does this control provides?)</strong> <br/>
Column 3 is <strong>Currrent Status (A quick self-assessment of your maturity (Implemented / Partially / Missing)</strong><br/> 
Column 4 is <strong>Owner (The person responsible for the control).</strong> <br/>
Column 5 is <strong>Needed Actions (The actions needed to reach full compliance.).</strong> <br/>  

<p align="center">
 <img src="https://i.imgur.com/cfgsLp1.png" height="80%" width="80%" alt="twentyControls"/>

 <p align="center">

 First, I wrote twenty requirements for each control then I use ChatGPT to review each control requirement and provide feedback on if it match the control or not. This way, I'm learning and ChatGPT is a mentor, not a quick fix.

<p align="center">
 <img src="https://i.imgur.com/SjMBfwo.png" height="80%" width="80%" alt="twentyControls"/>

<p align="center">
 <img src="https://i.imgur.com/rgbixPl.png" height="80%" width="80%" alt="twentyControls"/>

<p align="center">
 <img src="https://i.imgur.com/mCCk63T.png" height="80%" width="80%" alt="twentyControls"/> <br>

  <p align="center">
 <strong>Phase Seven: Assign a Maturity Rating</strong> <br/>

For the “Current Status” of each control, I used this "3-level Maturity Scale spreadsheet I created below:

<p align="center">
 <img src="https://i.imgur.com/Dbt4OFA.png" height="80%" width="80%" alt="twentyControls"/> <br>

 <strong>Implemented</strong> (Fully operational) | <strong>Partially implemented</strong> (Informal or incomplete) | <strong>Missing</strong>(No Process Yet)

 When reviewing each control, I ask myself these quick questions: <br>
 Do we have a written policy or procedure for this? <br>
 If Yes, then choose either Partially or Fully Implemented<br>
 If No, then choose Missing

 Is the process consistently followed by all staff? <br>
 If Yes, then choose Implemented <br>
 If No, then choose Partially <br>

 Is there documentation or evidence (logs, reports, training records)? <br>
 If Yes, then choose Implemented <br>
 If No, then choose either Partially or Missing <br>

 Has management reviewed or approved it recently? <br>
 If Yes, then choose Implemented <br>
 If No, then choose either Partially or Missing <br>

 Basically, instead of picking randomly, I remind myself that this should be logical so for each control, I assigned either implemented (fully operational), partially implemented (informal or incomplete), missing (no process yet) for the Current Status.

 <p align="center">
 <img src="https://i.imgur.com/umCvw0w.png" height="80%" width="80%" alt="twentyControls"/> <br>

  <p align="center">
 <img src="https://i.imgur.com/2yFDYR8.png" height="80%" width="80%" alt="twentyControls"/> <br>

  <p align="center">
 <img src="https://i.imgur.com/vWutFSE.png" height="80%" width="80%" alt="twentyControls"/> <br>

Note to Self:
I also used ChatGPT to review all of my 20 control Current Status for feedback...

  <p align="center">
 <strong>Phase Eight: Definne Needed Actions</strong> <br/>

   The “Needed Actions” column is where my matrix really comes alive. This is where I shift from identifying the state of compliance to proposing realistic next steps for SaveRecords Health Clinic. <br>
  
   The “Needed Actions” column answers one simple question: <br>
   <strong>“What’s the next step required to bring this control to full compliance?”</strong>

 <p align="center">
 <img src="https://i.imgur.com/5avzD8p.png" height="80%" width="80%" alt="twentyControls"/> <br>

  <p align="center">
 <img src="https://i.imgur.com/dgb9rDl.png" height="80%" width="80%" alt="twentyControls"/> <br>

  <p align="center">
 <img src="https://i.imgur.com/BYXD9mZ.png" height="80%" width="80%" alt="twentyControls"/> <br>

  <p align="center">
 <strong>Phase Nine: Compliance Program Overview</strong> <br/>

   The “Compliance Program Overview” is the final piece that ties this mini compliance program together. The goal was to tell the story of SaveRecords Health Clinic's security posture, what framework it follows, where it stands now, and what it plans to improve. <br>

 <p align="center">
 <img src="https://i.imgur.com/I4UYhwM.png" height="80%" width="80%" alt="twentyControls"/> <br>

  <p align="center">
 <img src="https://i.imgur.com/sXgI7na.png" height="80%" width="80%" alt="twentyControls"/> <br>

  <p align="center">
 <img src="https://i.imgur.com/eJ5OZvk.png" height="80%" width="80%" alt="twentyControls"/> <br>

   
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
