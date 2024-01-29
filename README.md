✦
AZ-900 Azure Fundamentals Study Cram - 2022 Edition!

00:06

An update to the previous study cram with over 150,000 views and a new 8 1/2 hour study course
The study course covers all the skills assessed in the exam and includes detailed lessons and handouts

✦                                                                                                                                                                                                                                                
Azure cloud provides agility, consumption-based pricing, high availability, faster recovery, and scalability.

02:36

Agility in terms of using the right service that meets specific goals and adapting to changing needs.
Consumption-based pricing allows paying only for what is used, accommodating fluctuations in usage and seasonality.
High availability ensures resilient infrastructure and mechanisms for architecting services.
Faster recovery with distributed deployments over large distances to mitigate the impact of natural disasters.

Scalability eliminates concerns about resource limitations.
✦
Azure provides different types of cloud services, including private and hybrid cloud.

08:09

Private cloud refers to running on-premises infrastructure with quotas and policies for control.
Hybrid cloud involves using both private and public cloud, allowing for variable workloads and burst usage.
Azure is an example of a public cloud service with options for operational expenditure (OpEx) payment model.

✦
Public clouds are suitable for variable workload scenarios where you pay for what you use.

10:46

The public cloud is ideal for scenarios where workloads have variable loads, such as on and off usage or rapid growth for startups.
Shared responsibilities exist between the customer and the provider in the public cloud, with different responsibilities depending on the service used.

✦
PaaS focuses on providing blocks for app development while SaaS provides business functions

16:12

PaaS allows developers to focus on their app and data, while SaaS provides ready-to-use business functions like SharePoint and email.
PaaS does not provide a business function on its own, unlike SaaS.

✦
Azure has multiple regions to meet data sovereignty requirements, ensure disaster recovery, and minimize latency.

18:37

Azure regions are set up to comply with data sovereignty regulations, allowing users to host their data in specific countries.
Having multiple regions enables disaster recovery by ensuring that services are not impacted by natural disasters.
Azure regions are strategically placed to minimize latency and provide a better user experience by placing services closer to customers.

✦
Azure uses pairings of regions for resiliency and updates

23:24

Pairings exist within the same geopolitical boundary, except for Brazil
Pairings are used by certain services in Azure for resiliency
Updates are staggered to paired regions to avoid downtime
Regions have multiple physical buildings that act as availability zones

✦
Resiliency is achieved by distributing services over multiple buildings using availability zones.

26:00

The concept of a subscription is used to expose availability zones in each region.
Availability zones can differ between different subscriptions, but within a single subscription, the same availability zones will always map to the same buildings.
Some services are inherently zone redundant, while others need to be pinned to a specific availability zone and multiple instances need to be created to achieve resiliency.
To ensure resiliency across availability zones, zonal VMs need to be created.

✦
Azure AD (AAD) is a cloud-based identity provider used by Azure and other services.

31:08

Azure AD contains users, groups, devices, and applications.
It supports various authentication protocols like OpenID Connect, SAML, WS-Fed, and OAuth2.

✦
Multifactor authentication and conditional access are important for strong authentication and authorization in Azure AD.

33:55

Multifactor authentication (MFA) provides additional confidence in user identity through the use of multiple authentication factors.
Conditional access in Azure AD allows for granular control over access requirements based on specified conditions and requirements.

✦
Azure AD enables seamless sign-on and central identity management

39:00

Azure AD synchronizes user and group identities up into Azure ID
Once synchronized, seamless sign-on allows authenticated users to access cloud applications without re-entering credentials

✦
In Azure, IT operations can be automated through self-service actions.

41:24

An IT operations person ensures compliance and requirements are met.
In the cloud, Azure provides self-service with controls and checks.

✦
Policies and initiatives provide control, compliance, and auditing capabilities.

46:29

Policies can be used to define controls for storage accounts, such as private links, customer managed keys, and limited allowed SKUs.
Initiatives are groups of policies that can be assigned at a certain scope to control and monitor compliance.

✦
Azure management groups allow for structured governance.

48:49

Management groups can be organized hierarchically based on different categories.
RBAC policy and budget settings can be applied at different levels and get inherited by lower levels.

