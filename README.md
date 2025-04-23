# Windows Event Log Analysis Script

## Project Overview

This project provides a set of PowerShell scripts designed to collect and analyze Windows Event Logs for system monitoring, security auditing, and troubleshooting purposes. It focuses on critical logs such as System, Application, and Security, filtering relevant event IDs related to crashes, updates, logon attempts, and potential security issues.

The analysis includes:
- Detection of shutdowns and restarts
- Monitoring of failed login attempts
- Identification of application crashes
- Event log formatting and exporting to Excel or CSV
- Simulated testing of forwarded events (single-system environment)

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
