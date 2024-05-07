---
layout: default
---

# 9. Configuration Management Policy

Health Note manages and documents all changes to production systems and networks within JIRA, the project management and issue tracking system. 

## 9.1 Applicable Standards

### 9.1.1 Applicable Standards from the HITRUST Common Security Framework

* 06 - Configuration Management

### 9.1.2 Applicable Standards from the HIPAA Security Rule

* 164.310(a)(2)(iii) Access Control & Validation Procedures

## 9.2 Configuration Management Policies

1. No systems are deployed into Health Note environments without approval of the Health Note CTO or Head of Engineering.
2. All changes to production systems, network devices, and firewalls are approved by the Health Note CTO or Head of Engineering before they are implemented to assure they comply with business and security requirements.
3. All changes to production systems are tested before they are implemented in production.
4. Implementation of approved changes are only performed by authorized personnel.
5. An up-to-date inventory of systems is maintained using Google spreadsheets and architecture diagrams hosted on Google Apps. All systems are categorized as production and utility to differentiate based on criticality.
6. All frontend functionality (developer dashboards and portals) is separated from backend (database and app servers) systems by being deployed on separate servers or containers.
7. All committed code is reviewed using pull requests to assure software code quality and proactively detect potential security issues in development.
8. Health Note utilizes development and staging environments that mirror production to assure proper function.
9. Clocks are continuously synchronized to an authoritative source across all systems using NTP or a platform-specific equivalent. Modifying time data on systems is restricted.

## Revisions

| Revision Date | Revision Description        | Notes               |
| --------------| --------------------------- | ------------------- |
| 4/18/2019     | Initial                     | Initial             |
| 4/14/2020     | Reviewed                    | No changes          | 
| 3/29/2021     | Reviewed                    | No changes          |
| 2/24/2022     | Reviewed                    | No changes          |
| 4/10/2023     | Reviewed                    | No changes          |
| 5/02/2024     | Updated                     | General updates     |