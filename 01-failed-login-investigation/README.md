Investigation 01 — Failed Login Detection
📌 Overview

This investigation demonstrates how Windows security logs can be used to identify and investigate failed authentication attempts.

The activity was generated intentionally within an isolated cybersecurity home laboratory.

🎯 Objective

Identify failed login attempts and determine:

Which account was targeted
When the attempts occurred
The source of the attempts
The number of failures
Whether the activity represents suspicious behaviour
🖥️ Environment

Operating System: Windows 11

Host: WIN-VICTIM

Log Source: Windows Security Event Log

Event ID: 4625

🔎 Investigation Process
Opened Windows Event Viewer.
Navigated to:
Windows Logs → Security
Filtered for Event ID:
4625
Reviewed the authentication events.
Examined the account name.
Reviewed the timestamp.
Reviewed the source information.
Documented the findings.
📊 Findings

Multiple failed authentication attempts were observed against the laboratory Windows system.

The events were generated intentionally as part of the cybersecurity training exercise.

🧠 What I Learned

This investigation demonstrated:

How Windows records authentication failures
How Event ID 4625 can be used during investigations
How to identify relevant fields within security events
How to document a security investigation
How authentication failures can be used as an indicator for further investigation
🚨 Security Considerations

Repeated authentication failures may indicate:

Incorrect user credentials
Password guessing
Brute-force activity
Misconfigured applications
Automated authentication attempts

The event must be investigated in context before determining whether malicious activity occurred.

📝 Incident Report

Severity: Low

Status: Closed

Environment: Isolated laboratory

Impact: No real-world systems affected

📸 Evidence

Screenshots from the investigation are stored in the screenshots directory.

⚠️ Disclaimer

This investigation was performed entirely within an isolated laboratory environment for educational purposes.
