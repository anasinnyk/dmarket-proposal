# DMarket Proposals

---
@snap[north span-50]
### Why am I start working on it?
@snapend
```
> k get po --no-headers=true --all-namespaces | wc -l #630

> k get ns --no-headers | wc -l #31

> gcloud container clusters list | wc -l #8
```
---
@snap[north span-50]
### Cluster != Environment
@snapend
> Computer cluster - set of loosely or tightly connected computers that work together

> Environment - represents the association between variable names and data types.
---
@snap[north span-50]
### Everything a code
@snapend
- Infrastructure as code
- Documentation as code
- Configuration as code
- Diagram as code
- Slides as code
---
@snap[north span-50]
### Terraform
@snapend

@snap[west span-50]
![](img/terraform.png)
@snapend
@snap[east span-50]
HashiCorp Terraform enables you to safely and predictably create, change, and improve infrastructure.
@snapend
---
@snap[north span-50]
### Possibilities
@snapend
- Modify cloudflare Configuration
- Added github webhook
- Manage access to external services github, cloudflare, vault
- Google cloud configuration
- Kubernetes configuration
- Helm packages installations
@snap[north span-50]
### Atlantis
@snapend
@snap[west span-50]
![](img/atlantis.png)
@snapend
@snap[east span-50]
Atlantis is an application for automating Terraform via pull requests. It is deployed as a standalone application into your infrastructure
@snapend
---
@snap[north span-50]
### Steps for delivery
@snapend
- Change infrastructure as code
- Create pull request
- Apply configuration on test environment
- Reviewed
- Verified
- Approved
- Deploy to production
---
@snap[north span-50]
### Vault
@snapend

@snap[west span-50]
![](img/vault.png)
@snapend
@snap[east span-50]
Secure, store and tightly control access to tokens, passwords, certificates, encryption keys for protecting secrets and other sensitive data
@snapend
---
@snap[north span-50]
### Possibilities
@snapend
- Remove secrets from code
- Provide secrets like environment variable to different application (BanzaiCloud)
- Manage pool secret access
---
@snap[north span-50]
### Argo
@snapend
@snap[west span-50]
![](img/argo.png)
@snapend
@snap[east span-50]
Open source Kubernetes native workflows, events, CI and CD
@snapend
---
@snap[north span-50]
### Possibilities
@snapend
- Handle any webhook (GitHub, DockerHub, Slack)
- Apply the same workflows to different projects
- Create different workflows pool
---
# Demo
