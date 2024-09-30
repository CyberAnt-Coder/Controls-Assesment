# Controls-Assesment

## Description
 In this lab, I evaluated and implemented various controls within a fictional organization. The lab is focused on giving hands-on experience with categorizing each control, determining if it needs to be implemented, as well as the priority level the control should be given.
<br />

# Walk-through:

## Current Assets

Assets managed by the IT Department include:

- **On-premises equipment for in-office business needs**
- **Employee equipment**: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- **Management of systems, software, and services**: accounting, telecommunication, database, security, ecommerce, and inventory management
- **Internet access**
- **Internal network**
- **Vendor access management**
- **Data center hosting services**
- **Data retention and storage**
- **Badge readers**
- **Legacy system maintenance**: end-of-life systems that require human monitoring

## Administrative Controls

| Control Name             | Control Type and Explanation                                                                                                                                                   | Needs to be Implemented (X) | Priority |
|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------|----------|
| Least Privilege          | Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs                                      | X                            | High     |
| Disaster Recovery Plans  | Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components | X                            | High     |
| Password Policies        | Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques               | X                            | High     |
| Access Control Policies  | Preventative; increase confidentiality and integrity of data                                                                                                                    | X                            | High     |
| Account Management Policies | Preventative; reduce attack surface and limit overall impact from disgruntled/former employees                                                                                  | X                            | High     |
| Separation of Duties     | Preventative; ensure no one has so much access that they can abuse the system for personal gain                                                                                | X                            | High     |

## Technical Controls

| Control Name                  | Control Type and Explanation                                                                                                           | Needs to be Implemented (X) | Priority |
|-------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|------------------------------|----------|
| Firewall                      | Preventative; firewalls are already in place to filter unwanted/malicious traffic from entering internal network                       | NA                           | NA       |
| Intrusion Detection System (IDS) | Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly                                           | X                            | High     |
| Encryption                    | Deterrent; makes confidential information/data more secure (e.g., website payment transactions)                                        | X                            | High     |
| Backups                       | Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan                               | X                            | High     |
| Password Management System    | Corrective; password recovery, reset, lock out notifications                                                                           | X                            | Medium   |
| Antivirus (AV) Software       | Corrective; detect and quarantine known threats                                                                                         | X                            | High     |
| Manual Monitoring, Maintenance, and Intervention | Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities | X                            | High     |

## Physical Controls

| Control Name                        | Control Type and Explanation                                                                                                             | Needs to be Implemented (X) | Priority |
|-------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|------------------------------|----------|
| Time-controlled Safe                | Deterrent; reduce attack surface/impact of physical threats                                                                              | X                            | Medium   |
| Adequate Lighting                   | Deterrent; limit “hiding” places to deter threats                                                                                        | X                            | Low      |
| Closed-circuit Television (CCTV) Surveillance | Preventative/detective; can reduce risk of certain events; can be used after event for investigation                                    | X                            | High     |
| Locking Cabinets (for Network Gear) | Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear | X                            | High     |
| Signage Indicating Alarm Service Provider | Deterrent; makes the likelihood of a successful attack seem low                                                                         | X                            | Medium   |
| Locks                              | Preventative; physical and digital assets are more secure                                                                               | X                            | High     |
| Fire Detection and Prevention       | Detective/Preventative; detect fire in the physical location to prevent damage to inventory, servers, etc.                                | X                            | Low      |


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
