<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket Help Desk Ticketing System Scenarios

### Overview
This project simulates a real-world enterprise help desk environment using osTicket. The lab focuses on ticket management, troubleshooting workflows, SLA administration, escalation procedures, and end-user support operations commonly used in enterprise IT environments.

The environment was configured to simulate realistic help desk operations where users submit tickets for password resets, printer failures, shared drive outages, and business-critical incidents.

### Business Impact
This project demonstrates how enterprise IT teams use help desk ticketing systems to manage support requests, prioritize critical issues, document troubleshooting steps, and reduce downtime for employees and business operations.

### Technologies Used
- osTicket
- Microsoft IIS
- MySQL
- PHP
- Windows Server 2022
- Windows 10

### Key Help Desk Skills Demonstrated
- Ticket Lifecycle Management
- SLA Administration
- Password Reset Support
- Printer & Network Troubleshooting
- Ticket Documentation
- End-User Support


### Environment Setup
- Windows Server VM
- Windows Client VM
- IIS Web Server
- MySQL Database Server
- PHP Configuration
- osTicket Deployment

### Departments
- Support
- SysAdmins
- Network Operations

### Teams
- Online Banking

### Agents
| Agent | Department | Access |
|---|---|---|
| John Doe | SysAdmins | Full Access |
| Keanu Wilder | Helpdesk | Helpdesk Access |
| Olivia Martinez | Network Operations | Limited Access |

### Users
| User | Department |
|---|---|
| Sarah Johnson | HR |
| Ethan Davis | Sales |
| Daniel Brooks | Finance |
| Karen Wallace | General User |
| Ken | General User |

### SLA Policies
| SLA | Grace Period | Schedule |
|---|---|---|
| Sev-A | 1 Hour | 24/7 |
| Sev-B | 4 Hours | 24/7 |
| Sev-C | 8 Hours | Business Hours |

# Project Configuration Steps

### Step 1 - Install IIS, PHP, and MySQL
Installed and configured the web server, PHP environment, and MySQL database required for osTicket deployment.

### Step 2 - Deploy osTicket
Configured osTicket and verified successful deployment through the Support Center and Admin Panel.

### Step 3 - Configure Roles, Departments, and Teams
Configured departments, teams, and role-based permissions to simulate enterprise help desk hierarchy and escalation workflows.

### Step 4 - Configure SLA Policies and Help Topics
Configured SLA response policies and realistic help topics for ticket categorization and escalation procedures.

---

# Help Desk Scenarios

## Scenario 1 - HR Payroll Account Lockout
### Assigned Agent
Keanu Wilder — Helpdesk Department
### User
Sarah Johnson — HR Department
### Help Topic
Report a Problem / Password Reset
### Priority
High
### SLA
Sev-A — 1 Hour Response / 24x7 Coverage

### Problem
Sarah Johnson was unable to access her workstation and payroll system before payroll processing deadlines.

### Troubleshooting
- Verified user identity
- Confirmed account lockout
- Reset password
- Unlocked account
- Tested successful login
- Added internal documentation notes

### Root Cause
Multiple failed login attempts caused the user account to become locked.

## Screenshots

## Ticket Submission

<img width="730" height="829" alt="image" src="https://github.com/user-attachments/assets/ec603b02-3336-45ac-9354-494d843dc462" />

## Ticket Queue

<img width="959" height="400" alt="image" src="https://github.com/user-attachments/assets/6a43c239-2422-4bd9-9aaa-8bf2fdd1933a" />

## Ticket Assignment

<img width="957" height="501" alt="image" src="https://github.com/user-attachments/assets/6a87befe-e8ea-4524-ae97-1799e7a77a98" />

## Account Lockout in AD

<img width="407" height="536" alt="image" src="https://github.com/user-attachments/assets/89053c6e-03cb-4818-95c3-911b66c3bf40" />

## Internal Troubleshooting Documentation

<img width="861" height="917" alt="image" src="https://github.com/user-attachments/assets/26f0fb17-45c5-42d4-8013-dad2980bb43a" />

## Resolved Ticket

<img width="853" height="146" alt="image" src="https://github.com/user-attachments/assets/87cc96e9-8d88-4271-b019-3ff31487dc8d" />

## Resolution
Password was reset and account access was restored successfully.

---
## Scenario 2 - Sales Printer Failure Before Client Meeting
### Assigned Agent
Keanu Wilder — Helpdesk Department
### Escalated To
John Doe SysAdmin Department
### User
Ethan Davis — Sales Department
### Help Topic
Report a Problem / Printer Issues
### Priority
Medium
### SLA
Sev-B — 4 Hour Response / 24x7 Coverage

### Problem
Sales staff were unable to print contracts before an important client meeting.

### Troubleshooting
- Verified printer connectivity
- Checked printer online status
- Restarted Print Spooler service
- Cleared stuck print queue
- Tested successful printing

### Root Cause
A stalled Print Spooler service prevented documents from printing successfully.

## Screenshots
## Ticket submission showing printer issue and business impact

<img width="841" height="899" alt="image" src="https://github.com/user-attachments/assets/c6e6e6a7-f5db-4430-a95d-5aab92ef81b0" />

## Ticket escalation from Keanu Wilder to John Doe

<img width="870" height="957" alt="image" src="https://github.com/user-attachments/assets/492c252c-792f-4def-b9c9-5a8037bdc0d9" />

