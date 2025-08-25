# OCI Zero to Hero

Learn Oracle Cloud Infrastructure (OCI) from scratch through structured notes, hands-on exercises, architecture diagrams, and links to free Oracle resources. This 21-day guide is inspired by similar cloud learning paths and focuses on practical DevOps practices.

No prior experience required—just sign up for OCI's Free Tier (oracle.com/cloud/free) for hands-on practice. Each day includes notes, exercises, and diagrams in dedicated folders. Contribute your improvements via pull requests!

### Why OCI?
- OCI offers high-performance compute (e.g., bare metal), always-free resources, and strong security features.
- Compare with AWS/Azure/GCP: OCI emphasizes cost predictability and multi-cloud interoperability.

### Getting Started
1. Sign up for OCI Free Tier: Get $300 credit and always-free resources like 2 VMs and an Autonomous Database.
2. Install OCI CLI: Follow docs.oracle.com/en-us/iaas/Content/API/Concepts/cliconcepts.htm.
3. Join the community: Share your progress on LinkedIn or Reddit (e.g., r/OracleCloud).

## Day 1: Introduction to Cloud and OCI
- Notes on cloud computing basics, OCI vs. others.
- Set up your OCI account and explore the Console/Cloud Shell.
- Diagram: Cloud architecture overview.
- [Folder: day-01](./day-01)

## Day 2: OCI Tenancy Setup and Billing
- Understand tenancies, compartments, quotas.
- Set budgets and enable APIs.
- Diagram: OCI hierarchy.
- [Folder: day-02](./day-02)

## Day 3: IAM – Policies and Best Practices
- IAM basics: users, groups, policies.
- Principle of least privilege.
- Use case: Limited access for a teammate.
- Diagram: Policy flow.
- [Folder: day-03](./day-03)

## Day 4: Compute Service – Instances, SSH, and Shapes
- Launch VMs/bare metal, connect via SSH.
- Instance shapes and NSGs.
- Diagram: Compute topology.
- [Folder: day-04](./day-04)

## Day 5: Object Storage – Buckets and Files
- Create buckets, lifecycle policies.
- Static website hosting.
- Demo: Integrate with a compute instance.
- Diagram: Storage tiers.
- [Folder: day-05](./day-05)

## Day 6: Virtual Cloud Network (VCN) – Subnets and Security
- VCNs, subnets, CIDRs.
- Security Lists and NSGs.
- Diagram: Network architecture.
- [Folder: day-06](./day-06)

## Day 7: Load Balancing and Autoscaling
- Set up Load Balancers and Instance Pools.
- Health checks for HA.
- Diagram: Autoscaling setup.
- [Folder: day-07](./day-07)

## Day 8: DNS and Domain Mapping
- DNS zones and records.
- Map domains to apps.
- Diagram: DNS resolution flow.
- [Folder: day-08](./day-08)

## Day 9: Monitoring and Logging
- Metrics, dashboards, alarms.
- Use case: CPU alert.
- Diagram: Monitoring pipeline.
- [Folder: day-09](./day-09)

## Day 10: Database Service – Autonomous Database
- Create ATP database, secure access.
- Backups and scaling.
- Diagram: DB architecture.
- [Folder: day-10](./day-10)

## Day 11: Vault – Managing Secrets
- Store and access secrets.
- IAM integration.
- Diagram: Secrets workflow.
- [Folder: day-11](./day-11)

## Day 12: Events and Notifications
- React to events, send alerts.
- Use case: Bucket creation notification.
- Diagram: Event-driven flow.
- [Folder: day-12](./day-12)

## Day 13: Docker on OCI – Containerizing Apps
- Dockerize apps, push to OCIR.
- Run containers.
- Diagram: Container lifecycle.
- [Folder: day-13](./day-13)

## Day 14: Container Registry – Secure Image Storage
- Manage OCIR repositories.
- Versioning and access.
- Diagram: Registry integration.
- [Folder: day-14](./day-14)

## Day 15: Intro to Kubernetes + OKE Cluster Setup
- Kubernetes basics, create OKE cluster.
- Deploy sample pod.
- Diagram: OKE components.
- [Folder: day-15](./day-15)

## Day 16: Deploy a Real App on OKE
- Deploy custom app with YAML.
- Updates and rollbacks.
- Diagram: App deployment.
- [Folder: day-16](./day-16)

## Day 17: DevOps with OCI Resource Manager
- CI/CD pipelines with GitHub.
- Automated deployments.
- Diagram: Pipeline overview.
- [Folder: day-17](./day-17)

## Day 18: Terraform – Infrastructure as Code
- Provision resources with Terraform.
- State management.
- Diagram: IaC flow.
- [Folder: day-18](./day-18)

## Day 19: Real-Time DevOps Project
- Combine tools for an e-commerce app.
- Monitoring and secrets.
- Diagram: End-to-end architecture.
- [Folder: day-19](./day-19)

## Day 20: Serverless with OCI Functions and API Gateway
- Deploy functions and APIs.
- Compare with OKE.
- Diagram: Serverless setup.
- [Folder: day-20](./day-20)

## Day 21: OCI Cost Optimization for DevOps
- Billing tips, autoscaling.
- Delete unused resources.
- Diagram: Cost breakdown.
- [Folder: day-21](./day-21)

### Additional Resources
- Oracle University Free Courses: learn.oracle.com (L100/L200/L300 levels).
- OCI Docs: docs.oracle.com/en-us/iaas.
- Oracle Learning YouTube: youtube.com/@OracleLearning.
- Contribute: Add your notes, diagrams, or fixes!

About: Community-driven OCI learning path. Fork and improve!

License: MIT
