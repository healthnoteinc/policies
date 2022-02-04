# 26.0 Patch Management Policy 

## 26.1 Purpose

Patch and vulnerability management is a security practice designed to proactively prevent the exploitation of IT vulnerabilities that exist in the wild and from within. Health Note is committed to ensuring a strong security posture and recognizes the need to prevent and manage IT vulnerabilities.  A compromised system threatens the integrity of the network and all computers connected to it.  
The purpose of this policy is to ensure that all Health Note systems and applications are proactively managed and patched with appropriate updates. 

## 26.2 Scope

- Systems and Infrastructure Assets
- Application and Dependencies

## 26.3 Patching Guidelines

- Routine Patching
- Routine Patching is scheduled every [30] days for managed systems

- Out of Band & Emergency Patching schedule will depend on severity of CVE rating:

| CVSS Score | Patch Window |
|------------|--------------|
| Critical   | < 2 days     |
| High       | < 7 days     |
| Medium     | < 14 days    |
| Low        | < 30 days    |

## 26.4 Installation and Validation

- Patch Application
Tasks will be done by engineering staff in accordance with our standard deployment process.

- Reboots
Security patches will likely require a reboot of the system and we will coordinate with our customers as outlined in the Customer Notification section of this document.

- Validation
Post-patch testing is performed in order to ensure there were no new issues introduced. 

## 26.5 Customer Notification

- Routine Patching
As it is routine, we do not notify of routine patches that are not intended to have significant impact.

- Out of Band & Emergency Patching
In the event of an emergency patch that will affect our customers, Health Note will provide notification via [email] at least [48] hours in advance.
