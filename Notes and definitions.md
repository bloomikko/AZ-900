# Notes and definitions
**AzCopy**
command-line utility to be used for copying blobs or files to or from your storage account

**Azure Active Directory**
cloud-based identity management solution: contains for example features of single sign-on (SSO), multi-factor authentication (MFA) and conditional access

**Azure Active Directory Domain Services**
service that provides managed domain services

**Azure Advanced Threat Protection (ATP)**
cloud-based solution for detecting and investigating security incidents across networks

**Azure Advisor**
service which recommends suggestions for example about high availability, security, performance, operational excellence and cost

**Azure Application Insights**
feature of Azure Monitor that allows the user to monitor running applications, automatically detect performance anomalies and use built-in analytics tools to see what users do on an app

**Azure App Service**
HTTP-based service for hosting web applications, REST APIs and mobile back ends

**Azure Arc**
delivers a consistent multi-cloud and on-premises management platform

**Azure Bastion**
service for connecting to virtual machine via browser and Azure portal (remote access for virtual machines)

**Azure Batch**
large-scale job scheduling and compute management

**Azure Blob Storage**
object storage solution for the cloud, optimised for massive amounts of unstructured data

**Azure Blueprints**
defined repeatable set of Azure resources which adheres to organisation’s standards, patterns and requirements

**Azure Compute**
cloud compute capacity, virtualization and scale on demand, provides infrastructure for your apps

**Azure Container Instances**
your app in a container without managing virtual machines

**Azure Content Delivery Network (CDN)**
distributed network of servers which efficiently deliver web content to users

**Azure Cost Management tool**
tool for checking Azure resource costs, creating alerts based on resource spend and creating budgets that can be used to automate management of resources

**Azure CycleCloud**
tool for orchestrating and managing High Performance Computing (HPC) environments

**Azure Data Box**
physical migration service: transferring data by Microsoft-provided physical device

**Azure DevOps**
set of collaborative development tools built for the cloud

**Azure DevTest Labs**
development and/or test environments with reusable templates and artifacts

**Azure DNS**
hosting service for Domain Name System (DNS) domains that provides name resolution by using Azure infrastructure

**Azure ExpressRoute**
connects on-premises networks to Microsoft cloud with the help of a connectivity provider (ExpressRoute Circuit)

**Azure Files**
serverless cloud file sharing system, accessible via SMB, NFS or Azure Files REST API

**Azure File Sync**
tool which lets the user to centralize file shares in Azure Files

**Azure Firewall**
threat protection service for cloud workloads running in Azure

**Azure Functions**
event-driven, readily available blocks of code, a serverless solution

**Azure Information Protection (AIP)**
controlling security properties of data, for example with classification

**Azure Key Vault**
tool for managing secrets

**Azure Kubernetes Service (AKS)**
tool for deploying and scaling containers

**Azure Load Balancer**
distributes evenly load of incoming network traffic

**Azure Log Analytics**
tool for writing log queries on the data gathered by Azure Monitor

**Azure Migrate**
service that helps migrating from an on-premises environment to the cloud

**Azure Monitor**
tool for collecting, analysing and responding to telemetry from cloud and on-premises environments, supports also autoscaling

**Azure Monitor activity log**
insights about subscription-level events, for example when resource is modified or virtual machine is started

**Azure Pipelines**
tool for continuous building, testing and deploying

**Azure Policy**
tool for evaluating resources against sets of business rules (given in JSON format) - helps you to manage and prevent IT issues with policy definitions that enforce rules and affect for your resources

**Azure Repos**
git repositories

**Azure Resource Manager (ARM) template**
block of code which defines the infrastructure and configuration for a project

**Azure Security Center**
base layer of security for monitoring security configuration and health of workloads, Cloud Security Posture Management (CSPM) solution for checking misconfigurations

**Azure Sentinel**
Security Information and Event Manager (SIEM) tool for responding to threats

**Azure Serverless**
application platform without managing the infrastructure

**Azure Service Health**
alert system for notifications of Azure service incidents and planned maintenance

**Azure Sphere**
Internet of Things (IoT) device platform

**Azure Storage Explorer**
GUI-based app where the user can manage files and blobs in Azure Storage Account

**Azure Subscriptions**
container for everything related to Azure, for example all virtual machines and databases

**Azure Virtual Machines (VMs)**
virtual machines running on Azure

**Azure VMware Solution**
runs VMware workloads in Azure with seamless integration and scalability

**Azure Virtual Desktop**
cloud-hosted version of Windows

**Azure Virtual Network (vNet)**
building block which enables private network in Azure: for example, virtual machines can securely communicate with each other, representation of own network in the cloud

**Azure VPN Gateway**
virtual network gateway which sends encrypted traffic between Azure virtual network and on-premises location over the public internet

**application security group**
configuration of application’s network security as a group of virtual machines

