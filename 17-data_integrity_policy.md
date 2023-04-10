---
layout: default
---

# 17. Data Integrity Policy

Health Note takes data integrity very seriously. As stewards and partners of Health Note Customers, we strive to assure data is protected from unauthorized access and that it is available when needed. The following policies drive many of our procedures and technical settings in support of the Health Note mission of data protection.

Production systems that create, receive, store, or transmit Customer data (hereafter "Production Systems") must follow the guidelines described in this section.

## 17.1 Applicable Standards

### 17.1.1 Applicable Standards from the HITRUST Common Security Framework

* 10.b - Input Data Validation

### 17.1.2 Applicable Standards from the HIPAA Security Rule

* 164.308(a)(8) - HIPAA Security Rule Evaluation

## 17.2 Disabling Non-Essential Services

1. All Production Systems must disable services that are not required to achieve the business purpose or function of the system.

## 17.3 Monitoring Log-in Attempts

1. All access to Production Systems must be logged. This is done following the Health Note Auditing Policy.

## 17.4 Prevention of Malware on Production Systems

1. All Production Systems are to only be used for Health Note business needs.

## 17.5 Patch Management

1. Software patches and updates will be applied to all systems in a timely manner. In the case of routine updates, they will be applied after thorough testing. In the case of updates to correct known vulnerabilities, priority will be given to testing to speed the time to production. Critical security patches are applied within 30 days from testing and all security patches are applied within 90 days after testing.
2. Administrators subscribe to mailing lists to ensure that they are using current versions of all Health Note-managed software on Production Systems.

## 17.6 Intrusion Detection and Vulnerability Scanning

1. Production systems are monitored using IDS systems. Suspicious activity is logged and alerts are generated.
2. Vulnerability scanning of Production Systems must occur on a predetermined, regular basis, no less than annually. Currently it is weekly. Scans are reviewed by Security Officer, with defined steps for risk mitigation, and retained for future reference.

## 17.7 Production System Security

1. System, network, and server security is managed and maintained by the Security Officer in conjunction with the Dev Ops team.
2. Up-to-date system lists and architecture diagrams are kept for all production environments.
3. Access to Production Systems is controlled using centralized tools and two-factor authentication.

## 17.8 Production Data Security

1. Reduce the risk of compromise of Production Data.
2. Implement and/or review controls designed to protect Production Data from improper alteration or destruction.
3. Ensure that confidential data is stored in a manner that supports user access logs and automated monitoring for potential security incidents.
4. Ensure Health Note Customer Production Data is segmented and only accessible to Customers authorized to access data.
5. All Production Data at rest is stored on encrypted volumes using encryption keys managed by Health Note. 

## 17.9 Transmission Security

1. All data transmission is encrypted end to end using encryption keys managed by Health Note. Encryption is not terminated at the network end point, and is carried through to the application.
2. Transmission encryption keys and machines that generate keys are protected from unauthorized access. 
3. Transmission encryption keys are limited to use for one year and then must be regenerated.
4. In the case of Health Note provided APIs, provide mechanisms to assure person sending or receiving data is authorized to send and save data.
5. System logs of all transmissions of Production Data access. These logs must be available for audit.


## 17.10 Email Security

1. Standard Email encryption as provided by the use of Google Suite (Gmail) is in use.

## 17.11 De-Identification of ePHI

1. When explictitly requested by the client all ePHI is de-identified on over 50 fields using an algorithmic anonymizer sanitation dictionary.

## Revisions

| Revision Date | Revision Description        | Notes               |
| --------------| --------------------------- | ------------------- |
| 4/18/2019     | Initial                     | Initial             |
| 4/14/2020     | Reviewed                    | No changes          | 
| 3/29/2021     | Reviewed                    | No changes          |
| 2/24/2022     | Reviewed                    | No changes          |
| 5/26/2022     | Updated                    | update p&p          |
| 6/16/2022     | Updated                    | add section          |
| 8/25/2022     | Updated                    | add clarification          |
| 4/10/2023     | Reviewed                    | No changes          |