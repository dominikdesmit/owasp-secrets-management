# OWASP Secrets Management Cheat Sheet
The OWASP best practices and guidelines for Secrets Management

<b>Why</b>: Secrets are being used everywhere nowadays with the DevOps movement. API keys, database credentials, IAM permissions, SSH keys, certificates, etc. Many organizations have them hard coded in source code, littered throughout configuration files and configuration management tools, and stored in plaintext in version control.

There is a big need in the centralizations of secrets to improve the security posture and preventing secrets from leaking and compromizing the organization. Most of the time, services are sharing the same secrets that make identifying the source of compromise or leak very challenging.

This cheat sheet aims to guide in terms of best practices and guidelines to help implement secrets management properly.

## Secrets Management guidelines
- General
- CI/CD
- Cloud Providers
- Containers
- Implementation 
- Encryption
- Applications
- Workflow in case of compromise
- Secrets Management Tooling

### General Secrets Management
- High availability
- Centralized approach
- Fine grained ACLs
- Remove human interaction (dynamic secrets)
- Auditing
- Secret Lifecycle (rotation, deletion, creation, lifespan)
- TLS Everywhere
- Automate Key Rotation
- Restore and backup
- Policies

### CI / CD
- Build tools
- Rotation vs dynamic creation
- Identity authentication
- Deployment

### Cloud Providers
- Vendor lock-in
- Geo Restrictions
- Latency 
- Data access (keys of the kingdom)

### Containers & Orchestrators
- Injection of secrets (file, in-memory)
- Short lived side car containers
- Internal vs external access

### Implementation guidance
- Key material management policies
- Dynamic vs static use cases
- Processes and Governance

### Encryption
- Encryption as a service (EaaS)

### Applications
- Least amount of impact (LaoI)
- Easy to use
- Easy to get on-board

### Workflow in case of compromise
- Process

### Secrets Management Tooling Guidelines
- Many native integrations possible (Cloud platforms, CI/CD tooling, application libraries, container orchestrators)
- Secret lifecycle (rotation, deletion, lifespan)
- Key material management (keys to kingdom)
- Open source? (Depending on security posture)
- Encryption (at rest, in transit)
- Access control (fine grained)
- Performance
- Audit logs
- Scalable (enterprise)
- Manageable operations (upgrading, recovery)
- Agnostic
- Support for many secrets backends: database, certificates, ssh keys, cloud providers, key/value, etc
- Dynamic secrets
- Encryption as a service
- Fine grained policies (mfa requirements)
- Extensibility
- Documentation

## Contributing
Please help us make this a powerful guide by submitting pull requests!
