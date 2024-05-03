# 33.0 Cloud Security Policy 

## 33.1 Purpose

This policy ensures the confidentiality, integrity and availability of data stored, accessed and manipulated using cloud computing services. It establishes a framework of responsibility and actions required to meet regulatory requirements and security guidelines for cloud computing.

## 33.2 Scope

This policy covers systems handling data within the “1.4. Information Types” section of this document. All services within the cloud environment that fall into this category will be subject to the requirements specified within this policy. Therefore, it applies to every server, database and other IT system that handles such data, including any device that is regularly used for email, web access or other work-related tasks. The requirements apply to new and existing installations. Every user who interacts with company IT services is also subject to this policy. The security control requirements are product agnostic and applicable for all approved cloud systems.

## 33.3 Ownership and Responsibilities

- Cloud Security Administrator

The person ultimately responsible for implementation, configuration and maintenance of cloud services security. This person shall address the following:

- Implementing security for new services
- Customizing the configuration of the cloud service security settings
- Maintaining access control and permissions management for each cloud service provided
- Retiring terminated services

## 33.4 Secure Usage of Cloud Computing Services

All cloud-based services must be approved prior to acquisition and deployment. To ensure secure adoption and usage of cloud services, the following steps must be taken:

- Define organizational needs and priorities.
- Define service users, both internal and external.
- Determine the type of cloud service to be adopted, including the physical and operational characteristics for SaaS, PaaS and IaaS solutions.
- Define the data types to be stored.
- Determine the security solutions and configurations required for encryption, monitoring, backups, etc.
- Generate a list of past security incidents involving this cloud provider.
- Request available security certifications.
- Obtain copies of agreements with the provider, including SLAs.

## 33.5 Inventory

- The Infrastructure Lead must perform an inventory of cloud services in use at least annually.
 
## 33.6 Approved Services

The organization is based in the U.S. with remote employees nationally and globally. All employees access services remotely from mobile and desktop devices (computers, laptops, tablets, phones, etc.). Each department — such as human resources, sales and project management — uses one or more cloud services. All departments must maintain a list of authorized cloud vendors and services that align with the overall cloud security policy.

The list of approved services includes: 

- Hardware layer: Amazon AWS

- Infrastructure layer: Amazon EC2, Amazon EKS, Amazon Lambda, MongoDB Atlas

- Platform layer: Amazon RDS, Amazon Elasticache, Amazon S3, AWS Workspaces

- Application layer: Absolute, Bandwidth, Bitwarden, Box, Brex, Calendly, Docusign, Github, Gong, Greenhouse, Hubspot, JAMF, JIRA, LucidChart, Notion, Pingdom, Postman, Rockelane, Rippling, SendGrid, Sentry, Slack, Stripe, Twilio, Zendesk, Zoom

## 33.6 Unauthorized Services

Only the cloud-based solutions on the list of approved services specified in Section 6 of this document may be used. The installation of unauthorized software on organizationally owned or managed user end-point devices (e.g., workstations, laptops and mobile devices) and IT infrastructure network and systems components is restricted. The cloud security administrator must provide authorization for any third-party cloud service before it is placed into use. 

## 33.7 Risk Assessment

Data from the “Sensitive” tier of the Data Classification Policy shall be available at all times, per regulations, for discovery and audit. Cloud providers shall conform to these compliance requirements.

The Cloud Security Administrator and the IT Security team shall conduct a risk assessment at the following times:

- Upon the implementation of a new cloud service
- After major upgrades or updates to an existing cloud service
- After any changes to the configuration of a cloud service
- When following up on a security event or incident
- Quarterly for all existing cloud services
- The cloud security risk assessment shall include the following:

- Audit results, both internal and external (cloud provider system security audit results)
- Threat and vulnerability analysis
- Regulatory compliance

## 33.8 Security Controls

At the time of cloud service implementation and quarterly after that, the Cloud Security Administrator shall review each service-level agreement, as well as request and analyze the cloud provider’s security audits.

## 33.9 Technical Security Controls Requirements

The organization shall put into place tools for centralized visibility of the cloud service infrastructure, such as cloud workload protection (CWP) tools. The tools shall offer traffic analysis, configuration monitoring and assessment, and alerts for configuration issues.

Access control methods to be used shall include:

- Auditing of attempts to log on to any device on the company network
- Role-based access model
- Firewall permissions
- Network zone and VLAN ACLs
- Web authentication rights
- Database access rights and ACLs
- Encryption at rest and in flight
- Network segregation
- Access controls apply to all networks, servers, workstations, laptops, mobile devices, cloud applications and websites, cloud storages, and services.

Identity and access controls include authentication, data access standards, credential lifecycle management and access segmentation.

Auditing includes configuration and change auditing. 

Data protection includes encryption, data remediation, data erasure, and data recovery.

Other technical controls include network security and wireless security (such as VPNs and firewalls).

## 33.10 Mobile Security Requirements

Cloud security shall include mobile security controls to prevent malware infection on company mobile devices and privately owned devices used to access the organization’s cloud services. Any device found without anti-malware protection shall be quarantined.

## 33.11 Awareness-Raising

The IT Security Management office shall provide quarterly security training to all users of cloud services. All users of cloud services must pass security training to maintain permissions and access to the service.

## 33.12 Enforcement

Employees who attempt to use unauthorized services shall have their permissions revoked until they pass security training.

## Revisions

| Revision Date | Revision Description        | Notes               |
| --------------| --------------------------- | ------------------- |
| 4/9/2023      | Initial                     | Initial             |
| 5/03/2024     | Updated                     | Removed Heroku and Microsoft Azure             |