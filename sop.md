**Version:** 1.1.3  

Thank you for visiting the SOP (Standard Operating Procedure) page. On this page, you can read in detail about the procedures that must be implemented by the Ticket Team at World Host Group Bali.

## 1. Individual Ticket Responsibility

### 1.1. Purpose

To ensure efficient and structured handling of customer complaints through a ticketing system. 

### 1.2. Scope

Covers all complaints received through the ticketing system, including both technical and non-technical issues. 

### 1.3. Ticket Handling

- Each Support Team member is required to take initiative in managing available tickets in the portal and must be ready to accept ticket assignments from the Supervisor and Team Leader. 
- Prioritize the oldest tickets in the assigned list. 
- Every Support Team member who takes and accepts a customer ticket must verify the customer’s account to validate the service. 
- Before responding to a ticket, the Support Team should first understand the problem reported by the customer. 
- Ensure that the issue reported is clearly confirmed with the customer. 
- If any changes or settings in the customer’s service are required, obtain the customer’s permission beforehand. 
- The Support Team should inform the customer about the expected escalation time if the ticket cannot be resolved quickly, and update the ticket’s progress if the issue remains unresolved within the mentioned escalation time. 
- If the issue is not resolved by the end of the working hours, the Support Team must leave detailed notes on the ticket to facilitate escalation to the next shift. 
- The Support Team should explain the issue and the steps taken to resolve it in detail to the customer when responding to a completed ticket. 
- The Support Team may provide a Trustpilot review link to the customer through the ticket if the issue has been fully resolved. 

## 2. SOP for Escalation to Other Departments

### 2.1. Purpose

To ensure an efficient and structured process for escalating customer complaints to other department teams through the ticketing system. 

### 2.2. Scope

Covers all complaints received through the ticketing system and all related departments, including technical and non-technical issues. 

### 2.3. Procedure for Escalating Tickets to Other Departments

- The Support Team may escalate tickets assigned by the supervisor if the ticket's context shifts from technical to non-technical issues. 
- The Support Team can escalate to the appropriate group chat by opening a thread, providing the ticket ID, product details, context, brand, and other relevant information to facilitate other departments' checks. 
- Ensure the ticket is assigned to the correct department listed in the portal. 
- If only consultation with another department is needed without assigning the ticket, the Support Team must add a note and attach the thread link to the ticket note. 
- Inform the customer that their issue is being handled by the relevant team and update them when the issue is resolved. 
- The Support Team can follow up in the thread if there is no update within a certain timeframe.

## 3. SOP for Escalation to Level 2

### 3.1. Purpose

To ensure an efficient and structured process for escalating tickets from the Level 1 (L1) Support Team to the Level 2 (L2) Support Team regarding customer complaints.

### 3.2. Scope

Covers all relevant complaints received through the ticketing system, including both technical and non-technical issues. 

### 3.3. Procedure for Escalating Tickets to Level 2

- Each ticket has varying levels of complexity. Before escalating a ticket to Level 2, Level 1 agents must ensure they have fully understood the core issue faced by the customer.  
- Level 1 agents are encouraged to directly consult with Level 2 for discussions regarding ongoing issues.  
- If a Level 1 agent transfers the ticket's Department to "Escalated", they must leave Internal Notes with details to expedite the investigation process by Level 2.

## 4. SOP for Issue Checks on Server

### 4.1. Purpose

To establish a standard procedure for handling shared hosting to ensure optimal service and reduce downtime risk. 

### 4.2. Scope

This SOP applies to all Ticket Teams covering customer complaints and server checks. 

### 4.3. Procedure for Handling Shared Services

- **Shared Resources Complaints**
 - The Support Team should verify the service to ensure it matches the customer’s complaint. 
 - Check shared hosting services by logging into the server with provided LDAP credentials. 
