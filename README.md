<p align="center">
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
| Keanu Wilder | SysAdmins | Supreme Admin |
| John Doe | Support | View Only |
| Olivia Martinez | Network Operations | Limited Access |

### Users
| User | Department |
|---|---|
| Sarah Johnson | HR |
| Ethan Davis | Sales |
| Daniel Brooks | Finance |
| Karen | General User |
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
Keanu Wilder — SysAdmin Department
### User
Sarah Johnson — HR Department
### Help Topic
Report a Problem / Password Reset
### Priority
High

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

### 📸 Screenshots
1. Ticket submission showing the user issue and ticket priority
2. Ticket assigned to Keanu Wilder in the SysAdmin department
3. Internal notes documenting password reset troubleshooting steps
4. Closed/resolved ticket showing successful resolution

### Resolution
Password was reset and account access was restored successfully.

---
## Scenario 2 - Sales Printer Failure Before Client Meeting
### Assigned Agent
John Doe — Support Department
### Escalated To
Keanu Wilder SysAdmin Department
### User
Ethan Davis — Sales Department
### Help Topic
Report a Problem / Printer Issues
### Priority
Medium

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

### Screenshots
1. Ticket submission showing the user issue and ticket priority
2. Ticket assigned to Keanu Wilder in the Support department
3. Internal notes documenting password reset troubleshooting steps
4. Closed/resolved ticket showing successful resolution steps
5. Resolved ticket status

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

### 📸 Screenshots
1. Critical ticket showing shared drive outage
2. Ticket escalation to Network Operations
3. Ticket assignment to Olivia Martinez
4. Internal notes documenting escalation and troubleshooting
5. Resolved ticket showing restored access

### Resolution
Network Operations restored connectivity and shared drive access successfully.

---
## Scenario 4 - Business Critical SLA Escalation
### Assigned Agent
Keanu Wilder SysAdmin Department
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

### 📸 Screenshots
1. Critical ticket showing SLA warning
2. Ticket escalation to SysAdmins
3. Ticket assignment to Keanu Wilder
4. Internal notes documenting escalation workflow
5. Resolved ticket showing final resolution

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
