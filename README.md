The Open Source Audit — Git
Project Overview

This project is a capstone audit of the open-source software Git (Version Control System) conducted as part of the Open Source Software course at VIT Bhopal University.

It explores:

The origin and philosophy of Git
The GPL v2 license and open-source freedoms
Ethical and ecosystem perspectives of open source
Practical Linux-level interaction with Git
Hands-on Bash scripting automation tasks
Student Details
Name: Pragati Kumari
Registration Number: 24BCE10433
Slot: D11
Course: Open Source Software
 Software Chosen
Git — Version Control System
License: GNU General Public License v2 (GPL v2)
 Key Concepts Covered
Distributed version control
Open-source philosophy & ethics
GPL vs MIT licensing
Linux file system & package management
Bash scripting fundamentals
 Project Structure
├── Script1_System_Report.sh
├── Script2_Package_Inspector.sh
├── Script3_Disk_Auditor.sh
├── Script4_Log_Analyzer.sh
├── Script5_Manifesto_Generator.sh
└── README.md
 Bash Scripts Description
 Script 1 — System Identity Report
Displays system details like:
Kernel version
Username
OS distribution
Uptime
Uses:
Command substitution $()
/etc/os-release parsing
 Script 2 — FOSS Package Inspector
Checks if Git is installed using dpkg
Extracts:
Version
License
Uses:
if-then-else
case statements
Script 3 — Disk and Permission Auditor
Audits important directories:
/etc, /var, /home, /tmp, etc.
Displays:
Permissions
Owner & group
Disk usage
Also checks:
~/.gitconfig
 Script 4 — Log File Analyzer
Reads log file line-by-line
Counts occurrences of a keyword
Accepts:
$1 → file path
$2 → keyword (default = error)
Outputs:
Total matches
Last 5 matching lines
 Script 5 — Open Source Manifesto Generator
Interactive script using read
Generates a personalized open-source manifesto
Demonstrates:
User input handling
String formatting
 How to Run
Give execution permission:
chmod +x script_name.sh
Run the script:
./script_name.sh
Example (Script 4):
./log_analyzer.sh /var/log/syslog error
 Why This Project Matters

Git is not just a tool—it represents the core philosophy of open collaboration.
This project highlights how open-source software:

Enables innovation
Promotes transparency
Empowers developers worldwide
 References
Git Official Documentation
GNU GPL v2 License
Linux man pages
Course material (OSS - VIT Bhopal)
 Final Thought

“Open source is not just about code — it’s about community, freedom, and shared progress.”