- **Resources Issues**
 - If the issue is due to resource limitations, the Support Team should inform the customer in detail about their resource usage.
 - If the resource limit can be increased, such as the PHP limit, the Support Team can adjust it within the allowed limits. 
 - Inform the customer of any adjustments made to the settings in detail.
 - If further adjustments are not possible, suggest optimization or a service upgrade to a higher plan.
- **Configuration Issue**
 - The Support Team should not make any changes to the service without customer permission, including changes to passwords, files, emails, DNS, or other configurations.
 - Request permission via support ticket if a change is needed during an issue check. 
 - Revert settings to their original state and inform the customer about the resolution steps through the ticket. 
- **Backup/Restore Issues**
 - For backup issues, ensure the availability of backup data on the server. 
 - Do not perform a restore without detailed information from the customer. 
 - Confirm with the customer regarding the backup data to be restored, including backup dates and specific data requirements. 
 - Notify the customer once the restore process is complete through the ticket. 
- **Email Issues**
 - Verify the issue details, such as requesting error messages or bounce-back notifications. 
 - Verify mail server settings to ensure they are correct. 
 - If email testing is needed, do not access the customer’s email account without permission. 
 - Use a dummy email account for testing, and send test emails to a designated support email. 
 - Do not send test emails to personal addresses. 
 - Inform the customer in detail about the cause of the issue through the support ticket. 
- **Shared Server Feature Limitations**
 - Support cannot change configurations as root on a shared server, including requests to install applications or enable disabled features.
 - Shared hosting does not allow whitelisting ISP IPs, except conditionally for remote database access needs.

### 4.4. Procedure for Handling Reseller Services

- Follow similar procedures as for shared hosting services for the following issues:
 - Resource Issues 
 - Configuration Issues 
 - Backup/Restore Issues 
 - Email Issues
- The Support Team must understand the features and limitations of reseller packages and ensure they are configured correctly on the server.
- Grant CloudLinux features for the highest reseller package upon customer request through the ticket. 
- Assist with IP whitelisting on Imunify360 Firewall function if requested by the customer for server connections, such as for WHMCS. 

### 4.5. Procedure for Managed Services

- Follow similar procedures as for shared hosting services for the following issues:
 - Resource Issues 
 - Configuration Issues 
 - Backup/Restore Issues 
 - Email Issues 
- Managed services do not permit the installation of unsupported applications. 
- Assist with IP whitelisting on Imunify360 Firewall function if requested by the customer. 

### 4.6. Procedure for Unmanaged Services

- The Support Team must verify the service to ensure it aligns with the customer’s complaint. 
- If server login is required, the Support Team may request login information from the customer. 
- The Support Team is not permitted to configure unmanaged services, only to identify issues and provide troubleshooting steps to the customer. 
- Do not install any applications on the server; instead, provide installation instructions to the customer via the support ticket. 
- Avoid restarting the server unless the customer cannot access it; in such cases, escalate to the Infra team for further checks as per the SOP for Escalation to Other Departments. 

## 5. SOP for Billing and Cancellation Issue Handling 

### 5.1. Purpose

To establish procedures for efficient and timely verification and resolution of billing and cancellation-related issues.

### 5.2. Scope

Covers all complaints received through the ticket system related to billing, service activation, cancellations, and active periods. 

### 5.3. Billing and Cancellation Ticket Handling 

#### 5.3.1. Verification

The Support Team has limitations on what can be done and what to escalate to the Billing and Retention team, including:

- The Support Team is not allowed to respond to, handle, or work on tickets assigned to the Billing and Cancellation teams.
- If a Billing or Cancellation ticket is accidentally taken by the Support Team, they may reassign the ticket to the appropriate department.

#### 5.3.2. Issue Identification

