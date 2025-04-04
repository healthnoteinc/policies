---
layout: default
---

# 7. System Access Policy

Access to Health Note systems and applications is limited for all users, including but not limited to workforce members, volunteers, business associates, contracted providers, and consultants. Access by any other entity is allowable only on a minimum necessary basis. All users are responsible for reporting an incident of unauthorized use or access of the organization's information systems. These safeguards have been established to address the HIPAA Security regulations including the following:

## 7.1 Applicable Standards

### 7.1.1 Applicable Standards from the HITRUST Common Security Framework

* 01.d - User Password Management
* 01.f - Password Use
* 01.r - Password Management System
* 01.a - Access Control Policy
* 01.b - User Registration
* 01.h - Clear Desk and Clear Screen Policy
* 01.j - User Authentication for External Connections
* 01.q - User Identification and Authentication
* 01.v - Information Access Restriction
* 02.i - Removal of Access Rights
* 06.e - Prevention of Misuse of Information Assets

### 7.1.2 Applicable Standards from the HIPAA Security Rule

* 164.308(a)(4)(ii)(C) Access Establishment and Modification
* 164.308(a)(3)(ii)(B) Workforce Clearance Procedures
* 164.308(a)(4)(ii)(B) Access Authorization
* 164.312(d) Person or Entity Authentication
* 164.312(a)(2)(i) Unique User Identification
* 164.308(a)(5)(ii)(D) Password Management
* 164.312(a)(2)(iii) Automatic Logoff
* 164.310(b) Workstation Use
* 164.310(c) Workstation Security
* 164.308(a)(3)(ii)(C) Termination Procedures

### 7.1.3 Applicatble Standards from NIST
* NIST SP 800-63b, section 5.1.1

## 7.2 Access Establishment and Modification

