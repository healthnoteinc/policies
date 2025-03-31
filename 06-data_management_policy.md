---
layout: default
---

# 6. Data Management Policy

Health Note has procedures to create and maintain retrievable exact copies of electronic protected health information (ePHI) stored in conjunction with the Health Note Platform. The policy and procedures will assure that complete, accurate, retrievable, and tested backups are available for all systems used by Health Note.

Data backup is an important part of the day-to-day operations of Health Note. To protect the confidentiality, integrity, and availability of ePHI, both for Health Note and Health Note Customers, complete backups are done daily to assure that data remains available when needed and in case of a disaster.

Violation of this policy and its procedures by workforce members may result in corrective disciplinary action, up to and including termination of employment.

## 6.1 Applicable Standards

### 6.1.1 Applicable Standards from the HITRUST Common Security Framework

* 01.v - Information Access Restriction

### 6.1.2 Applicable Standards from the HIPAA Security Rule

* 164.308(a)(7)(ii)(A) - Data Backup Plan
* 164.310(d)(2)(iii) - Accountability
* 164.310(d)(2)(iv) - Data Backup and Storage

## 6.2 Backup Policy and Procedures

1. Automate daily snapshot backups of all systems that process, store, or transmit ePHI for HealthNote Customers.
2. The Health Note Dev Ops Team is designated to be in charge of backups.
3. Dev Ops Team members are trained and familiar with cloud tools for creating backups.
4. Ensure that all backups are properly encrypted at rest with a key that is owned by Health Note.
5. Test backups annually and document that files have been completely and accurately restored.

## 6.3 Cloud Backup Scope

Health Note uses a variety of cloud services and backup inventory is as follows:

* RDS Snapshots
* S3 Cross-Country Replication
* Elasticache Backups
* EC2 Images
* MongoDB Backups

## Revisions

| Revision Date | Revision Description        | Notes               |
| --------------| --------------------------- | ------------------- |
| 4/18/2019     | Initial                     | Initial             |
| 4/14/2020     | Reviewed                    | No changes          | 
| 3/29/2021     | Reviewed                    | No changes          |
| 2/24/2022     | Updated                    | Added clarification and scope          |
| 4/10/2023     | Reviewed                    | No changes          |
| 5/01/2024     | Updated                    | Removed Heroku from 6.3          |
| 03/27/2025    | Reviewed                    | No changes          |