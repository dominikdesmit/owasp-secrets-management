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

## Secrets Management tooling guidelines
- Minimum requirements

