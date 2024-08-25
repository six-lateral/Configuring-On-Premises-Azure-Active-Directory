# Active Directory Scenario Simulation

<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h2>Prerequisites</h2>

- [Installing and Configuring Active Directory in Azure](https://github.com/ben-trainer/Azure-Active-Directory-Home-Lab)
- [Understanding DNS in Azure](https://github.com/ben-trainer/dns-testing/tree/main)
- [Understanding File Permissions in Azure](https://github.com/ben-trainer/file-share-permissions/tree/main)

<h2>Objectives</h2>

<h4>Scenario Simulation</h4>

- Engage in practical simulations of diverse scenarios
- Password resets
- Group membership changes
- Account deactivations
- Develop troubleshooting skills by simulating scenarios

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Active Directory Domain Services

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (22H2)


<h1>Scenarios</h1>

<h3>1)User Account Creation</h3>

<h4>Background:</h4>

<p>A new software developer, John Smith, has been hired to join the IT department at your company. As part of the onboarding process, the IT help desk needs to create a new user account for John in Active Directory.</p>

<p><strong>Create a new user account named "John Smith" with the username "john_smith" and a temporary password.</strong></p>

<img width="324" alt="john smith" src="https://i.imgur.com/TN4rTHz.png">

<p><strong>NOTE: Make sure the "User must change password at next login" is checked</strong></p>

<img width="340" alt="developers" src="https://i.imgur.com/hXyNnG3.png">


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong> Assign John to the "Software Developers" security group in Active Directory.</strong></p>

<img width="340" alt="developers" src="https://i.imgur.com/4BgzhnH.png">

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>Ensure that John's account is located in the appropriate Organizational Unit (OU) for IT staff.</strong></p>

<img width="340" alt="check" src="https://i.imgur.com/jMy310h.png">

<br>
<br>

- Communicate the login credentials and temporary password to John through a secure channel.
- Document the date and time of account creation for auditing purposes.

<h3>2) Password Reset </h3>

<h4>Background:</h4>

<p> Thomas Anderson, a marketing executive, contacts the IT help desk reporting that he has forgotten his password and is unable to access his computer and email. The help desk needs to assist Thomas in resetting his password in Active Directory.</p>

<p><strong> Locate Thomas' user account and initiate a password reset.</strong></p>

<img width="383" alt="reset password" src="https://i.imgur.com/FDbTuQm.png">


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Set a temporary password for Sarah that complies with the company's password policy.</strong></p>

<img width="383" alt="enable acc" src="https://i.imgur.com/rq7rkqi.png">

<p><strong>NOTE: Make sure to click the highlighted boxes to ensure the user’s account is unlocked and enable them to set their own password. The final product should result in this prompt.</strong></p>

<img width="383" alt="enable acc" src="https://i.imgur.com/j1WqIb8.png">

- Communicate the temporary password to Thomas through a secure channel and instruct his to change it immediately upon login.
- Provide guidance on how to change the password using the company's self-service password reset tool if available.
- Document the date and time of account creation for auditing purposes.

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>3) Group Membership Update </h3>

<h4>Background:</h4>

<p>Jennifer Doe, an assistant manager, has recently been promoted to a managerial role within the IT department. As part of her new responsibilities, Jennifer now requires access to specific network resources and project folders. The IT help desk needs to update Jennifer's group memberships in Active Directory accordingly.</p>

<p><strong>Locate Jennifer's user account and review her current group memberships.</strong></p>

<img width="304" alt="Jennifer " src="https://i.imgur.com/Fd3ke9y.png">

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Remove Jennifer from the "Assistant Manager" group and add her to the "IT Managers" group.</strong></p>

<img width="303" alt="IT managers" src="https://i.imgur.com/DEpyXxg.png">

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Confirm that Jennifer now has the necessary access rights to project folders and relevant network resources.</strong></p>

<img width="600" alt="image" src="https://i.imgur.com/JBz6EY5.png">


- Communicate the group membership update to Jennifer, along with any additional instructions or changes in access.
- Document the whole process


<h3>4) Organizational Unit (OU) Management </h3>

<h4>Background:</h4>

<p>The Sales department has recently undergone a reorganization, resulting in the creation of a new team focused on international sales. The IT help desk needs to reflect this change in the Active Directory structure by creating a new Organizational Unit (OU) for the International Sales team and moving relevant user accounts into the new OU.
</p>

<p><strong>Create a new Organizational Unit named "International Sales" within the Sales department's organizational structure.</strong></p>

<img width="323" alt="International Sales" src="https://i.imgur.com/Md3Kjnh.png">

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Move the user accounts of team members, such as Thomas Anderson and Xuvev God, to the newly created OU.</strong></p>

<img width="307" alt="Alex Turner to IS " src="https://i.imgur.com/RMttcW8.png">

<img width="305" alt="Maria to IS" src="https://i.imgur.com/H95pG2u.png">

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong> Verify that the users now appear under the "International Sales" OU in Active Directory.
</strong></p>

<img width="296" alt="Verify" src="https://i.imgur.com/3X3ae5K.png">

<br>
<br>

<p><strong>Communicate the organizational change to relevant stakeholders, such as department heads and team leaders.
</strong></p>

<h4>Considerations:</h4>

- Ensure that the new OU structure aligns with the company's organizational hierarchy.

- Confirm that the appropriate Group Policy settings apply to the users within the new OU.
  
- Communicate any changes in access permissions or policies resulting from the OU reorganization to the IT security team.



<h2> Lesssons Learned </h2>

<p>
I recognize Active Directory is crucial for managing user accounts and network resources. I chose to cover common IT help desk tasks, such as creating user accounts, resetting passwords, and updating group memberships to practice what may be used in a real job. I was able to learn that Active Directory has a vast amount of options when it comes to user management and there will always be something new to learn based on the job responsibilities. With practice I should be able to adapt to what is needed. </p>
