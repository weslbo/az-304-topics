# AZ-304 Exam (Beta) objectives

__Important__:

The aim of this guide is to provide the Azure Architect learner for [AZ-304 (beta)](https://docs.microsoft.com/en-us/learn/certifications/exams/az-304) with various links towards official Azure documentation. This is by no means an official guide, nor a guarantee to pass the exam. Although this guide has an extensive list of topics you should master, it is no way an exhaustive list. 

[Design Monitoring (10-15%)](monitoring.md)
-------------------------------------------

#### Design for cost optimization

- recommend a solution for cost management and cost reporting
- recommend solutions to minimize costs

#### Design a solution for logging and monitoring

- determine levels and storage locations for logs
- plan for integration with monitoring tools including Azure Monitor and Azure Sentinel
- recommend appropriate monitoring tool(s) for a solution
- choose a mechanism for event routing and escalation
- recommend a logging solution for compliance requirements

[Design Identity and Security (25-30%)](identity-and-security.md)
---------------------------------------------------------------

#### Design authentication

- recommend a solution for single-sign on
- recommend a solution for authentication
- recommend a solution for Conditional Access, including multi-factor authentication
- recommend a solution for network access authentication
- recommend a solution for a hybrid identity including Azure AD Connect and Azure AD Connect Health
- recommend a solution for user self-service password reset
- recommend and implement a solution for B2B integration
- NOT: federation with ADFS

#### Design authorization

- choose an authorization approach
- recommend a hierarchical structure that includes management groups, subscriptions and resource groups
- recommend an access management solution including RBAC policies, access reviews, role assignments, physical access, Privileged Identity Management (PIM), Azure AD Identity Protection, Just In Time (JIT) access

#### Design governance

- recommend a strategy for tagging
- recommend a solution for using Azure Policy
- recommend a solution for using Azure Blueprint

#### Design security for applications

- recommend a solution that includes KeyVault
  - What can be stored in KeyVault
  - KeyVault operations
  - KeyVault regions
- recommend a solution that includes Azure AD Managed Identities
- recommend a solution for integrating applications into Azure AD

[Design Data Storage (15-20%)](data-storage.md)
---------------------------------------------------

#### Design a solution for databases

- select an appropriate data platform based on requirements
- recommend database service tier sizing
- recommend a solution for database scalability
- recommend a solution for encrypting data at rest, data in transmission, and data in use

#### Design data integration

- recommend a data flow to meet business requirements
- recommend a solution for data integration, including Azure Data Factory, Azure Data Bricks, Azure Data Lake, Azure Synapse Analytics

#### Select an appropriate storage account

- choose between storage tiers
- recommend a storage access solution
- recommend storage management tools

[Design Business Continuity (10-15%)](business-continuity.md)
-------------------------------------------------------------

#### Design a solution for backup and recovery

- recommend a recovery solution for Azure hybrid and on-premises workloads that meets recovery objectives (RTO, RLO, RPO)
- design and Azure Site Recovery solution
  - recommend a site recovery replication policy
  - recommend a solution for site recovery capacity
  - recommend a solution for site failover and failback (planned/unplanned)
  - recommend a solution for the site recovery network
- recommend a solution for recovery in different regions
- recommend a solution for Azure Backup management
- design a solution for data archiving and retention
  - recommend storage types and methodology for data archiving
  - identify business compliance requirements for data archiving
  - identify requirements for data archiving
  - identify SLA(s) for data archiving
  - recommend a data retention policy

#### Design for high availability

- recommend a solution for application and workload redundancy, including compute, database, and storage
- recommend a solution for autoscaling
- identify resources that require high availability
- identify storage types for high availability
- recommend a solution for geo-redundancy of workloads

[Design Infrastructure (25-30%)](infrastructure.md)
---------------------------------------------------

#### Design a compute solution

- recommend a solution for compute provisioning
- determine appropriate compute technologies, including virtual machines, App Services, Service Fabric, Azure Functions, Windows Virtual Desktop, and containers
- recommend a solution for containers
  - AKS versus ACI and the configuration of each one
- recommend a solution for automating compute management

#### Design a network solution

- recommend a solution for network addressing and name resolution
- recommend a solution for network provisioning
- recommend a solution for network security
  - private endpoints
  - firewalls
  - gateways
  - etc.
- recommend a solution for network connectivity to the Internet, on-premises networks, and other Azure virtual networks
- recommend a solution for automating network management
- recommend a solution for load balancing and traffic routing

#### Design an application architecture

- recommend a microservices architecture including Event Grid, Event Hubs, Service Bus, Storage Queues, Logic Apps, Azure Functions, and webhooks
- recommend an orchestration solution for deployment of applications including ARM
  templates, Logic Apps, or Azure Functions
  - select an automation method
  - choose which resources or lifecycle steps will be automated
  - design integration with other sources such as an ITSM solution
  - recommend a solution for monitoring automation
- recommend a solution for API integration
  - design an API gateway strategy
  - determine policies for internal and external consumption of APIs
  - recommend a hosting structure for API management
  - recommend when and how to use API Keys

#### Design migrations

- assess and interpret on-premises servers, data, and applications for migration
- recommend a solution for migrating applications and VMs
- recommend a solution for migration of databases
  - determine migration scope, including redundant, related, trivial, and outdated data