**availability set**
logical grouping of virtual machines, used to ensure maximum availability – each availability set is consisted by update domain and fault domain

**availability zone**
zones of data centers in a region, for example if one zone suffers from malfunction the two other zones in the region continue to work normally

**Cloud Solution Provider (CSP)**
Microsoft Partner organization which offers Azure services

**compliance manager**
template tool to assess compliance requirements

**conditional access**
allow or deny access to resources based on identity signals, such as the device being used

**elasticity**
automatic increase or decrease of resources by need

**fabric controller**
special software which runs in a server: connected to the orchestrator

**Failure Mode Analysis (FMA)**
tool to identify possible points of failure

**gateway subnet**
IP address range of virtual network where the resources and services operate

**geography**
area which contains one or more regions

**geo-redundant storage (GRS)**
replicates data in two regions in LRS (see definition) way

**geo-zone-redundant storage (GZRS)**
replicates data so that it runs ZRS (see definitions) in the primary region and LRS in the secondary region

**horizontal scaling**
if the current resources are not enough even with extra CPUs or RAM, adding more of them (for example, additional virtual machines or containers) can help

**hypervisor**
layer which enables creating virtual machines and servers

**Infrastructure as a Service (IaaS)**
cloud provider is responsible for maintaining the hardware, network connectivity and physical security, basically renting the hardware but it is up to you what you do with it

**internal load balancer**
tool for balancing traffic inside a virtual network

**Kubernetes cluster**
a set of nodes which run containerized applications

**lift-and-shift migration**
moving resources from on-premises datacenter to cloud infrastructure

**locally redundant storage (LRS)**
replicates data three times within a single data center in the primary region

**local network gateway**
object which represents the on-premises location for routing purposes: connecting on-premises to cloud

**management group**
multiple subscriptions

**management in the cloud**
the ability to manage cloud environment and resources, for example through a web portal or command line interface

**management of the cloud**
cloud management, for example automatically scaling resource deployments based on need

**Microsoft Defender for Cloud**
monitoring tool for cloud security posture management and threat protection, provides guidance and notifications aimed at strenghtening the security posture

**Microsoft Managed Desktop**
subscription-based desktop as a service (DaaS) cloud platform

**Microsoft Service Trust portal**
portal which has various content, tools and other resources about Microsoft security, privacy and compliance practices

**multi-cloud**
using multiple public cloud providers

**network security group**
tool for filtering network traffic between Azure resources in an Azure virtual network

**orchestrator**
manages everything in Azure: for example, responds to user requests and forwards them to fabric controller

**peering**
linking virtual networks together

**Platform as a Service (PaaS)**
in addition to IaaS, cloud provider is also responsible for maintaining operating systems, databases and development tools

**PowerShell CLI**
command line interface (CLI) for PowerShell

**public load balancer**
provides outbound connections for virtual machines inside a virtual network

**queue storage**
storage for large number of messages

**Role-Based Access Control (RBAC)**
tool for managing access and write rights of resources, for example one user can manage virtual machines and another can manage virtual networks

**region**
unit of datacenter locations, geography contains many regions

**resiliency**
ability of system to recover from failures and continue to function, consists of high availability and disaster recovery

**resource group**
grouping of resource: one resource can only be in one group, groups cannot be nested

**resource lock**
protection measurement for Azure resources, for example can prevent accidental user deletions and modifications

**resource tag**
metadata for Azure resources as key-value pairs

**service endpoint**  
exposes and connects Azure services to a virtual network

**Service Trust Portal**
Microsoft’s definitions how they manage and protect user data

**scalability**
ability to increase or decrease resources

**Software as a Service (SaaS)**  
most responsibility with the cloud provider – the user basically uses a fully developed application

**sovereign region**  
region which is isolated from the main instance of Azure

**subscription**  
isolated area where your Azure works – for example, you can create Azure resources here

**(virtual machine) scale set**
group of identical, load balanced virtual machines

**table storage**
service which stores non-relational structured data, providing a key/attribute store with a schemaless design

**Total Cost of Ownership (TCO) Calculator**  
tool for calculating the cost savings over time of operating a solution in Azure compared to operating in an on-premises datacenter

**vertical scaling**  
scaling virtual machine resources, for example CPUs or RAM

**virtual machine availability set**  
sets of virtual machines which stagger updates and have varied power and network connectivity, ensuring not losing all virtual machines in case of network or power failure

**virtual machine scale set**  
group of identical load-balanced virtual machines

**virtual network gateway (Azure VPN Gateway)**
tool which connects for example on-premises network to Azure virtual networks

**VPN connection point (point-to-site VPN)**
tool used to create a secure connection to a virtual network from an individual client computer

**zone-redundant storage (ZRS)**  
replicates Azure Storage data across three Azure availability zones in the primary region