1. Requests for access to Health Note systems and applications are made formally using the following process:
  1a. For new hires, Rippling automatically provisions predefined access based upon defined roles.
  1b. For access changes a Health Note workforce member initiates the access request by filling out a [**Systems Access Form**](https://docs.google.com/forms/d/e/1FAIpQLSdus2wN2WHjbj0JBal2aG6Z8NmguTP7am1GCmZAgPvb7zSKaw/viewform?usp=pp_url&entry.768761467=Pending).
     * User identities must be verified prior to granting access to new accounts.
     * As a remote-only company, identifies must be verified over the phone or video conference.
     * For new accounts, the method used to verify the user's identity must be recorded on the Systems Access Form.
  2. The Security Officer or Privacy Officer will review access to systems as dictated by the employee's job title. If additional access is required outside of the minimum necessary to perform job functions, the requester must include a description of why the additional access is required as part of the access request.
  3. Once the review is completed, the Security Officer or Privacy Officer approves or rejects the form. If the form is rejected, it goes back for further review and documentation.
  4. If the review is approved, the Security Officer or Privacy Officer then updates the Systems Access Form as Done, adding any pertinent notes required. IT Operations then grants requested access.
     * New accounts will be created with a temporary secure password that meets all requirements from [§7.12](#7.12-password-management), which must be changed on the initial login.
     * All password exchanges must occur over an authenticated channel.
     * For non-production systems, access grants are accomplished by leveraging the access control mechanisms built into those systems. Account management for non-production systems may be delegated to a Health Note employee at the discretion of the Security Officer, Privacy Officer, or CTO.
2. Access is not granted until receipt, review, and approval by the Health Note Security Officer or Privacy Officer.
3. The request for access is retained for future reference.
4. All access to Health Note systems and services is reviewed and updated on a bi-annual basis to ensure proper authorizations are in place commensurate with job functions. The form used to conduct account review is on Google Drive.  A security consultant is designated by the Security Officer or CTO to perform the access review.
5. Any Health Note workforce member can request change of access using the process outlined in [§7.2 paragraph 1](#7.2-access-establishment-and-modification).
6. Access to production systems is controlled using centralized user management and authentication.
7. Temporary accounts are not used unless absolutely necessary for business purposes.
   * Accounts are reviewed every 90 days to ensure temporary accounts are not left unnecessarily.
   * Accounts that are inactive for over 90 days are removed.
8. In the case of non-personal information, such as generic educational content, identification and authentication may not be required. This is the responsibility of Health Note Customers to define, and not Health Note.
9. Privileged users must first access systems using standard, unique user accounts before switching to privileged users and performing privileged tasks.
   * For production systems, this is enforced by creating non-privileged user accounts that must invoke `sudo` to perform privileged tasks.
   * Rights for privileged accounts are granted by the Security Officer or Privacy Officer using the process outlined in [§7.2 paragraph 1](#7.2-access-establishment-and-modification).
10. All application to application communication using service accounts is restricted and not permitted unless absolutely needed. Automated tools are used to limit account access across applications and systems.
11. Generic accounts are not allowed on Health Note systems.
12. In cases of increased risk or known attempted unauthorized access, immediate steps are taken by the Security and Privacy Officer to limit access and reduce risk of unauthorized access.
13. Direct system to system, system to application, and application to application authentication and authorization are limited and controlled to restrict access.

## 7.3 Workforce Clearance

1. The level of security assigned to a user to the organization's information systems is based on the minimum necessary amount of data access required to carry out legitimate job responsibilities assigned to a user's job classification and/or to a user needing access to carry out treatment, payment, or healthcare operations.
2. All access requests are treated on a "least-access principle."
3. Health Note maintains a minimum necessary approach to access to Customer data. As such, Health Note, including all workforce members, does not readily have access to any ePHI.
4. All workforce members are subject to a background check before access is granted to information systems, facilties, and/or ePHI.

## 7.4 Access Authorization

1. Role based access categories for each Health Note system and application are pre-approved by the Security Officer, or an authorized delegate of the Security Officer.  Defined roles can be referenced in Appendix 1 of the systems access policy.
2. Health Note utilizes hardware and software firewalls to segment data, prevent unauthorized access, and monitor traffic for denial of service attacks.

## 7.5 Person or Entity Authentication

1. Each workforce member has and uses a unique user ID and password that identifies him/her as the user of the information system.
2. Each Customer and Partner has and uses a unique user ID and password that identifies him/her as the user of the information system.

## 7.6 Unique User Identification

1. Access to the Health Note Platform systems and applications is controlled by requiring unique User Login IDs and passwords for each individual user and developer.
2. Passwords requirements mandate strong password controls (see below).
3. Passwords are not displayed at any time and are not transmitted or stored in plain text.
4. Default accounts on all production systems, including root, are disabled.
5. Shared accounts are not allowed within Health Note systems or networks.
6. Automated log-on configurations that store user passwords or bypass password entry are not permitted for use with Health Note workstations or production systems.

## 7.7 Automatic Logoff

1. Users are required to make information systems inaccessible by any other individual when unattended by the users (ex. by using a password protected screen saver or logging off the system).
2. Information systems automatically log users off or lock with password protected screen saver systems after 10 minutes of inactivity.
3. The Security Officer pre-approves exceptions to automatic log off requirements.

## 7.8 Employee Workstation Use

All employee workstations at Health Note are company owned, and all are laptop Apple products running Mac OSX or Linux or PC laptops running Windows 10 or Linux.

1. Workstations may not be used to engage in any activity that is illegal or is in violation of organization's policies.
2. Access may not be used for transmitting, retrieving, or storage of any communications of a discriminatory or harassing nature or materials that are obscene or "X-rated". Harassment of any kind is prohibited. No messages with derogatory or inflammatory remarks about an individual's race, age, disability, religion, national origin, physical attributes, sexual preference, or health condition shall be transmitted or maintained. No abusive, hostile, profane, or offensive language is to be transmitted through the organization's system.
3. Information systems/applications also may not be used for any other purpose that is illegal, unethical, or against company policies or contrary to organization's best interests. Messages containing information related to a lawsuit or investigation may not be sent without prior approval.
4. Solicitation of non-company business, or any use of organization's information systems/applications for personal gain is prohibited.
5. Transmitted messages may not contain material that criticizes the organization, its providers, its employees, or others.
6. Users may not misrepresent, obscure, suppress, or replace another user's identity in transmitted or stored messages.
7. All workstation hard drives are encrypted using FileVault 2.0, Windows Bitlocker, or equivalent.
8. All workstations have firewalls enabled to prevent unauthorized access unless explicitly granted.
9. All workstations are to have the following messages added to the lock screen and login screen: *This computer is owned by Health Note Health, Inc. By logging in, unlocking, and/or using this computer you acknowledge you have seen, and follow, these policies (https://healthnoteinc.github.io/policies/) and have completed this training (https://training.healthnote.com/). Please contact us if you have problems with this - privacy@HealthNote.com.*
10. All workstations are set to automatically update for Windows Updates or MacOS updates.
11. All workstations have virus protection software installed, configured, and enabled.

## 7.9 Wireless Access Use

1. Health Note production systems are not accessible directly over wireless channels.
2. Wireless access is disabled on all production systems.
3. When accessing production systems via remote wireless connections, the same system access policies and procedures apply to wireless as all other connections, including wired.
4. Wireless networks managed within Health Note non-production facilities (offices, etc.) are secured with the following configurations:
   * All data in transit over wireless is encrypted using WPA2 encryption;
   * Passwords are rotated on a regular basis, presently quarterly. This process is managed by the Health Note Security Officer.

## 7.10 Employee Termination Procedures

1. The Human Resources Department (or other designated department), users, and their supervisors are required to notify the Security Officer upon completion and/or termination of access needs and facilitating completion of the "Termination Checklist".
2. The Human Resources Department, users, and supervisors are required to notify the Security Officer to terminate a user's access rights if there is evidence or reason to believe the following (these incidents are also reported on an incident report and is filed with the Privacy Officer):
   * The user has been using their access rights inappropriately;
   * A user's password has been compromised (a new password may be provided to the user if the user is not identified as the individual compromising the original password);
   * An unauthorized individual is utilizing a user's User Login ID and password (a new password may be provided to the user if the user is not identified as providing the unauthorized individual with the User Login ID and password).
3. The Security Officer will terminate users' access rights immediately upon notification, and will coordinate with the appropriate Health Note employees to terminate access to any non-production systems managed by those employees.
4. The Security Officer audits and may terminate access of users that have not logged into organization's information systems/applications for an extended period of time.

## 7.11 Paper Records

Health Note does not use paper records for any sensitive information. Use of paper for recording and storing sensitive data is against Health Note policies.

## 7.12 Password Management

1. User IDs and passwords are used to control access to Health Note systems and may not be disclosed to anyone for any reason.
2. Users may not allow anyone, for any reason, to have access to any information system using another user's unique user ID and password.
3. On all production systems and applications in the Health Note environment, password configurations are expected to follow the Password Construction Guidelines (see 7.13).
4. All system and application passwords must be stored and transmitted securely.
   * Where possible, passwords should be stored in a hashed format using a salted cryptographic hash function (SHA-256 or equivalent).
   * Passwords that must be stored in non-hashed format must be encrypted at rest pursuant to the requirements in [§17.8](#17.8-production-data-security).
   * Transmitted passwords must be encrypted in flight pursuant to the requirements in [§17.9](#17.9-transmission-security).
5. Each information system automatically requires users to change passwords at a pre-determined interval as determined by the organization, based on the criticality and sensitivity of the ePHI contained within the network, system, application, and/or database.
6. Passwords are inactivated immediately upon an employee's termination (refer to the [Employee Termination Procedures in §7.10](#7.10-employee-termination-procedures)).
7. All default system, application, and Partner passwords are changed before deployment to production.
8. Upon initial login, users must change any passwords that were automatically generated for them.
9. Password change methods must use a confirmation method to correct for user input errors.
10. All passwords used in configuration scripts are secured and encrypted.
11. If a user believes their user ID has been compromised, they are required to immediately report the incident to the Security Office.

## 7.13 Password Construction Guidelines

Passwords are used for various purposes at the Health Note. Some of the more common uses include user-level accounts, web accounts, e-mail accounts, screen saver protection, voice-mail password, and customer logins. Since very few systems have support for one-time tokens (i.e., dynamic passwords
which are only used once), everyone should be aware of how to select strong passwords.

Limited only by systems that support it (we make our best effort to enforce up to the limitations of a particular platform):
* a minimum length of 16 and max length of 64 characters;
* a mix of upper case characters, lower case characters, and numbers or special characters;
* a 90-day password expiration on all accounts that can access ePHI or other sensitive data;
* prevention of password reuse using a history of the last 6 passwords;
* where supported, modifying at least 4 characters when changing passwords;
* user accounts that have system-level privileges granted through group memberships or programs such as "sudo" must have a unique password from all other accounts held by that user.
* where Simple Network Management Protocol (SNMP) is used, the community strings must be defined as something other than the standard defaults of "public," "private," and "system," and must be different from the passwords used to log in interactively. A keyed hash must be used where available (e.g., SNMPv2).

Google Workspace password requirements shall be set to “Enforce strong passwords”. Minimum requirements include:

* a minimum length of 16 and max length of 64 characters
* a mix of uppercase characters, lower case characters, and numbers or special characters
* a 90-day password expiration
* Password reuse not allowed
* 2FA/MFA is required

Amazon AWS password requirements shall be set to the strongest system settings. Minimum requirements include:

* a minimum length of 16 characters
* a mix of uppercase characters, lower case characters, and numbers or special characters
   * must contain at least one (1) uppercase letter from the Latin alphabet (A-Z)
   * must contain at least one (1) lowercase letter from the Latin alphabet (a-z)
   * must contain at least one (1) number character
   * must contain at least one non-alphanumeric character (special character)
* a 90-day password expiration
* password reuse from the last 24 changes are not allowed
* 2FA/MFA is required


## 7.14 Application Development Password Standards

Application developers must ensure their programs contain the following security precautions:
* Applications should support authentication of individual users - not groups.
* Applications should not store passwords in clear text or in any easily reversible form.
* Applications should provide for some sort of role management, such that one user can take
over the functions of another without having to know the other's password.
* Applications should support Single-Sign-On wherever possible.


## 7.15 Password Protection Guidelines

Passwords are meant to be treated as sensitive, confidential Health Note information. If someone demands a password, refer them to this document or have them call someone in the Security Office for clarification.
 
* Do not reveal a password over the phone to ANYONE.
* Do not reveal a password in an e-mail message.
* Do not reveal a password to the boss.
* Do not talk about a password in front of others.
* Do not hint at the format of a password (e.g., “my family name”).
* Do not reveal a password on questionnaires or security forms.
* Do not share a password with family members.
* Do not reveal a password to co-workers while on vacation.
* Do not write a password in an obvious place that is accessible to others.
* Do not write passwords down and store them anywhere in your office.
* Do not share agency passwords with anyone, including administrative/executive assistants.
* Do not use SMS for 2-factor auth - use an app or hardware device where possible.


## 7.16 Access to ePHI

1. Unless explicitly approved by management, Employees may not download ePHI to any workstations used to connect to production systems.
2. Disallowing transfer of ePHI to workstations is enforced through technical measures.
   * On production Linux bastions, all file transfer services are disabled including file-transfer functionality of SSH services (SCP/SFTP).

## Revisions

| Revision Date | Revision Description        | Notes               |
| --------------| --------------------------- | ------------------- |
| 4/18/2019     | Initial                     | Initial             |
| 4/14/2020     | Reviewed                    | No changes          | 
| 5/29/2021     | Updated                     | additional NIST password guidelines,etc.          |
| 2/24/2022     | Updated                    | clarification          |
| 5/26/2022     | Updated                    | update p&p          |
| 6/10/2022     | Updated                    | update scope          |
| 7/15/2022     | Updated                    | general updates          |
| 7/26/2022     | Updated                    | general updates          |
| 8/1/2022     | Updated                    | general updates          |
| 4/10/2023     | Updated                    | role change          |
| 10/23/2023     | Updated                    | form link          |
| 5/02/2024     | Updated                    | general updates         |
| 03/27/2025    | Reviewed                    | No changes          |