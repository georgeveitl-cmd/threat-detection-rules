# Suspicious PowerShell Execution

## Overview

Attackers frequently use PowerShell to execute malicious commands or download payloads.

Monitoring PowerShell execution patterns can help detect malicious activity.

## Detection Indicators

• Encoded PowerShell commands
• Network downloads initiated by PowerShell
• Execution from unusual directories
• PowerShell spawning other processes

## Investigation Steps

1. Identify the system executing the command
2. Review the command line arguments
3. Determine whether the execution is legitimate
4. Check for additional suspicious processes
5. Review network connections initiated by the script

## Response Actions

• Isolate the affected system
• Terminate malicious processes
• Review endpoint telemetry
• Perform malware scanning

## MITRE ATT&CK Mapping

Command and Scripting Interpreter – T1059
