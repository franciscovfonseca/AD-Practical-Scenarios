<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1> Active Directory: Practical Scenario Simulation </h1>
<br>


Welcome to the **Active Directory: Practical Scenario Simulation** project.

In this project, we'll simulate various scenarios to enhance our understanding of ***User Provisioning***, ***Administration***, and ***Problem-Solving*** within **Active Directory**.
<br>
<br>

<h2>Prerequisites</h2>

- <a href="https://github.com/franciscovfonseca/Active-Directory-and-Azure-Setup/blob/main/README.md"> Preliminary Setup for Active Directory and Network Traffic Analysis between Azure VMs </a>
- <a href="https://github.com/franciscovfonseca/Active-Directory-Deployment-and-Configuration/blob/main/README.md"> Active Directory Deployment and Configuration </a>
- <a href="https://github.com/franciscovfonseca/Active-Directory-User-Generation/blob/main/README.md">Active Directory: User Generation </a>
<br>

<h2>Key Objectives</h2>

<h3>🟢 Scenario Simulation</h3>

- Engage in practical simulations of diverse scenarios, such as password resets, group membership changes, and account deactivations.

<h3>🟢 Troubleshooting Scenarios</h3>

- Develop troubleshooting skills by simulating scenarios where users encounter access issues, and learn to identify and resolve these challenges effectively.
<br>

<h2>Environments and Technologies Used</h2>

🔹 Microsoft Azure (Virtual Machines)

🔹 Remote Desktop

🔹 Active Directory Domain Services

<br>

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)
<br>

<h1>Scenarios</h1>

<h3>1️⃣ User Account Creation </h3>

*<h4>BACKGROUND:</h4>*

- A new software developer, John Smith, has been hired to join the IT department at your company.

- As part of the onboarding process, the IT help desk needs to **Create a New User Account** for John in **Active Directory**.
<br>


🔸 First **Create a New User Account** named *John Smith* with the Username "*john_smith*" and a Temporary Password.

<img width="324" alt="john smith" src="https://github.com/franciscovfonseca/Active-Directory-Practical-Scenario-Simulation/assets/172988970/090466f7-bb0a-418d-93de-e24dee6e9418">
<br>
<br>


⚠️ NOTE: Set the Account to ***User must change the password at next logon***.

<img width="324" alt="john smith" src="https://github.com/franciscovfonseca/Active-Directory-Practical-Scenario-Simulation/assets/172988970/b04b9990-c04c-4808-9218-498b7b7dac98">
<br>
<br>


Assign John to the "***Developers***" Security Group in Active Directory.

<img width="340" alt="developers" src="https://github.com/franciscovfonseca/Active-Directory-Practical-Scenario-Simulation/assets/172988970/08ed3545-24ff-4002-a044-9a75b8edff4c">

<br>
<br>
<br>

🔸 Then ensure that **John's Account** is located in the appropriate **Organizational Unit (OU)** for the IT staff (***Developers***):

<img width="340" alt="check" src="https://github.com/franciscovfonseca/Active-Directory-Practical-Scenario-Simulation/assets/172988970/ec0f5e0e-f753-49ef-bcd8-429305fdaed0">

<br>
<br>
<br>

➜ Communicate the **Login Credentials** and **Temporary Password** to John through a secure channel.

➜ Document the **Date and Time of Account Creation** for auditing purposes.
  
<br>


*<h4>CONSIDERATIONS:</h4>*

✔ The Temporary Password should meet the Company's Password Policy Requirements.

✔ Ensure that John has the Necessary Permissions and Group Memberships to access the Resources required for his role.

<br>
<br>

<h2></h2>

<h3>2️⃣ Password Reset </h3>

*<h4>BACKGROUND:</h4>*

- Sarah Thompson, a marketing executive, contacts the IT help desk reporting that she has forgotten her password and is unable to access her computer and email.

- The help desk needs to assist Sarah in resetting her password in Active Directory.
<br>


🔸 Locate Sarah's user account and initiate a password reset.

<img width="383" alt="reset password" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/c74f2c28-6fd8-4d3e-b3ed-7e16d14d1364">

<br>
<br>
<br>


Set a temporary password for Sarah that complies with the company's password policy.

⚠️ NOTE: Make sure to click the highlighted boxes to ensure the user’s account is unlocked and enable them to set their own password.

<img width="383" alt="enable acc" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/85e43120-0d23-4cb8-a8e2-6e64005a7303">

<br>
<br>
<br>

➜ Communicate the **Temporary Password** to Sarah through a secure channel and instruct her to **Change it Immediately upon Login**.

➜ Provide guidance on **How to Change the Password** using the company's **Self-service Password Reset Tool** if available.

➜ Document the **Date and Time of Account Creation** for auditing purposes.
  
<br>


*<h4>CONSIDERATIONS:</h4>*

✔ Ensure that the chosen temporary password is strong and complies with the company's password policy.

✔ Remind Sarah to update the password on any additional devices or applications where the old password was saved.


