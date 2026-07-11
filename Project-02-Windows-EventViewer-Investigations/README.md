# Project 02-Windows Event Viewer Security Log Investigation 
## Objective
The objective of this project was to investigate Windows Security logs using Event Viewer.The investigation focused on identifying successful logon events, understanding Windows authentication logs, and documenting findings from a SOC analyst perspective.
---
## Tools Used 
- Windows Event Viewer
- Windows 11
- Windows Security Logs
---
## Investigation Steps
1. Opened Event Viewer.
2. Navigated to **Windows Logs > Security**.
3. Applied a filter for **Event ID 4624**.
4. Reviewed successful authentication events.
5. Examined Event Properties.
6. Documented authentication details and observations.
---
## Evidence Collected
### Figure 1 - Successful Logon Event (Event ID 4624)
The screenshot below shows Windows Event Viewer displaying Security Event ID 4624 (Successful Logon). The security log was filtered to display successful logon events for investigation.
![Successful Logon Event] (Screenshots/event_4624_successful_logon.png)
The investigation identified the following observations:
- Event ID 4624 represents a successful user logon.
- Authentication completed successfully.
- The event was recorded in the Windows Security log.
- Logon Type 5 was observed.
- Audit Success confirmed successful authentication.
- No failed authentication attempts were identified during this review.
---
## Findings 
- Successfully filtered Windows Security logs using Event Viewer.
- Verified Event ID 4624 records successfully authentication activity.
- Reviewed authentication details including:
  - Security ID
  - Account Name
  - Computer Name
  - Logon Type
  - Audit Success
- No suspicious authentication behaviour was identified.
---
## Conclusion 
This investigation demonstrated how Windows Security Event ID 4624 can be used to verify successful authentication events. The reviewed log entries appeared consistent with normal Windows activity, and no indicators of malicious or unauthorized logon attempts were identified.
---
## Skills Demonstrated 
- Windows Event Viewer
- Wondows Security Log Analysis
- Authentication Analysis
- Windows Forensics
- SOC Investigation
- Log Analysis 
