# os_lifecycle<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>

<p>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.
</p><br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>
<p>
The ticket lifecycle in osTicket refers to the various stages a support ticket goes through from its creation to resolution or closure. 
</p>

<p>
By following this ticket lifecycle, osTicket helps support teams efficiently manage customer inquiries, provide timely solutions, and maintain a transparent and organized support process. Here's a step-by-step explanation of the typical ticket lifecycle in osTicket:
</p>

<p>
1. Ticket Creation or Intake: The lifecycle begins when a customer submits a new support ticket. This can happen through various channels, such as a web form on the support portal, an email sent to a designated support email address, or even an API integration with other systems.
</p>
<p>
In this tutorial, we can access the osTicket system we previously installed and configured as an end user to create a new ticket by browsing to the following URL: http:/localhost/osTicket, then clicking on "Open New Ticket." Each ticket contains the customer information who is requesting the issue to be resolved, a drop-down menu with the category under which the issue falls, and a brief description of what the issue is to help the Help Desk professional better understand. 
</p>


<p>
<img src="https://github.com/mariamcpherson/os_lifecycle/assets/139581822/e0e1ec01-2d28-445d-8576-0879f7b82a51"/>
</p>

<p>
I created three different made up tickets for different Help Topics, as shown below. 
</p>

<p>
This imaginary customer, Ken, is requesting help with a Critical business issue, that according to the SLAs we set up in the previous section, will have to be dealt with on a 24/7 schedule, with a grace period of 1 hour. This is an important issue that affects business operations.
</p>


<p>
<img src="https://github.com/mariamcpherson/os_lifecycle/assets/139581822/286331d2-4157-4219-b9ee-a2494cfed843"/>
</p>


<p>
The same customer, Ken, is requesting help with an issue under the category of Personal Computer Issues, and he also included a brief description.
</p>


<p>
<img src="https://github.com/mariamcpherson/os_lifecycle/assets/139581822/60ad2f91-4284-4613-be9d-4d4723ab86af"/>
</p>

<p>
In this case, Ken, has a general question regarding hardware updates for his department.
</p>

<p>
<img src="https://github.com/mariamcpherson/os_lifecycle/assets/139581822/32fb4c18-fdac-43ef-8358-f182c5ac4a86"/>
</p>

<p>
Now, let's change roles. A customer has created a few tickets for our Help Desk team to work on, so we will be logging into the system as one of our admins. I logged in as jane.doe with the credentials that I created during osTicket installation and setup, but you can log in as any of the Agents created in the previous section. 
</p>

<p>
So, as Jane Doe, administrator, I see the three tickets submitted on my Dashboard. 
</p>

<p>
<img src="https://github.com/mariamcpherson/os_lifecycle/assets/139581822/5147fa10-13d5-4ff1-b6a9-74571cff86f4"/>
</p>

<p>
2. Ticket Assignment: Once the ticket is created, it needs to be assigned to an appropriate agent or support staff member. In osTicket, this can be done manually by a supervisor or team lead, or it can be automated based on predefined rules, agent availability, or workload distribution.
</p>

<p>
3. Ticket Response: After assignment, the agent or support staff member responds to the ticket. They may ask for additional information from the customer to better understand the issue or provide a preliminary solution.
</p>

<p>
4. Ticket Status Updates: During the ticket lifecycle, the ticket's status may change several times to reflect its current state. Common status labels include "Open," "In Progress," "Pending Customer Reply," "On Hold," and "Closed." These labels help in tracking the progress of the ticket and provide better visibility to both agents and customers.
</p>

<p>
5. Ticket Communication: There may be back-and-forth communication between the agent and the customer until the issue is fully resolved. osTicket keeps a record of all communications, which is helpful for tracking the ticket history and ensuring continuity in case of agent changes or follow-ups.
</p>

<p>
6. Ticket Resolution: Once the issue is resolved, the agent will mark the ticket as "Resolved" or a similar status. The resolution may involve providing a solution, offering instructions, or addressing the customer's concern appropriately.
</p>

<p>
7. Ticket Closure: After the ticket is resolved, it can be marked as "Closed." This indicates that the issue has been successfully addressed to the customer's satisfaction. The ticket is no longer considered active, but the information is still accessible for future reference and reporting purposes.
</p>

<p>
8. Ticket Reopening: In some cases, a customer may reopen a closed ticket if they encounter the same issue again or if they are not satisfied with the initial resolution. When this happens, the ticket is reactivated, and the support process resumes.
</p>

<p>
9. Ticket Escalation: For complex or critical issues that require higher-level attention, the ticket may be escalated to a supervisor, manager, or a specialized support team. Escalation ensures that challenging cases receive the necessary expertise and resources for resolution.
</p>

<p>
10. Ticket Reporting and Analysis: Throughout the ticket lifecycle, osTicket gathers data and metrics about support ticket activities. These reports help support teams analyze their performance, identify trends, and make data-driven decisions to improve customer service.
</p>


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