✦
Resource groups have a common life cycle and facilitate easy management.

53:54

Resource groups are not a boundary of use and can be connected to different components
Resource groups help in implementing role-based access control policies and budgets

✦
Azure Resource Manager is how we interact with Azure and it is responsible for managing resources

56:17

Azure is made up of resources that are defined in resource providers
Different resource providers offer various resource types, such as virtual machines, disks, and scale sets

✦
Different ways to access Azure resources

1:01:23

Azure Portal is great for viewing and exploring resources
Cloud Shell provides command line access to Azure CLI and PowerShell
Mobile app for monitoring resource status and basic management
PowerShell Azure module for automation from command line

✦
Azure provides powerful command line interfaces for automation and management.

1:03:38

The Azure PowerShell module is great for automation with its rich commands and capabilities.
The Azure CLI is a bash-based tool that can be run on Windows using CMD, providing similar capabilities.

✦
Azure Resource Manager templates are powerful and allow parallel creation of resources.

1:08:16

Azure Resource Manager templates enable parallel creation of resources, eliminating the need to wait for each resource to be created one by one.
Declarative nature of ARM templates makes it easy to compare with existing resources and work with other tools like DevOps, GitHub repo, and Azure DevOps repos.
Bicep is a new technology that transpiles into an ARM JSON template, providing a more human-friendly way to create declarative templates.

✦
Resource locks in Azure provide governance control to prevent accidental changes or deletions.

1:10:26

Resource locks can be applied at different levels such as subscription, resource group, or individual resource.
Resource locks can be set to prevent changes or deletions, or to allow read-only access.

✦
Azure blueprint allows defining and assigning a set of artifacts to a subscription for streamlined resource management

1:14:57

Tagging metadata in billing is useful for filtering and organizing bills
Azure blueprint enables defining resource groups, ARM templates, role-based access control, and other resources for easy configuration deployment

✦
Important things to know about assignments in Azure

1:17:33

Assignments maintain the connection between blueprints and updates
Assignments apply at the Azure Resource Manager level and do not impact the data plane

✦
Different types of virtual machines in Azure have different ratios of CPU to memory.

1:22:17

For every two CPUs, we get 4 gigabytes of memory, resulting in a 1 to 2 ratio.
The ratio varies depending on the type of virtual machine, with general purpose having a ratio of 2 to 8 (1 to 4) and memory optimized having a ratio of 2 to 16 (1 to 8).

✦
Auto scale allows changing the number of virtual machines based on workload

1:24:35

Virtual machine scale sets create and delete virtual machines based on set conditions
Azure Dedicated Host provides the option to have exclusive use of a certain box

✦
Containers are lightweight and quickly deployable, while VMs require more resources and time to start.

1:29:21

Containers virtualize software and create isolated sandboxes for running applications.
Containers share a container host, resulting in low overhead and fast deployment, but multi-tenant scenarios may require separate VMs.

✦
Azure provides options for running containers

1:31:49

Azure Container Instances allow running individual containers or container groups with automatic isolation
Azure Kubernetes Service (AKS) provides a fully managed environment for deploying and managing containers using Kubernetes

✦
App service and Azure functions are key offerings for web app development on Azure.

1:36:35

App service allows easy web application deployment with minimal maintenance overhead.
Azure functions are designed for running short-lived code tasks in different languages.

✦
Azure Functions and Logic Apps are two serverless options in Azure

1:38:59

Azure Functions allow running code in a serverless manner, either in an app service plan or consumption mode
Logic Apps provide a graphical canvas where connectors can be used to create workflows without coding

✦
Azure Key Vault enables secure storage and access of sensitive information.

1:43:34

It provides a hardware security module backed service for storing secrets, keys, and certificates.
Access to the stored entities can be controlled through access policies or role-based access control (RBAC).

✦
Virtual network in Azure is defined by IPV 4 address ranges and can optionally include IPV 6 ranges.

1:45:53

Virtual networks cannot span regions or subscriptions.
When choosing an IP range for a virtual network, it should not conflict with other virtual networks or networks in other clouds/on-premises.

✦
Azure provides options for network connectivity through route-based and express route gateways.

1:51:12

