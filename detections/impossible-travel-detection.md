# Impossible Travel Authentication Detection

## Overview

Impossible travel occurs when a user account authenticates from two geographically distant locations within a time frame that is physically impossible.

This behavior may indicate credential compromise.

## Detection Logic

Alert when:

• A user logs in from two different countries
• The login events occur within a short time window
• The distance between locations cannot reasonably be traveled

## Investigation Steps

1. Identify the user account
2. Verify login locations and IP addresses
3. Check for VPN usage
4. Review recent account activity
5. Confirm whether the activity is legitimate

## Response Actions

• Force password reset
• Revoke active sessions
• Investigate related activity
• Monitor the account for further anomalies

## MITRE ATT&CK Mapping

Valid Accounts – T1078
