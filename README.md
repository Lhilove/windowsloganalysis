# Windows Event Log Analysis Script

## Project Overview

This project provides a set of PowerShell scripts designed to collect and analyze Windows Event Logs for system monitoring, security auditing, and troubleshooting purposes. It focuses on critical logs such as System, Application, and Security, filtering relevant event IDs related to crashes, updates, logon attempts, and potential security issues.

The analysis includes:
- Detection of shutdowns and restarts
- Monitoring of failed login attempts
- Identification of application crashes
- Event log formatting and exporting to Excel or CSV
- Simulated testing of forwarded events (single-system environment)

  ## Tools Used

- **PowerShell**: The primary scripting language used to query and filter Windows event logs.
- **Event Viewer**: For manual validation and exploration of log entries.
- **ImportExcel PowerShell Module**: For exporting event log data to Excel format.
- **Windows Event Log API (via `Get-WinEvent`, `Get-EventLog`)**: For structured access to system, security, and application logs.

## SOC Use Cases and Relevance

This script suite is highly relevant for Security Operations Center (SOC) teams. Use cases include:

- **Security Monitoring**: Detects failed logon attempts (Event IDs 4625), successful logons (4624), and suspicious logon behavior.
- **Incident Response**: Helps trace application crashes (Event ID 1000), and abnormal shutdowns (6008), useful during post-incident analysis.
- **System Integrity Checks**: Monitors update/install events (Event IDs like 11707, 1033) and configuration changes that could indicate unauthorized changes.
- **Threat Hunting**: Provides an initial layer of data for hunting persistence mechanisms or lateral movement attempts.
- **Compliance Auditing**: Assists in validating system event data for regulatory requirements like HIPAA, GDPR, and PCI-DSS.

## Setup Instructions

1. Clone the Repository
   ```bash
   git clone https://github.com/yourusername/windows-event-log-analysis.git
   cd windows-event-log-analysis
2. Ensure PowerShell Script Execution Is Enabled Open PowerShell as Administrator and run:
## Usage Instructions
# Input files
analyze_system.ps1

analyze_application.ps1

analyze_security.ps1

analyze_setup.ps1

# Output Files
Systemlog.xlxs

Applicationlog.xlxs

Securitylog.xlxs

# Documentation
Windows log analysis.pdf

## Author
Name: Adewole Love Oluwapelumi

Email: pelumiade92@gmail.com

GitHub: console-lhilove