Route-based connectivity supports multiple connections, point-to-site VPN, and encryption over the Internet.
Express route connectivity offers a private connection, either through colocation, MPLS, or layer 2 connections, with different traffic types like private peering and Microsoft peering.

✦
Network Security Groups (NSGs) are used to control traffic flow in Azure.

1:53:50

NSGs are built around properties like source and destination IP or port, protocol, name, description, and priority.
Rules based on IP addresses can be created and linked to subnets for traffic control. Service tags and application security groups (ASGs) provide additional options for traffic control. Azure Firewall is another service for more advanced control.

✦
Service endpoints and private endpoints in Azure networking.

1:58:53

Service endpoints enable better routes and firewall control for services within a specific subnet.
Private endpoints provide an IP address in a subnet for accessing services from other networks and offer more control over traffic.

✦
Azure offers both a basic and standard offering for DDoS protection service.

2:01:21

The basic offering redirects traffic at a huge scale, while the standard offering provides additional features like availability guarantee, cost protection policies, and machine learning for understanding normal patterns.
For applications that require tuned DDoS protection, the DDoS standard offering is recommended.

✦
Different resiliency options and performance vary depending on the type of storage account.

2:06:30

For certain services, there is a read access variant (RA) like GRS or RA-GZRS which allows reading from a secondary pair.
Not all services support RA, but it is available for some of them.
The available resiliency options also depend on the region's support for availability zones.
Standard storage accounts have options for LRS, ZRS, and GRS.
Premium storage accounts may not have the Geo redundant (RA-GZRS) and ZRS options, depending on the type.
When creating a storage account, the performance and resiliency options can be selected based on the type of account.
Premium storage accounts offer different types of services such as BLOB, block blob, and page blob.
Page blob is suitable for reading and writing over random areas, similar to an operating system disk.
Append blob is another type available for storage accounts.

✦
Azure Blob storage has flat structure with virtual directories, but Azure Data Lake Storage Gen 2 provides a hierarchical file system.

2:09:06

Azure Blob storage stores files in containers without true folders, but virtual directories can be created using folder names.
Azure Data Lake Storage Gen 2 adds capabilities like POSIX style ACLs and a hierarchical file system, allowing for true folders.

✦
Different storage tiers available in Azure with varying cost and accessibility

2:14:22

The storage tiers in Azure include premium, standard (with hot, cool, and archive options), and offline archive.
Lifecycle management can automate the movement of data between different tiers based on specified rules.

✦
Different types of database services are available in Azure, including Azure SQL Database and Azure SQL Managed Instance.

2:16:41

Azure SQL Database is a fully managed PaaS solution that offers different SKUs and capabilities like hyperscale, serverless, standard, and business critical.
Azure SQL Managed Instance is designed for compatibility and provides more features compared to Azure SQL Database, such as common language runtime and cross-database queries.

✦
Azure Marketplace provides various types of solutions for networking and resources

2:21:56

Cosmos DB allows you to choose the consistency level for handling data synchronization across regions
Azure Marketplace offers pre-configured VMs with different types of software and licensing options

✦
Azure IoT hub is a service that allows devices to register and communicate with each other.

2:24:17

Azure IoT hub enables devices to send and receive data, receive firmware updates, and software updates.
It provides a device twin that represents the device, allowing information retrieval and instruction sending.

✦
Azure data services enable secure communication and data transformation.

2:29:41

Secure communication is ensured by verifying identity and preventing unauthorized access.
Azure data services involve extracting, transforming, and loading data from various sources to achieve desired outcomes.

✦
Azure offers various services for data transformation and analytics.

2:32:17

Hdinsight is a comprehensive service that utilizes multiple open-source frameworks like Hadoop, Storm, Spark, and more for different types of data processing.
Databricks, built on Apache Spark, is a fully managed offering that simplifies data transformation, analytics, and uses VMs and blobs for storage.
Azure Synapse Analytics brings everything together into one workspace, providing orchestration, a data warehouse, and an Apache Spark transformation service.

✦
Azure cognitive services, Azure bot service, and DevOps are key topics in the video.

2:37:43

Azure cognitive services include prebuilt models for image and video analysis.
Azure bot service enables interactions with people, supports chatbots and voice integration.
DevOps is a process for working together, utilizing tools like continuous integration and deployment.

