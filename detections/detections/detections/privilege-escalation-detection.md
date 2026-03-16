# Privilege Escalation Detection

## Overview

Privilege escalation occurs when an attacker gains higher-level permissions within a system or environment.

Monitoring changes to privileged roles can help detect unauthorized access.

## Detection Logic

Alert when:

• A user account is assigned a privileged role
• Role assignments occur outside normal change windows
• New administrative accounts are created

## Investigation Steps

1. Identify the account receiving privileges
2. Verify change request authorization
3. Review role assignment logs
4. Determine whether the action is legitimate

## Response Actions

• Remove unauthorized privileges
• Reset account credentials
• Investigate related activity

## MITRE ATT&CK Mapping

Privilege Escalation – TA0004
