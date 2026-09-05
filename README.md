# ServiceNow IT Service Management Lab

## Project Overview

This project is a hands-on IT Service Management (ITSM) lab built in a ServiceNow Personal Developer Instance (PDI). The goal was to simulate a real-world IT help desk environment and gain practical experience managing incidents, automating ticket assignments, configuring service-level agreements (SLAs), and analyzing service desk data.

The environment includes realistic IT support incidents across network, hardware, and software categories with varying levels of impact, urgency, and priority. I configured assignment groups, automated routing, a custom SLA for critical incidents, and an analytics dashboard to monitor service desk activity.
## Skills & Technologies

- **Platform:** ServiceNow Personal Developer Instance (PDI)
- **IT Service Management:** Incident Management, ticket lifecycle, assignment groups, and escalation
- **Automation:** Assignment Rules for automated incident routing
- **SLA Management:** SLA definitions, start/pause/stop conditions, and business-hour schedules
- **Analytics:** Platform Analytics dashboards, reports, and incident metrics
- **Incident Prioritization:** Impact, urgency, and priority configuration
- **Technical Documentation:** Work notes, troubleshooting documentation, and resolution records
## What I Built

### Incident Management
- Created and managed realistic IT support incidents involving network, hardware, and software issues.
- Practiced the complete incident lifecycle from ticket creation and troubleshooting through resolution.
- Used impact and urgency to determine incident priority.
- Documented troubleshooting steps and technician activity using work notes.

### Automated Incident Routing
- Created IT Help Desk and Network Support assignment groups.
- Configured an assignment rule that automatically routes incidents categorized as **Network** to the **Network Support** group.
- Tested the rule with network incidents to verify that tickets were routed correctly.

### SLA Management
- Created a custom **Critical Incident Resolution - 1 Hour** SLA for Priority 1 incidents.
- Configured the SLA to:
  - Start when an incident reaches **Priority 1 - Critical**
  - Pause when the incident is placed **On Hold**
  - Stop when the incident is **Resolved**
- Applied an **8-5 weekday business schedule excluding holidays**.
- Tested the SLA on a new critical incident and verified that it successfully attached to the ticket.

### Service Desk Analytics
- Built an **IT Service Management Dashboard** using ServiceNow Platform Analytics.
- Created visualizations to monitor:
  - Incidents by Category
  - Incidents by Priority
  - Incidents by Assignment Group
  - Total Incident Volume
- Filtered dashboard data to focus specifically on incidents created for the lab environment.
## Project Screenshots

The following screenshots demonstrate the key components configured and tested within the ServiceNow lab environment.

### IT Service Management Dashboard
Provides a centralized view of incident volume by category, priority, assignment group, and total incidents.

<img width="954" height="484" alt="Screenshot 2026-09-04 234626" src="https://github.com/user-attachments/assets/49ea1510-48f4-4ff8-bd53-8470daa6b0bd" />

### Critical Incident SLA Validation
A Priority 1 critical incident was used to test SLA behavior. The SLA timeline confirms that the custom **Critical Incident Resolution - 1 Hour** SLA successfully attached to the incident.

<img width="958" height="356" alt="Screenshot 2026-09-04 234755" src="https://github.com/user-attachments/assets/2e28d5ad-aa5d-44a5-975d-9c7af5cfe949" />

### Incident Management & Troubleshooting
Managed an IT support incident through the incident lifecycle while documenting troubleshooting steps and technician activity using ServiceNow work notes.

<img width="959" height="400" alt="Screenshot 2026-09-04 234921" src="https://github.com/user-attachments/assets/e3ced6ab-b765-41fe-bbba-f8924f822433" />

### Automated Incident Routing
Configured an assignment rule to automatically route incidents categorized as **Network** to the **Network Support** assignment group, reducing the need for manual ticket assignment.

<img width="959" height="383" alt="Screenshot 2026-09-04 235053" src="https://github.com/user-attachments/assets/6361c72e-8fc5-46ab-9c8d-fc5d2081da98" />

### Custom Critical Incident SLA
Configured a custom **1-hour resolution SLA** for Priority 1 critical incidents. The SLA uses a business-hours schedule and includes conditions to start when an incident becomes critical, pause when placed On Hold, and stop when the incident is Resolved.

<img width="959" height="454" alt="Screenshot 2026-09-04 235208" src="https://github.com/user-attachments/assets/2446d76d-8526-4d77-b5f2-3612f7add8ee" />

## What I Learned

Through this project, I gained hands-on experience with the core components of IT Service Management in ServiceNow. I learned how incidents move through the support lifecycle and how impact and urgency influence ticket priority.

I also gained experience configuring assignment rules to automate ticket routing, creating SLA conditions to track resolution expectations, and using Platform Analytics to turn incident data into useful service desk metrics.

Most importantly, this project helped me understand how different ServiceNow features work together to support an IT service desk rather than viewing incident management, automation, SLAs, and reporting as separate functions.

