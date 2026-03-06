# 29.0 System Development Life Cycle Policy

## 29.1 Purpose

The purpose of the Systems Development Life Cycle (SDLC) Policy is to describe the requirements for developing
and/or implementing new software and systems at the Health Note and to ensure that all development
work is compliant as it relates to any and all regulatory, statutory, federal, and /or state guidelines.

## 29.2 Scope

This policy is applicable to all employees (full time, or part time), contractors, and other
covered individuals (e.g., vendors, independent contractors, etc.) that perform any type of
software or systems development work under the purview of Health Note.
In the event a department chooses to seek an exemption for reasons such as inability to meet specific
points, tasks, or subtasks within the SDLC Policy or Standards, a SDLC Review Committee, comprised of
representatives from across departments as designated by Information Technology, will convene in order to assess the
specific merits of the exemption request(s) while still adhering to the main principles behind the SDLC Policy and
Standards.

## 29.3 Policy


Information Technology at Health Note is responsible for developing, maintaining, and participating in a Systems Development Life Cycle (SDLC) for system development projects. All entities at the company, engaged in systems or software development activities, must follow the SDLC.

SDLC Phases:
1. Initiation
2. Development / Acquisition
3. Implementation / Assessment
4. Operations and Maintenance
5. Disposal

### 29.3.1 Secure Development Requirements (PCI Compliance)

To ensure compliance with PCI and other regulatory requirements, the following secure development controls must be implemented throughout the SDLC:

- **Prevention of Authorization Bypass Attacks:**
	- Enforce strict access controls and least privilege principles.
	- Implement robust authentication and authorization checks at every layer of the application.
	- Conduct regular code reviews and penetration testing to identify and remediate potential bypass vectors.

- **Prevention of Cross Site Request Forgery (CSRF) Attacks:**
	- Use anti-CSRF tokens for all state-changing requests.
	- Validate the origin and referer headers where appropriate.
	- Educate developers on secure coding practices to avoid CSRF vulnerabilities.

- **Prevention of Cross Site Scripting (XSS) Attacks:**
	- Sanitize and validate all user input and output.
	- Use secure frameworks and libraries that provide built-in XSS protection.
	- Implement Content Security Policy (CSP) headers where feasible.

- **Prevention of Injection Attacks (e.g., SQL, Command, LDAP):**
	- Use parameterized queries and prepared statements for all database access.
	- Avoid dynamic code execution and direct user input in system commands.
	- Validate and sanitize all inputs before processing.

- **Avoidance of Insecure Session IDs:**
	- Use secure, randomly generated session identifiers.
	- Transmit session IDs only over encrypted (TLS/SSL) channels.
	- Implement session expiration and regeneration on privilege changes.

- **Use of Vulnerable Libraries:**
	- Regularly scan for vulnerabilities using automated tools.
	- Promptly update or replace libraries with known vulnerabilities.
	- Unacceptable use: Deploying or continuing to use libraries with known, unpatched critical vulnerabilities.
	- Acceptable use: Only libraries with no known critical vulnerabilities and with active maintenance/support.

All development teams must document and demonstrate compliance with these requirements as part of the SDLC process. Failure to adhere to these controls may result in disciplinary action and/or removal of non-compliant systems from production environments.

## 29.4 Exemptions

If an exemption from this policy is required, a Policy Exemption request needs to be submitted and it needs to
clearly articulate the reason for the exemption. An operational risk assessment will be conducted to identify the
risks associated with this exemption. Exceptions to this policy and associated standards shall be allowed only if
previously approved by the SDLC Review Committee and such approval documented and verified by the Chief
Technology Officer. If the committee can accept the risk, an exemption to this policy may be granted.

## 29.5 Enforcement

Information Technology is responsible for managing security assessments for the company according to established requirements.
Any systems under the policy authority of IT with requirements
that deviate from the policies are required to submit a Policy Exemption Form to IT for
consideration and potential approval.
Any attempt by personnel to circumvent or otherwise bypass this policy or any supporting policy will be treated as
a security violation and subject to investigation. The results of the investigation may entail written reprimand,
suspension, termination, and possibly criminal and/or civil penalties.

## Revisions
| Revision Date | Revision Description        | Notes               |
| --------------| --------------------------- | ------------------- |
| 5/27/2021     | Initial                    | Initial          |
| 2/24/2022     | Reviewed                    | No changes          |
| 4/10/2023     | Reviewed                    | No changes          |
| 5/03/2024     | Reviewed                    | No changes          |
| 03/27/2025    | Reviewed                    | No changes          |
| 03/05/2026   | Updated                      | Updates for PCI compliance|