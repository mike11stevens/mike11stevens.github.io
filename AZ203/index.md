---
layout: default
course: AZ-203
image: \assets\images\Associate.png
description: Collection of curated links, training resources, and other stuff for AZ-203 Developing Solutions for Microsoft Azure exam and Microsoft Certified Azure Developer Associate.
---

![AZ-203](\assets\images\Associate.png)

# AZ-203 | Developing Solutions for Microsoft Azure 

<hr class="thin" />

* [Certification](#certification)
* [Learning Path](#learning-path)
* [Training Resources](#training-resources)
* [Objectives](#objectives)
* [Parking Lot](#parking-lot)

<hr class="thin" />

## Certification
<a name="certification"></a>

### [Exam AZ-203: Developing Solutions for Microsoft Azure](https://www.microsoft.com/en-us/learning/exam-AZ-203.aspx)

This exam measures your ability to accomplish the following technical tasks: develop Azure Infrastructure as a Service compute solutions; develop Azure Platform as a Service compute solutions; develop for Azure storage; implement Azure security; monitor, troubleshoot, and optimize solutions; and connect to and consume Azure services and third-party services.

## Training Resources
<a name="training-resources"></a>

* [MicrosoftLearning/AZ-203-DevelopingSolutionsforMicrosoftAzure](https://github.com/MicrosoftLearning/AZ-203-DevelopingSolutionsforMicrosoftAzure){:target="_blank"} (GitHub)

## Learning Path
<a name="learning-path"></a>

### [Azure Developer]('https://docs.microsoft.com/en-us/learn/browse/?resource_type=learning%20path&roles=developer&products=azure'){:target="_blank"}
* [Azure Fundamentals](https://docs.microsoft.com/en-us/learn/paths/azure-fundamentals){:target="_blank"}
* [Mange Resources in Azure](https://docs.microsoft.com/en-us/learn/paths/manage-resources-in-azure){:target="_blank"}
* [Create serverless applications](https://docs.microsoft.com/en-us/learn/paths/create-serverless-applications/){:target="_blank"}
* [Deploy a website with Azure virtual machines](https://docs.microsoft.com/en-us/learn/paths/deploy-a-website-with-azure-virtual-machines){:target="_blank"}
* [Deploy a website with Azure App Services](https://docs.microsoft.com/en-us/learn/paths/deploy-a-website-with-azure-app-service){:target="_blank"}
* [Secure your cloud data](https://docs.microsoft.com/en-us/learn/paths/secure-your-cloud-data/){:target="_blank"}
* [Store data in Azure](https://docs.microsoft.com/en-us/learn/paths/store-data-in-azure/){:target="_blank"}
* [Work with realtional data in Azure](https://docs.microsoft.com/en-us/learn/paths/work-with-relational-data-in-azure/){:target="_blank"}
* [Work with NoSQL data in Azure CosmosBD](https://docs.microsoft.com/en-us/learn/paths/work-with-nosql-data-in-azure-cosmos-db/){:target="_blank"}
* [Build automated workflows to integrate data and apps with Azure Logic Apps](https://docs.microsoft.com/en-us/learn/paths/build-workflows-with-logic-apps/){:target="_blank"}
* [Connect your services together](https://docs.microsoft.com/en-us/learn/paths/connect-your-services-together/){:target="_blank"}

## Objectives
<a name="objectives"></a>

* [Develop Azure Infrastructure as a Service compute solutions (10-15%)](#objective-1)
* [Develop Azure Platform as a Service compute solutions (20-25%)](#objective-2)
* [Develop for Azure storage (15-20%)](#objective-3)
* [Implement Azure security (10-15%)](#objective-4)
* [Monitor, troubleshoot, and optimize solutions (10-15%)](#objective-5)
* [Connect to and consume Azure services and third-party services (20-25%)](#objective-6)

<a name="objective-1"></a>
### Develop Azure Infrastructure as a Service compute solutions (10-15%)

* [Develop Azure Infrastructure as a Service compute solutions (edX course)](https://openedx.microsoft.com/courses/course-v1:Microsoft+AZ-203.1+2019_T2/course/){:target="_blank"}

#### Implement solutions that use virtual machines (VM)
* #### provision VMs
* #### create ARM templates
* #### configure Azure Disk Encryption for VMs

#### Implement batch jobs by using Azure Batch Services
* #### manage batch jobs by using Batch Service API
* #### run a batch job by using Azure CLI, Azure portal, and other tools
* #### write code to run an Azure Batch Services batch job

#### Create containerized solutions
* #### create an Azure Managed Kubernetes Service (AKS) cluster
* #### create container images for solutions
* #### publish an image to the Azure Container Registry
* #### run containers by using Azure Container Instance or AKS

<a name="objective-2"></a>
### Develop Azure Platform as a Service compute solutions (20-25%)

#### Create Azure App Service Web Apps
* #### create an Azure App Service Web App
* #### create an Azure App Service background task by using WebJobs
* #### enable diagnostics logging

#### Create Azure App Service mobile apps
* #### add push notifications for mobile apps
* #### enable offline sync for mobile app
* #### implement a remote instrumentation strategy for mobile devices

#### Create Azure App Service API apps
* #### create an Azure App Service API app
* #### create documentation for the API by using open source and other tools

#### Implement Azure functions
* #### implement input and output bindings for a function
* #### implement function triggers by using data operations, timers, and webhooks
* #### implement Azure Durable Functions
* #### create Azure Function apps by using Visual Studio

<a name="objective-3"></a>
### Develop for Azure storage (15-20%)

#### Develop solutions that use storage tables
* #### design and implement policies for tables
* #### query table storage by using code
* #### implement partitioning schemes

#### Develop solutions that use Cosmos DB storage
* #### create, read, update, and delete data by using appropriate APIs
* #### implement partitioning schemes
* #### set the appropriate consistency level for operations

#### Develop solutions that use a relational database
* #### provision and configure relational databases
* #### configure elastic pools for Azure SQL Database
* #### create, read, update, and delete data tables by using code

#### Develop solutions that use blob storage
* #### move items in blob storage between storage accounts or containers
* #### set and retrieve properties and metadata
* #### implement blob leasing
* #### implement data archiving and retention

<a name="objective-4"></a>
### Implement Azure security (10-15%)

#### Implement authentication
* #### implement authentication by using certificates, forms-based authentication, or tokens
* #### implement multi-factor or Windows authentication by using Azure AD
* #### implement OAuth2 authentication
* #### implement Managed Service Identity (MSI)/Service Principal authentication

#### Implement access control
* #### implement CBAC (Claims-Based Access Control) authorization
* #### implement RBAC (Role-Based Access Control) authorization
* #### create shared access signatures

#### Implement secure data solutions
* #### encrypt and decrypt data at rest and in transit
* #### create, read, update, and delete keys, secrets, and certificates by using the KeyVault API

<a name="objective-5"></a>
### Monitor, troubleshoot, and optimize solutions (10-15%)

#### Develop code to support scalability of apps and services
* #### implement autoscaling rules and patterns (schedule, operational/system metrics, singleton applications)
* #### implement code that handles transient faults

#### Integrate caching and content delivery within solutions
* #### store and retrieve data in Azure Redis cache
* #### develop code to implement CDNs in solutions
* #### invalidate cache content (CDN or Redis)

#### Instrument solutions to support monitoring and logging
* #### configure instrumentation in an app or service by using Application Insights
* #### analyze and troubleshoot solutions by using Azure Monitor
* #### implement Application Insights Web Test and Alerts

<a name="objective-6"></a>
### Connect to and consume Azure services and third-party services (20-25%)

#### Develop an App Service Logic App
* #### create a Logic App
* #### create a custom connector for Logic Apps
* #### create a custom template for Logic Apps

#### Integrate Azure Search within solutions
* #### create an Azure Search index
* #### import searchable data
* #### query the Azure Search index

#### Establish API Gateways
* #### create an APIM instance
* #### configure authentication for APIs
* #### define policies for APIs

#### Develop event-based solutions
* #### implement solutions that use Azure Event Grid
* #### implement solutions that use Azure Notification Hubs
* #### implement solutions that use Azure Event Hub

#### Develop message-based solutions
* #### implement solutions that use Azure Service Bus
* #### implement solutions that use Azure Queue Storage queues

<br /><br />

## Parking Lot
<a name="parking-lot"></a>

<!-- Parking Lot -->
{% include parkinglot.html %}
<!-- Parking Lot -->