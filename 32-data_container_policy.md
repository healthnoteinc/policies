# 32.0 Data Container Security Policy 

## 32.1 Purpose

Containers and container infrastructure is used extensively at Health Note.   Health Note is committed to securing containers against malware, data leaks, and other threats at all stages of the container lifecycle. The purpose of this policy is to ensure that all Health Note containers and container infrastructure are properly managed to maintain data integrity and security. 

## 32.2 Scope

- Systems and Infrastructure Assets
- Application and Dependencies

## 32.3 Container infrastructure security

- Access to private container registries, kubernetes clusters, CI/CD pipelines are secured following the least privilege model.

## 32.4 Container images

Usage of external container images require them to be signed and originate from a trusted registry.

Container images are stored in private repositories on Amazon AWS's Elastic Container Registry.

## 32.5 Container scanning

Containers are scanned for vulnerabilities and identified vulnerabilities are ticketed for remediation.
 

## 32.6 Container security requirements

 Containers are required to utilize Linux User Namespace Support to reduce the kernel and system resources that a container can access.
