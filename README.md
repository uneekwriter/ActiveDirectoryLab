<br> 
<h1>Active Directory Lab</h1>

<h2>OBJECTIVE:</h2>
Create the Organizational Units schema for your organization. Add users and groups to the corresponding OU.

In this lab you will
Create Users using AD DS
Create Groups using AD DS
Create OU using AD DS

<h2>Scenario:</h2>

You are requested to create some User accounts, Groups, and OUs under the labscholas.local domain.  
They have requested the following:
Add 9 users
Add the following Organizational Units:
OU- New York
           -SubOU Sales
                    -SubOU Users
           -SubOU IT
                    - SubOU Users
           -SubOU HR
                    -SubOU Users
Place the users in the organizational units based on their role in the organization.
Create User Groups: one for all the users on the New York site and a group for each department.

<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Win 10 Lab VM</b> 
- <b>Win Server 2016 Lab VM</b>

<h2>Lab walk-through:</h2>

<p align="center">
Launch the Virtual Machines: <br/>
<img src="https://imgur.com/RkDlW1Q.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Create Users in Active Directory:  <br/>
<img src="https://imgur.com/eVrmg3H.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
All users created: <br/>
<img src="https://imgur.com/A0sNWWb.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Create Organization Users:  <br/>
<img src="https://imgur.com/XcSCpyE.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
All OU’s created in New York:  <br/>
<img src="https://imgur.com/16bjIQp.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
All Users added to NY Users:  <br/>
<img src="https://imgur.com/gGF6cYY.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Groups Part 2 (Sales Dept):  <br/>
<img src="https://imgur.com/DX2EudG.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Groups (IT Dept:  <br/>
<img src="https://imgur.com/5cXRmly.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Groups (HR Dept):  <br/>
<img src="https://imgur.com/7LYBVh7.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Test User Login and update password:  <br/>
<img src="https://imgur.com/GmoWbBn.png" height="80%" width="80%" alt="Active Directory Steps"/>
<br />
<br />
Settings > About AD Domain Check:  <br/>
<img src="https://imgur.com/9fK99tT.png" height="80%" width="80%" alt="Active Directory Steps"/>

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
