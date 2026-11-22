# Endpoint Security Monitoring and Threat Detection Using Wazuh SIEM

## Project Overview
Designed and implemented a cybersecurity home lab using Wazuh SIEM to monitor endpoint activities, detect suspicious events, and perform Security Configuration Assessment (SCA).

## Lab Architecture
- Wazuh Manager – Ubuntu Linux
- Endpoint – Windows 11 with Wazuh Agent
- Kali Linux – Security testing environment
- Virtualization – Oracle VirtualBox
- Network – NAT Network

## Technologies Used
- Wazuh SIEM
- Ubuntu Linux
- Windows 11
- Kali Linux
- VirtualBox
- XML Custom Detection Rules
- Windows Event Monitoring
- CIS Security Configuration Assessment

## Project Implementation
1. Installed and configured Wazuh Manager.
2. Connected Windows 11 endpoint using Wazuh Agent.
3. Verified endpoint communication and event collection.
4. Configured custom detection rules for simulated attack scenarios.
5. Monitored Windows authentication failures and service configuration changes.
6. Performed CIS Windows 11 Security Configuration Assessment.
7. Investigated alerts through the Wazuh dashboard.

## Detection Results

| Security Event | Detection |
| Failed Windows login | Rule ID 60122 |
| Windows service configuration change | Rule ID 61104 |
| Windows application event | Rule ID 60608 |
| Custom training scenarios | 17 of 18 expected rule IDs detected |

## Security Configuration Assessment
Performed CIS Microsoft Windows 11 Enterprise Benchmark assessment.

- Initial assessment score: 26%
- Passed checks: 123
- Failed checks: 349
- Invalid checks: 10
- Some checks showed Not applicable and require further investigation.

## Learning Outcomes
- SIEM deployment and configuration
- Endpoint monitoring
- Security event analysis
- Custom detection rule implementation
- Windows authentication monitoring
- Security posture assessment
- Incident investigation fundamentals

## Project Limitations
- Custom Windows training scenarios through the Windows agent remain pending.
- One expected custom rule (100211) was not detected.
- Some SCA findings require additional investigation.

## Disclaimer
This project was performed in an isolated virtual lab using simulated security events for educational purposes. No unauthorized systems were accessed.

## Author
Cybersecurity Lab Project | Wazuh SIEM