✦
Azure DevOps provides tooling sets for DevOps, including repos, boards, pipelines, artifacts, and test plans.

2:40:10

Azure DevOps has repos for version control, supporting both git and team Foundation version control.
Azure DevOps offers boards for organizing and tracking projects, including kanban boards with swim lanes and work in progress limits.
Azure DevOps provides pipelines for continuous integration, continuous delivery, and continuous deployment.
Azure DevOps includes artifacts for storing built assets or libraries.
Azure DevOps has test plans for managing testing activities.
GitHub, which offers repo functionality with enhanced security features, is now receiving more investment from Microsoft.

✦
Understanding the factors that impact the cost of Azure resources.

2:44:53

Resource type, such as storage account or virtual machine, impacts cost.
The cost can be influenced by factors like location, metering, provisioning, autoscale, workload, storage, interactions, transactions, and licensing.

✦
Optimizing resource usage and costs in Azure

2:47:27

Ensure resource allocation matches workload for efficiency
Utilize autoscale and deallocation to maximize resource utilization
Use resource groups to easily organize and delete unnecessary resources
Consider using life cycle management and moving to PaaS services for cost optimization
Implement tagging and Azure Advisor for better resource management

✦
Using Azure Spot VMs to save costs and maximize server utilization

2:52:29

Azure spot instances allow users to create VMs at a lower price, with the understanding that they may be taken off if a regular pay-as-you-go customer needs the resources
The spot price may vary depending on spare capacity, but it can provide significant cost savings for workloads that can be stopped and resumed

✦
The pricing calculator helps estimate the costs of different Azure resources.

2:54:44

By inputting the type of service, quantity, and duration, the calculator provides the price.
Reserved instances and Azure hybrid benefit can lower the cost, especially for Windows VMs.

✦
Azure Advisor provides recommendations for optimizing Azure resources and services.

2:59:29

It offers guidance on shutting down or resizing virtual machines, using burstable VMs, and optimizing Azure databases.
Azure Monitor allows for monitoring and staying up to date on the entire environment, including different resources and their metrics and logs.

✦
Azure provides log analytics workspace, storage account, and event hub for data storage and analysis.

3:02:19

Log analytics workspace is a log ingestion and analysis service in Azure.
Storage account is useful for long-term storage but not for interaction.
Event hub enables publishing and subscribing to events, making it useful for external systems.
Azure monitor allows creating alert and action rules based on signals from various sources.

✦
Azure services have Service Level Agreements (SLAs) that define their availability.

3:07:28

SLAs are typically expressed in terms of a number of nines, representing the percentage of uptime per week.
SLAs can vary based on the configuration of the environment, such as the use of availability zones.

✦
Azure provides different levels of SLA depending on the deployment configuration.

3:10:06

Azure offers a higher SLA (Service Level Agreement) if services are deployed across multiple availability zones.
If services are within the same availability zone but spread across different racks in the same data center, a lower SLA is provided.
The type of disk used also affects the SLA, with premium SSD offering a higher SLA than standard SSD or hard disk drives.
The SLA may vary depending on the distribution and configuration of services.
The Azure status page provides an overview of service statuses across different regions.

✦
Documentation and compliance offerings are important for understanding Azure's security, privacy, and compliance features.

3:15:05

Explore different documents such as privacy statements and online services terms to understand Microsoft's data handling policies.
Azure offers a wide range of compliance offerings that address security, privacy, and data protection.
Visit the trust center for detailed information on security, privacy, and compliance.
Check the compliance offerings section in the trust center for a comprehensive list of all compliance offerings.
Consider security aspects specific to the cloud and on-premises environments.

✦
Implement defense in depth with layers of security

3:17:40

Focus on physical security, identity and access management, perimeter protection, network security, compute security, application layer security, and data protection
Adopt the CIA (Confidentiality, Integrity, Availability) principles for enhanced security

✦
Azure Sentinel is a security information and event management tool

3:22:34

It recognizes patterns in logs to identify potential threats
It can automate responses to security incidents

✦
Tips for passing the exam

3:24:49

Eliminate obvious options and make educated guesses
If you don't pass the first time, identify your areas of weakness and study more
