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

 I needed a clear story for the compliance environment so first, I identify from personal experience of the type of jobs I worked. Healthcare came to mind. Healthcare is naturally high compliance relevance (HIPAA, ISO 27001, etc). With healthcare comes electronic records and data types like PII and PHI. 
  <ul>
  <li>Compliance Environment Story: A healthcare clinic called SaveRecords that stores electronic patient records and protects confidential data (PII/PHI)</li>
 </ul>
     
<p align="center">
 <strong>Phase Two: Define Assets, Systems, Users & Data Types with ChatGPT Assistance</strong> <br/>

 Once I created the compliance enviroment story, I ask ChatGPT to list the assets, systems, users, and data types that fits to this compliance environment story. 
 <ul>
  <li>Assets: EMR application (custom web app), Cloud database (AWS), Staff laptops/workstations, Internet routers/firewalls, Patient data repository (contains PII and PHI)</li>
  <li>Systems: AWS (hosting and data storage), EMR platform (used by staff), Internal email and file-sharing tools</li>
  <li>Users: Doctors, Admin Staff, Nurses, IT Support</li>
  <li>Data Types: Personally Identifiable Information (PII), Protected Health Information (PHI)</li>
 </ul>

This gives me a nice scoping statement I can plug into my ISO 27001 documents later.  It defines what's in scope (systems, assets, data) and who interacts with them.

<p align="center">
 <strong>Phase Three: Write out the Scope Summary </strong> <br/>

 I basically reviewed Phase Two and wrote a quick scope summary around this fictional company (SaveRecords Health Clinic)

Scope Summary:
SaveRecords Health Clinic operates an internal patient management system where doctors, nurses, and admin staff access patient records stored in a secure cloud environment. The scope of this compliance program includs the clinics information systems, electronic medical record (EMR) platforms, staff laptops and patient data store in the cloud.
 
<p align="center">
 <strong>Phase Four: Choose A Framework </strong> <br/>

 I chose (ISO 27001 Annex A) for my healthcare clinic scenario because it's globally recognized, risk based, and structured for exactly what SaveRecords needs which is protecting PII and PHI in a systematic way. 


<br />
<br />

<h2>Lessons Learned:</h2>
<ul>
 <li>Understanding how compliance frameworks are structured</li>
 <li>Learning how to map controls to business processes</li>
 <li>Identifying gaps and building remediation plans</li>
 <li>Documenting compliance maturity in a clear, structured format</li>
</ul>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
