# DMarket Proposals

---
### Why am I start working on it?

```
> k get po --no-headers=true --all-namespaces | wc -l #630

> k get ns --no-headers | wc -l #31

> gcloud container clusters list | wc -l #8
```
---
## Cluster != Environment

> Computer cluster - set of loosely or tightly connected computers that work together

> Environment - represents the association between variable names and data types.
---
## DRY Principle

- .circleci/config.yaml
- Makefile
- Dockerfile
---
## Everything a code

- Infrastructure as code
- Documentation as code
- Configuration as code
- Diagram as code
- Slides as code
---
## Steps for delivery

- Change infrastructure configuration
- Create pull request
- Apply configuration on test environment
- Reviewed
- Verified
- Approved
- Deploy to production
---
## Terraform

@snap[west span-50]
![](img/terraform.pmg)
@snapend
@snap[east span-50]
HashiCorp Terraform enables you to safely and predictably create, change, and improve infrastructure. It is an open source tool that codifies APIs into declarative configuration files.
@snapend