- **System Errors**: The approach depends on the specific system error. If it's a global temporary issue (e.g., Upmind), escalate it directly to the Billing Team. However, if a specific client encounters an error while trying to make a payment, request the exact error message first. Once you have more details, pass the ticket to the Billing Team for further handling.
- **Human Errors**: If a customer inquires about pricing, do not engage in verification or clarification. Instead, immediately escalate the ticket to the Billing Team for further assistance.
- **Ticket Changes & Adjustment**: The Support Team is permitted to transfer tickets to the Billing department without responding to the customer. When transferring a ticket to the Billing department, ensure that it remains unassigned and its status is set to 'Open.' This policy also applies when the Support Team handles tickets related to the Cancellation, Domain, and Trust & Safety departments.

#### 5.3.3. Activation Issue

- For support staff handling customer complaints regarding service activation, verify the ordered service.
- **Shared Hosting and Reseller Services**
 - Check the error logs in the customer portal under "Manage" and debug the error. 
 - If the issue is caused by the system failing to activate automatically, proceed with manual activation. 
- **Domain Services**
 - Check the error logs in the customer portal under "Manage" and debug the error. 
 - If the error is due to incomplete information, inform the customer via ticket to complete the required data. 
 - If the error is due to a registrar issue, escalate it to the Domain Team as per the Escalation SOP.
- **Server/VPS Services**
 - Ensure that the server's hostname (FQDN) is present.
 - If not, confirm with the customer via ticket, then escalate the ticket to the System Administrator (Infrastructure) Team for deployment assistance
 - Provide an activation time estimate, and update the ticket once the activation is complete, including where the login credentials are stored. 

#### 5.3.4. Cancellation Issues

- Any inquiries related to subscription cancellation, please immediately move to the 'cancellation' queue.

#### 5.3.5. Active Period & Due Date Issues 

- Support handling requests regarding the active period or due date should review the customer's history in previous tickets or invoices. 
- If the customer requests a due date extension, please escalate to the billing team.

#### 5.3.6. Invoice Issues 

- Any inquiries or invoice issue including internal issue (Upmind), please immediately escalate to the Billing Team. For example: If a customer inquires about pricing, do not engage in verification or clarification. Instead, immediately escalate the ticket to the Billing Team for further assistance.

#### 5.3.7. Service Renewal or Reactivation Issues

- Any inquiry related to this, please immediately escalate to the Billing Team.

#### 5.3.8. Service Upgrade Issues

- Any inquiry related to this, please immediately escalate to the Billing Team.

#### 5.3.9. Refund Issue

- Any inquiry related to this, please immediately escalate to the Billing Team.
- If there is an urgent matter, such as an imminent renewal or a dispute, ensure the Billing and Retention Team is flagged accordingly.

## 6. Ticket Department and Status

The Support Team is responsible for handling tickets specifically assigned to them and should not intervene in tickets managed by other departments.   

### 6.1. Purpose

Covers that all tickets are well-organized, and the Support Team handles only their responsible to tickets that related with Support without interfering with those belonging to other departments.   

### 6.2. Scope

Handles adjustments and modifications for all tickets that don't belong to the Support Team queue.   

### 6.3. Responsibility of Other Tickets Departments

- The Technical Support Team is not authorized to handle or work on the tickets related to other departments, including **Billings**, **Cancellations**, **Domains**, **Advocacy**, **Sales**, **Migration**, and **Trust & Safety**.
- The Technical Support Team is solely responsible for handling tickets in the following departments:
 - **Level 1 Technical Support**:
  - General
  - Support
  - SSL
  - DNS Troubleshooting
  - Email Troubleshooting
  - Hosting Troubleshooting
  - M365 Support
  - OX MAIL
 - **Level 2 Technical Support**:
  - Escalated
  - VIP Customers
- The Technical Support Team members who identify a ticket that should be handled by another department are allowed to change the ticket department without the need to respond.
- If the Technical Support Team has previously communicated and worked on a ticket, and it subsequently needs to be changed to another department, they must include relevant information in the ticket's Internal Note and change the ticket status to **Open**.

## 7. Data Backup Restore SOP 

### 7.1. Purpose

