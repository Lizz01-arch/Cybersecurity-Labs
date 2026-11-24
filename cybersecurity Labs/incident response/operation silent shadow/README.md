# Operation Silent Shadow: MITRE ATT&CK Incident Analysis

  Author: Liz Mukami
  Category: Incident Response

## Overview

A lab exercise built around a fictional espionage attack on a government ministry. I mapped each phase of the attack to MITRE ATT&CK techniques, identified the most likely threat actor, and recommended mitigations for every phase.

This was a course exercise on a fictional scenario. No real organizations or data are involved.

## What the report covers

| Section | Focus |
|---|---|
| Step 1 | Initial Access: spearphishing attachments and user execution |
| Step 2 | Persistence and Privilege Escalation: Windows service and credential dumping |
| Step 3 | Defense Evasion and Credential Access: PowerShell, valid accounts, lateral movement |
| Step 4 | Exfiltration and Impact: exfiltration over C2 and data encryption |
| Step 5 | Threat Actor Attribution: Lazarus Group (G0032), moderate confidence |
| Step 6 | Mitigation: controls for each phase, tied to ATT&CK mitigation IDs |
| Conclusion | Summary of findings |

## Key techniques identified

`T1566.001` `T1204.002` `T1543.003` `T1003.001` `T1078` `T1059.001` `T1027` `T1021.002` `T1041` `T1071` `T1486`

## Skills demonstrated

- Mapping attacker behavior to MITRE ATT&CK techniques and sub-techniques
- Threat actor research and attribution, including stating confidence and ruling out alternatives
- Recommending layered defensive controls aligned to specific TTPs
- Clear technical writing for a security audience

## Files

- [`Operation_Silent_Shadow_Report.pdf`](Operation_Silent_Shadow_Report.pdf): the full report

## Note

Attribution based only on TTP overlap is not conclusive, since many groups share techniques. The conclusion reflects the scenario details provided and the ATT&CK group pages at the time of writing.

[Back to all labs](../../README.md)