<br>
<br>

<h2></h2>

<h3>3️⃣ Group Membership Update </h3>

<h4>Background:</h4>

<p>Emma Rodriguez, a systems analyst, has recently been promoted to a managerial role within the IT department. As part of her new responsibilities, Emma now requires access to specific network resources and project folders. The IT help desk needs to update Emma's group memberships in Active Directory accordingly.</p>

<p><strong>Locate Emma's user account and review her current group memberships.</strong></p>

<img width="304" alt="Emma " src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/e0f15108-dcdb-477d-8de4-5f3747e5ea07">

<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Remove Emma from the "Systems Analysts" group and add her to the "IT Managers" group.</strong></p>

<img width="303" alt="IT managers" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/5120932a-c9de-45d9-9419-383bf839bbc4">

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>Confirm that Emma now has the necessary access rights to project folders and relevant network resources.</strong></p>

<img width="600" alt="image" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/aadea113-c15b-4135-93d8-8b4ebf48de04">


- Communicate the group membership update to Emma, along with any additional instructions or changes in access.
- Document the whole process


<h4>Considerations:</h4>

- Ensure that Emma's new group memberships align with her managerial responsibilities.
- Communicate the changes to other relevant parties, such as the IT security team, to maintain awareness.
- Verify that Emma's access permissions are correctly configured after the group membership update.

<h3>&#9315; Account Deactivation </h3>

<h4>Background:</h4>

<p>Mark Johnson, a network administrator, has recently resigned from the company. The IT help desk needs to deactivate Mark's user account in Active Directory to prevent unauthorized access and ensure the security of company resources.</p>

<p><strong>Locate Mark's user account and initiate the account deactivation process.</strong></p>

<img width="421" alt="makr" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/0a51e96b-9dce-4bf6-a22f-92943f6e8a20">

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>Disable Mark's account to prevent further logins while retaining the account details for reference.</strong></p>

<img width="470" alt="disable" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/da07b6af-1ba3-467a-b0a0-8109afc37bfb">

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>You may receive a confirmation dialog; click "Yes" to confirm the disabling of the user account.</strong></p>

<img width="223" alt="disable 2" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/5b5bdfe6-996d-4ff3-8201-4cd9549bdd46">

<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Remove Mark from all security groups to revoke his access to network resources.</strong></p>

<img width="295" alt="remove mark" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/1613e604-3e4c-462f-8c30-ea0dd7fed0bf">

<br>
<br>

<p><strong> Confirm with other relevant departments (e.g., HR) that Mark's departure aligns with company policies and document the whole process.</strong></p>

<h4>Considerations:</h4>

- Ensure a smooth transition of Mark's responsibilities to other team members.

-  Communicate the account deactivation to other departments, such as HR and security, for coordinated efforts.

-  Retain Mark's user account details for historical records and potential future reference.
   
-  Conduct a review of Mark's access rights to identify and update any shared resources associated with his account.

<h3>&#9316; Organizational Unit (OU) Management </h3>

<h4>Background:</h4>

<p>The Sales department has recently undergone a reorganization, resulting in the creation of a new team focused on international sales. The IT help desk needs to reflect this change in the Active Directory structure by creating a new Organizational Unit (OU) for the International Sales team and moving relevant user accounts into the new OU.
</p>

<p><strong>Create a new Organizational Unit named "International Sales" within the Sales department's organizational structure.</strong></p>

<img width="323" alt="International Sales" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/19db8909-74bf-4e02-8b5d-353bce7818ee">

<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Move the user accounts of team members, such as Alex Turner and Maria Sanchez, to the newly created OU.</strong></p>

<img width="307" alt="Alex Turner to IS " src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/ff044b9d-17ee-4b8d-8b40-0f55dff95070">

<img width="305" alt="Maria to IS" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/641b24cb-156c-4a32-8edd-bc9041ca3741">

<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong> Verify that the users now appear under the "International Sales" OU in Active Directory.
</strong></p>

<img width="296" alt="Verify" src="https://github.com/kirkgacias/ad-scenario-simulation/assets/158519921/8c4884d1-e16a-48a6-a492-6cc12f6e91e8">

<br>
<br>

<p><strong>Communicate the organizational change to relevant stakeholders, such as department heads and team leaders.
</strong></p>

<h4>Considerations:</h4>

- Ensure that the new OU structure aligns with the company's organizational hierarchy.

- Confirm that the appropriate Group Policy settings apply to the users within the new OU.
  
- Communicate any changes in access permissions or policies resulting from the OU reorganization to the IT security team.



<h2> Final Thoughts </h2>

<p>
In summary, Active Directory is crucial for managing user accounts and network resources. The scenarios provided cover common IT help desk tasks, such as creating user accounts, resetting passwords, updating group memberships, and handling account deactivation. These scenarios serve as practical exercises for training IT personnel and highlight the importance of Active Directory in maintaining a secure and organized digital environment. </p>