To ensure efficient handling of data backup restore requests for Shared Hosting and Reseller packages via the ticket system.

### 7.2. Scope

Covers all data backup restore requests received by the Support Team through the ticket system.

### 7.3. Data Backup Restore Handling 

- Support verifies the customer's service through the client area and confirms backup availability on the server. 
- Support should confirm with the customer whether a full or partial data restore is desired. 
- If an error occurs during the restore, escalate the issue to the System Administrator (Infrastructure) Team as per the Escalation SOP. 
- After completion, inform the customer and recommend a post-restore check. 

## 8. SOP for Email Test Trials 

### 8.1. Purpose

To ensure that handling email issues on customer services does not interfere with the customer's email privacy and activity. 

### 8.2. Scope

Covers all requests for email issue checks received by the Support Team through the ticketing system.

### 8.3. Email Test Procedure 

- When the Technical Support Team receives a complaint from a client regarding email issues, whether they are unable to send or receive emails, they must perform a test to verify both sending and receiving functionality on the customer's service.  
- **Permission Requirement**: The Support Team must obtain permission from the customer if they need to perform a test of email send/receive activity using the customer's email account. 
- Once the customer has agreed and given permission, the Support Team may send an email to a provided address, such as Gmail, Hotmail, or Yahoo. 
- **Prohibited Actions**: Support staff are not allowed to perform test sends or receives to their own personal email accounts.
- If the customer prefers not to grant access to their email, the Support Team should request permission to create a temporary dummy test email on the customer's service. 
- After completing the test successfully, the Support Team should delete the dummy email. 
- Send the email test results to the customer by attaching a screenshot of the sent email to the ticket. 

## 9. SOP for Ticket Categorization 

### 9.1. Purpose

To classify the complexity level of tickets submitted by customers for organized handling and use as a KPI assessment parameter.

### 9.2. Scope

Applies to all complaints received through the ticket system, covering both technical and non-technical issues. 

### 9.3. Ticket Categorization Procedure 

- The Technical Support Team must proactively manage tickets available in the portal and be ready to accept ticket assignments from the Supervisor or Team Leader.
- Each ticket received has a different level of difficulty and carries a different weight in case-handling assessment. 
- Ticket levels are divided into three categories set by the Team Leader and Supervisor:
 - **Lower Case**: Basic level tickets.
 - **Medium Case**: Intermediate level tickets. 
 - **Hard Case**: Complex level tickets.
- The ticket categories are communicated to the Support Team by the Team Leader and Supervisor as a performance parameter. 
- Each category has a performance value that will be compiled and used for KPI assessment, with values determined by the Team Leader and Supervisor. 
- Summary assessments will be communicated to the Support Team in one-on-one meetings with the team leader and supervisor.

## 10. SOP for KPI Assessment 

### 10.1. Purpose 

To establish performance parameters for the ticketing team across all aspects to evaluate individual team members’ performance over a specific period.

### 10.2. Scope 

Includes all assessments of the ticket team’s individual performance in handling both technical and non-technical issues.

### 10.3 KPI Assessment Procedure 

- The Team Leader and Supervisor define the assessment aspects and parameters, including:
 - **Key Results Area**:
  1. Resolution Performance Index
  2. Response Efficiency Metric
  3. Effective Escalation
  4. Individual Productivity
  5. Customer Satisfaction
 - **Individual Performance**
  1. Personal Dynamic Index
  2. Performance Impact-Service
  3. Adaptibility
  4. Initiative
  5. SOP Compliance
- Assessments are based on the ticket team’s daily activities and pre-defined assessment data and parameters, as shared with the team. 
- Assessment aspects are objective and aligned with the data and parameters agreed upon by the Ticket Team, Supervisor, Team Leader, and Management.
- KPIs will be summarized monthly and reviewed semi-annually.
- The Team Leader will present the KPI results to the ticket team through one-on-one sessions. 