## Print Spooler troubleshooting after users reported stuck print jobs. The service was stopped, preventing printer communication and document processing.

<img width="406" height="465" alt="image" src="https://github.com/user-attachments/assets/9599351b-8346-444f-a39c-8eab21bf1ab0" />

## Internal troubleshooting notes documenting escalation and remediation steps

<img width="857" height="399" alt="image" src="https://github.com/user-attachments/assets/d652c7f1-bd91-4a32-a305-2007b444c361" />

## Resolved Ticket

<img width="909" height="152" alt="image" src="https://github.com/user-attachments/assets/03b3cdeb-3bfe-4145-9ae2-1c384de9ec75" />

### Resolution
Printer functionality was restored successfully.

---
## Scenario 3 - Finance Shared Drive Outage
### Assigned Agent
Olivia Martinez — Network Operations
### User
Daniel Brooks — Finance Department
### Help Topic
Report a Problem / Shared Drive Access
### Priority
Critical

### Problem
Finance employees lost access to a shared network drive containing department financial reports.

### Troubleshooting
- Verified issue across multiple users
- Tested network connectivity
- Confirmed shared drive outage
- Escalated ticket to Network Operations
- Coordinated with Olivia Martinez for investigation

### Root Cause
Network connectivity disruption prevented users from accessing the finance shared drive.

## Screenshots
## Critical shared drive outage ticket showing business impact

<img width="758" height="713" alt="image" src="https://github.com/user-attachments/assets/694c5f87-4c6f-4886-9c22-81d2a0b2b12d" />

## Ticket Assign to Olivia Martinez in Network Operations

<img width="859" height="686" alt="image" src="https://github.com/user-attachments/assets/5d405d65-18b1-434f-91dc-37882cd70824" />

## Network troubleshooting showing failed shared drive access or connectivity testing

<img width="353" height="363" alt="image" src="https://github.com/user-attachments/assets/aee15d6a-edf0-4007-b1cd-63c5e0832196" />
<img width="1119" height="764" alt="image" src="https://github.com/user-attachments/assets/16f0e009-7f64-440d-9b3d-248528594ecb" />

## Internal troubleshooting notes documenting escalation and network investigation

<img width="361" height="447" alt="image" src="https://github.com/user-attachments/assets/2cf170f9-a71a-40ed-bb71-3e1ee77244a7" />
<img width="852" height="466" alt="image" src="https://github.com/ser-attachments/assets/609de83b-7906-415b-bd43-52dd562acdad" />

## Restored shared drive access or successful connectivity verification

<img width="1125" height="766" alt="image" src="https://github.com/user-attachments/assets/42d4f300-ccbd-4c76-b0ef-c93ee929e985" />

### Resolution
Network Operations restored connectivity and shared drive access successfully for Daniel Brooks Finance Department.

---
## Scenario 4 - Business Critical SLA Escalation
### Assigned Agent
Keanu Wilder — Helpdesk Department
### Escalated To
John Doe SysAdmin Department
### User
Karen — General User
### Help Topic
Report a Problem / Business Critical Outage
### Priority
Critical

### Problem
A business-critical outage exceeded SLA response windows and required escalation to senior administrators.

### Troubleshooting
- Reviewed SLA timers
- Escalated ticket to SysAdmins
- Assigned ticket to Keanu Wilder
- Monitored response window
- Updated internal documentation

### Root Cause
Critical outage required escalation beyond frontline support capabilities.

## Screenshots
## Critical VPN outage ticket showing SLA priority and business impact

<img width="860" height="806" alt="image" src="https://github.com/user-attachments/assets/8ee5055b-3e7f-4d52-8695-a318479b2cbf" />

## Ticket escalation from Keanu Wilder to John Doe in the SysAdmins department

<img width="860" height="806" alt="image" src="https://github.com/user-attachments/assets/4bf52f83-b204-488a-b518-1a859e07bc90" />

## VPN troubleshooting showing failed VPN connection or service investigation

<img width="404" height="466" alt="image" src="https://github.com/user-attachments/assets/bc3ddca1-aa9d-480a-8e14-444f9591c326" />

## Internal troubleshooting notes documenting SLA escalation and remediation steps

<img width="858" height="749" alt="image" src="https://github.com/user-attachments/assets/47e4f40b-bd79-48c2-829d-93b7ca15bebc" />

## Successful VPN reconnection or restored VPN service verification

<img width="802" height="587" alt="image" src="https://github.com/user-attachments/assets/b40415b4-b361-43c9-93e8-605e47f2b59e" />
<img width="848" height="161" alt="image" src="https://github.com/user-attachments/assets/a39c98c6-4c26-4a44-ba60-9c2774600a5e" />

### Resolution
Issue was escalated appropriately and resolved successfully.

---
## Lessons Learned
This project strengthened my understanding of enterprise help desk operations, ticket lifecycle management, SLA administration, escalation procedures, and troubleshooting methodology.

Through realistic support scenarios, I gained hands-on experience documenting technical issues, prioritizing incidents based on business impact, troubleshooting authentication and connectivity problems, and coordinating escalations between support teams.

The project also improved my understanding of role-based access control, departmental ticket routing, and enterprise support workflows commonly used in IT support environments.

## Future Improvements
- Configure email-to-ticket integration
- Implement automated escalation workflows
- Add knowledge base documentation
- Configure Active Directory integration
- Implement advanced reporting dashboards
- Configure ticket auto-assignment rules
- Integrate monitoring and alerting systems
