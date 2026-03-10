<h1>Mini Compliance Program</h1>

<h2>Video Demonstration</h2>
 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
This repository demonstrates how I built a mini compliance program by selecting a framework (ISO 27001 Annex A) and creating a fictional healthcare clinic called SaveRecords that stores electronic patient records containing PII and PHI. 
<br />

<h2>Framework Used</h2>

- <b>ISO 27001 Annex A</b>

<h2>Task To Complete</h2>

- <b>Choose a fictional company (for example, a SaaS startup or healthcare clinic) and define its scope: assets, systems, users, and data types.</b>
- <b>Download the ISO 27001 Annex A control list or NIST 800-53 catalog to use as your baseline requirements.</b>
- <b>Create a spreadsheet with columns such as Control ID, Requirement, Current Status, Owner, and Needed Actions.</b>
- <b>Select at least 15–20 controls that apply to your environment and document whether they are implemented, partially implemented, or missing.</b>
- <b>Write a brief one-page “Compliance Program Overview” describing your chosen scope, goals, and current level of maturity.</b>
- <b>Highlight 3–5 gaps and propose realistic remediation steps that an organization could take to improve compliance readiness.</b>
- <b>Store all evidence (matrix, notes, document drafts) as part of your growing portfolio.</b>


<h2>Program walk-through:</h2>

<p align="center">
 Phase One: Define The Fictional Organization <br/>

 I needed a clear story for the compliance environment so I thought of this like world-building for risk professionals.
     
 - <b>Compliance Environment Story: A healthcare clinic called SaveRecords that stores electronic patient records containing PII and PHI.</b>

<br />

<p align="center">
 Phase Two: Define Assets, Systems, Users & Data Types with ChatGPT Assistance <br/>

 Once I created the compliance enviroment story, I ask ChatGPT to list the assets, systems, users, and data types that fits to this compliance environment story. 
  - <b>Assets: EMR application (custom web app), Cloud database (AWS), Staff laptops/workstations, Internet routers/firewalls, Patient data repository (contains PII and PHI)</b>
 
  - <b>Systems: EMR application (custom web app), Cloud database (AWS), Staff laptops/workstations, Internet routers/firewalls, Patient data repository (contains PII and PHI)</b>
  
  - <b>Users: EMR application (custom web app), Cloud database (AWS), Staff laptops/workstations, Internet routers/firewalls, Patient data repository (contains PII and PHI)</b>
  
  - <b>Data Types: Personally Identifiable Information (PII), Protected Health Information (PHI) </b>

<br />
<br />


Phase Two:  <br/>
 We’re going to download “Windows 10 ISO” https://www.microsoft.com/en-us/software-download/windows10ISO 
 <img src="https://i.imgur.com/riYjtQP.png" height="80%" width="80%" alt="Virtualbox"/>
 <br/> 





<br />
<br />
Step Three:  <br/>
We’re going to create our first virtual machine which is going to be our domain controller which is going to house an active directory. We’re going to give this virtual machine two network adapters, one is going to be used to connect to the outside internet and the other one that’s going to be used to connect to the virtual box, a kind of private network that the clients are going to connect to.  <br/> 
 <img src="https://i.imgur.com/EJrzmD0.png" height="80%" width="80%" alt="Virtualbox"/>
 <br/> 

<br />
<br />
Step Four:  <br/>
After our virtual machine is created, we’re going to install “Server 2019” on it and then we’re going to assign IP addresses for the internal network. The external network will automatically get IP addresses from your home network or like your home router so we don’t have to worry about it.
<br />
<br />
Step Five:  <br/>
 After we have IP Addressing setup, we’re going to name the server and then we’re going to install Active Directory and create our domain then we’re going to configure that and routing so the clients on the private network can reach the internet through the domain controller
<br />
<br />
Step Six:  <br/>
 We’re going to set up a DHCP on the domain controller so when we create our “Windows 10” machine, it can automatically get an IP address.
<br />
<br />
Step Seven:  <br/>
The last thing we do on the domain controller before we create our client virtual machine is we’re going to run a powershell script that will automatically create a thousand users in Active Directory. 
<br />
<br />
Step Eight:  <br/>
After creating the users, we’re going to create another virtual machine and install “Windows 10” on it and that virtual machine will be connected to the private virtual box network. We’re going to name that machine “Client1” and join it to the domain and then we’re going to log into it with one of our domain accounts.
<br />
<br />

<h2>Lessons Learned:</h2>

- <b>Understanding how compliance frameworks are structured</b>
- <b>Learning how to map controls to business processes</b>
- <b>Identifying gaps and building remediation plans</b>
- <b>Documenting compliance maturity in a clear, structured format</b>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
