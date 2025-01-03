<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (22H2)

<h2>Ticket Lifecycle Stages</h2>

1. **Intake**
2. **Assignment and Communication**
3. **Working the Issue**
4. **Resolution**

<h2>Lifecycle Stages</h2>

<h3>1.) Create Tickets as End-Users</h3>

- **Scenario 1:** Create a ticket as an end-user with the following details:
  - **Subject:** "Entire mobile/online banking system is down"
  - **Details:** Describe the issue briefly (e.g., "The entire online banking system is down, preventing users from accessing their accounts.")

<p>
<img src="https://i.imgur.com/Y6Xptx1.png" height="80%" width="80%" alt="Lab 3 Step 3"/>
</p>

<h3>2.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.
 
<p>
<img src="https://i.imgur.com/LjDNXwD.png" height="80%" width="80%" alt="Lab 3 Step 3"/>
</p>

<h3>3.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-A (1 hour, 24/7).
  - **Assigned To:** Online Banking Department.

<p>
<img src="https://i.imgur.com/cisoLqw.png" height="80%" width="80%" alt="Lab 3 Step 3"/>
</p>

<h3>4.) Verify Ticket Permissions</h3>

- Log back in as **Help Desk Agent (john)**.
- Attempt to view or modify the ticket. Verify whether the changes are accessible or editable.

<h3>5.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (jane)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

<p>
<img src="https://i.imgur.com/9xTQiJv.png" height="80%" width="80%" alt="Lab 3 Step 3"/>
</p>

---

<h3>6.) Create Another Ticket as End-User</h3>

- **Scenario 2:** Create a ticket as an end-user with the following details:
  - **Subject:** "Accounting department needs Adobe upgrade, broken"
  - **Details:** Describe the issue briefly (e.g., "The Adobe software used by the accounting department is broken and needs an upgrade.")
 
<p>
<img src="https://i.imgur.com/oOqE4OE.png" height="80%" width="80%" alt="Lab 3 Step 3"/>
</p>

<h3>7.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.
 
<p>
<img src="https://i.imgur.com/jJBm8Pa.png" height="80%" width="80%" alt="Lab 3 Step 3"/>
</p>

<h3>8.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-B (4 hours, 24/7).
  - **Department:** Support.
 
<p>
<img src="https://i.imgur.com/jeRS4dt.png" height="80%" width="80%" alt="Lab 3 Step 3"/>
</p>

<h3>9.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (john)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

<p>
<img src="https://i.imgur.com/v7cimS1.png" height="80%" width="80%" alt="Lab 3 Step 3"/>
</p>

---

<h3>10.) Create a Final Ticket as End-User</h3>

- **Scenario 3:** Create a ticket as an end-user with the following details:
  - **Subject:** "CFO’s laptop will no longer turn on"
  - **Details:** Describe the issue briefly (e.g., "The CFO's laptop is not powering on, and it needs urgent attention.")
 
<p>
<img src="https://i.imgur.com/FF8TDmh.png" height="80%" width="80%" alt="Lab 3 Step 3"/>
</p>

<h3>11.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.

<p>
<img src="https://i.imgur.com/BOIMfD3.png" height="80%" width="80%" alt="Lab 3 Step 3"/>
</p>

<h3>12.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-B (4 hours, 24/7).
  - **Department:** Support.

<p>
<img src="https://i.imgur.com/5QIMpDf.png" height="80%" width="80%" alt="Lab 3 Step 3"/>
</p>

<h3>13.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (john)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

---

<h2>Conclusion</h2>

By following these steps, you have successfully demonstrated the lifecycle of a ticket from intake to resolution within osTicket. This lab highlights the importance of ticket properties, proper assignment, and resolution processes in a help desk environment.
