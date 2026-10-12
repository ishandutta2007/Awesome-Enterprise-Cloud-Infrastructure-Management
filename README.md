# Awesome-Enterprise-Cloud-Infrastructure-Management

## Top Enterprise Cloud Infrastructure Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Infrastructure-as-Code, Multi-Cloud Orchestration & Cloud Governance*

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Cloud Infrastructure Management**. These tools enable organizations to provision, orchestrate, and govern cloud resources across public, private, and hybrid environments—with policy enforcement, cost optimization, and self-service delivery.



**Examples** include Salesforce Hyperforce, VMware Aria, HashiCorp Terraform Cloud (HCP Terraform), AWS CloudFormation, Azure Management, Google Cloud Deployment Manager, Nutanix Prism, Morpheus Data, Spacelift, and env0 (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, multi-cloud orchestration, and open IaC platforms—ideal for platform engineers, DevOps teams, and organizations seeking transparent, vendor-independent infrastructure management.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesforce Hyperforce](https://www.salesforce.com/)**  

  Salesforce's next-generation infrastructure foundation for deploying application stacks on public cloud providers (primarily AWS). Enables data residency control across Australia, Canada, France, Germany, India, Japan, UK, and US. Zero-trust security principles with encryption at rest and in transit. No additional cost for migration .



- **[VMware Aria](https://www.vmware.com/products/aria.html)**  

  Unified cloud management for VMware Cloud Foundation. Products no longer sold standalone—capabilities now part of VCF. Aria Automation for self-service provisioning, Aria Operations for AI-powered IT operations, Aria Suite Lifecycle for automated app management. Reported 5X reduction in relative downtime and 50% reduction in network outages .



- **[HCP Terraform (Terraform Cloud)](https://www.hashicorp.com/products/terraform)**  

  HashiCorp's managed IaC platform. Free tier up to 500 resources/month, then $0.00014/hour per resource. Features workspaces, VCS integration, Sentinel/OPA policy as code, private module registry, and config-driven import. Note: resource-based pricing counts every resource in state—teams often find their actual count is 3-4x assumed .



- **[AWS CloudFormation](https://aws.amazon.com/cloudformation/)**  

  Native AWS IaC service for declaring resources in JSON/YAML templates. Features stacks, change sets, StackSets for multi-account/multi-region provisioning, and IaC Generator to create templates from existing resources. Highly reliable and mature with drift detection .



- **[Azure Management](https://azure.microsoft.com/)**  

  Comprehensive cloud management spanning monitoring, configuration, governance, security, protection, and migration. Azure Policy for governance compliance, Azure Cost Management for spend tracking, Microsoft Defender for Cloud for hybrid security, Azure Backup and Site Recovery for business continuity .



- **[Google Cloud Deployment Manager](https://cloud.google.com/deployment-manager)**  

  Google Cloud's infrastructure deployment service for automating resource creation and management. Configuration files and templates define deployments spanning Compute Engine, Cloud Storage, Cloud SQL, and other services. Examples repository and reference architectures available .



- **[Nutanix Prism](https://www.nutanix.com/products/prism)**  

  Unified management plane for Nutanix Cloud Infrastructure—included at no additional cost. Single console for on-prem and public cloud VMs, storage, and networking. Features proactive health monitoring, multi-cluster management, automated lifecycle management, live migration, and granular RBAC. Prism Central for global-scale visibility via Nutanix Central .



- **[Morpheus Data](https://morpheusdata.com/)**  

  Infrastructure-agnostic multi-cloud orchestrator with deep integrations across AWS, Azure, GCP, VMware, OpenStack, Nutanix, and bare metal. Self-service provisioning, unified governance, and FinOps-focused cost optimization. Infrastructure-agnostic positioning competitive against VMware and Red Hat. AstraZeneca reduced deployment time from 80 hours to minutes .



- **[Spacelift](https://spacelift.io/)**  

  Multi-IaC orchestration platform supporting Terraform, OpenTofu, Ansible, Kubernetes, Terragrunt, CloudFormation, and Pulumi. Features policy as code (OPA), stack dependencies, drift detection, and AI assistant with MCP server. Self-hosted option with multi-region disaster recovery. Checkout.com scaled from handful to 500+ deployments/day .



- **[env0](https://www.envzero.com/)**  

  IaC automation platform with flat monthly pricing (not per-resource). Supports Terraform, Terragrunt, and OpenTofu. Features unlimited concurrency, multi-IaC support, cost enforcement with budget-blocking, TTL environments, Cloud Analyst AI, and self-hosted agents. Positioned for teams frustrated with HCP Terraform's resource-based billing .



## Open-Source GitHub Projects



- **[Terraform](https://github.com/hashicorp/terraform)**  

  Industry-standard IaC tool (MPL-2.0) for provisioning cloud resources via HCL. 44k+ GitHub stars. Declarative configuration, plan/apply workflow, and extensive provider ecosystem covering AWS, Azure, GCP, and hundreds of services. Foundation for most enterprise IaC practices .



- **[OpenTofu](https://github.com/opentofu/opentofu)**  

  Open-source Terraform fork under Linux Foundation (MPL-2.0). Created after HashiCorp's license change to BSL 1.1. Drop-in replacement with community governance. 25k+ GitHub stars. Features state encryption, early variable evaluation, and provider iteration. Supported natively by Spacelift and env0 .



- **[Crossplane](https://github.com/crossplane/crossplane)**  

  Open-source control plane (Apache-2.0) turning Kubernetes into a universal cloud resource orchestrator. 10k+ GitHub stars. Manages AWS, Azure, GCP, and on-prem resources as Kubernetes custom resources. Enables GitOps-driven infrastructure with continuous reconciliation and drift correction .



- **[Pulumi](https://github.com/pulumi/pulumi)**  

  Open-source IaC SDK (Apache-2.0) using general-purpose programming languages—TypeScript, Python, Go, .NET, Java. 22k+ GitHub stars. Supports 100+ providers including AWS, Azure, GCP, Kubernetes, and Cloudflare. Features component model for reusable infrastructure patterns and policy as code .



- **[Ansible](https://github.com/ansible/ansible)**  

  Open-source configuration management and automation platform (GPL-3.0). 63k+ GitHub stars. Agentless architecture via SSH. Supports cloud provisioning (AWS, Azure, GCP modules), configuration management, application deployment, and orchestration. Foundation for many enterprise automation workflows.



- **[Kubernetes](https://github.com/kubernetes/kubernetes)**  

  Container orchestration platform (Apache-2.0) serving as cloud-native control plane. 113k+ GitHub stars. Foundation for Crossplane, cluster API, and modern infrastructure management. Enables declarative resource management across hybrid and multi-cloud environments.



- **[Cluster API](https://github.com/kubernetes-sigs/cluster-api)**  

  Kubernetes SIG project (Apache-2.0) for declarative cluster lifecycle management. 3k+ GitHub stars. Provisions and manages Kubernetes clusters across AWS, Azure, GCP, vSphere, and bare metal using Kubernetes-style APIs.



- **[KubeVirt](https://github.com/kubevirt/kubevirt)**  

  Open-source add-on (Apache-2.0) running VMs alongside containers in Kubernetes. 6k+ GitHub stars. Enables unified management of VM and container workloads—useful for hybrid infrastructure management and legacy workload migration.



- **[KubeCost](https://github.com/kubecost/cost-analyzer)**  

  Open-source Kubernetes cost monitoring (Apache-2.0). 5k+ GitHub stars. Provides real-time cost visibility, allocation, and optimization recommendations for multi-cloud Kubernetes environments.



- **[Infracost](https://github.com/infracost/infracost)**  

  Open-source cloud cost estimation for IaC (Apache-2.0). 11k+ GitHub stars. Shows cost impact of Terraform changes in pull requests before apply. Supports AWS, Azure, GCP, and 200+ resources.



### Additional Strong Open-Source Options



- **[Terragrunt](https://github.com/gruntwork-io/terragrunt)** — Thin Terraform wrapper (MIT) for DRY configurations and multi-environment orchestration.

- **[Atlantis](https://github.com/runatlantis/atlantis)** — Terraform pull request automation (Apache-2.0) for GitOps workflows.

- **[Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)** — Multi-cloud governance rules engine (Apache-2.0) for policy enforcement and cost optimization.

- **[Steampipe](https://github.com/turbot/steampipe)** — Zero-ETL cloud API querying with SQL (AGPL-3.0) for infrastructure visibility.

- **[Checkov](https://github.com/bridgecrewio/checkov)** — Static analysis for IaC (Apache-2.0) with 1000+ built-in policies.

- Community **n8n** workflows for cloud resource provisioning and alerting automation.



**Frameworks for building custom systems**: Combine **OpenTofu** or **Terraform** as the provisioning engine with **Crossplane** for Kubernetes-native control planes, **Atlantis** or **Spacelift** for GitOps workflow automation, **Infracost** for cost governance, and **Cloud Custodian** for policy enforcement—creating a fully self-hosted, enterprise-grade cloud infrastructure management platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Cloud infrastructure management platforms handle credentials and control critical resources—must follow security best practices (least privilege, short-lived credentials, audit logging).

- Self-hosted open-source solutions require proper security hardening, state file protection, and ongoing maintenance. Resource-based pricing on managed platforms can become unpredictable as infrastructure scales—measure actual resource counts before committing to tiers .



---



**Made for platform engineers, DevOps teams, cloud architects, and developers building transparent infrastructure management solutions.**

Let's make Enterprise Cloud Infrastructure Management more open, data-driven, and efficient.
