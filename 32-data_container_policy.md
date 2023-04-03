# 32.0 Data Container Security Policy 

## 32.1 Purpose

Containers and container infrastructure is used to host applications at Health Note.   Health Note is committed to securing containers against malware, data leaks, and other threats at all stages of the container lifecycle. The purpose of this policy is to ensure that all Health Note containers and container infrastructure are properly managed to maintain data integrity and security. 

## 32.2 Scope

- Systems and Infrastructure Assets
- Application and Dependencies

## 32.3 Container infrastructure security

- Access to private container registries, Kubernetes clusters, CI/CD pipelines are secured following the least privilege model with Amazon AWS.
- Helm and helm charts are used to orchestrate deployments within CI/CD pipelines 
- Container secrets are managed in a secret management system, i.e. AWS Parameter Store
- Commit IDs are used to tag images to ensure consistent automated builds and to prevent attacks leveraging tag mutability
## 32.4 Container images

- Use of external container images are required to be signed and originate from a trusted registry, i.e. Docker Hub
- Health Note Application container images are stored in private repositories within Amazon AWS's Elastic Container Registry.

## 32.5 Container scanning

- Containers are regularly scanned for vulnerabilities and identified vulnerabilities are queued/documented/ticketed for remediation.
 

## 32.6 Container security requirements

 - Containers are required to utilize Linux User Namespace Support to reduce the kernel and system resources that a container can access.
