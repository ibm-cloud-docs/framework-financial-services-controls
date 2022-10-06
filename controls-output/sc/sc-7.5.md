---

copyright:
  years: 2020, 2022

lastupdated: "2022-10-06"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# SC-7 (5) - Deny by Default / Allow by Exception
{: #sc-7.5}

## Control requirements
{: #control-requirements}

SC-7 (5) - 0
    : The information system at managed interfaces denies network communications traffic by default and allows network communications traffic by exception (i.e., deny all, permit by exception).

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Accessing the public internet](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-to-internet)
- [Connecting application provider to the management VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-management)
- [Connectivity to {{site.data.keyword.cloud_notm}} services with private endpoints](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-to-ibm-services)
- [Consumer connectivity to workload VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-workload)
- [Creating and connecting the management and workload VPCs](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-create-vpcs)
- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)
- [Working with {{site.data.keyword.openshiftlong_notm}}](/docs/framework-financial-services?topic=framework-financial-services-shared-containers-openshift)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.6.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- 3000020: Check whether authorized IP ranges are configured for the account 
- 3000105: Check whether Cloud Object Storage is accessible only by using private endpoints 
- 3000107: Check whether Cloud Object Storage network access is restricted to a specific IP range 
- 3000306: Check whether Event Streams is accessible only by using private endpoints 
- 3000307: Check whether Event Streams network access is restricted to a specific IP range 
- 3000406: Check whether Virtual Private Cloud (VPC) has no rules in the default security group 
- 3000412: Check whether all virtual server instances have at least one Virtual Private Cloud (VPC) security group attached 
- 3000413: Check whether all network interfaces of a virtual server instance have at least one Virtual Private Cloud (VPC) security group attached 
- 3000418: Check whether account has at least one VPN or Direct Link configured 
- 3000427: Check whether Application Load Balancer for VPC has public access disabled 
- 3000442: Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to RDP port 
- 3000444: Check whether Security Groups for VPC contains no outbound rules in security groups that specify source IP 8.8.8.8/32 to DNS port 
- 3000447: Check whether Virtual Private Cloud (VPC) classic access is disabled 
- 3000448: Check whether Virtual Private Cloud (VPC) has no public gateways attached at the time of provisioning 
- 3000449: Check whether Virtual Private Cloud (VPC) has no public gateways attached 
- 3000451: Check whether Virtual Private Cloud (VPC) network access control lists should allow ingress to any ports that are open only to permitted IPs 
- 3000452: Check whether Virtual Private Cloud (VPC) network access control lists should allow egress to any ports that are open only to permitted IPs 
- 3000453: Check whether Virtual Servers for VPC instance has the minimum # interfaces 
- 3000454: Check whether Virtual Servers for VPC instance doesn't have a floating IP 
- 3000455: Check whether Virtual Servers for VPC instance has all interfaces with IP-spoofing disabled 
- 3000467: Check whether Virtual Private Cloud (VPC) has no subnet with public gateway attached 
- 3000468: Check whether Virtual Private Cloud (VPC) is configured with public gateways that are provisionable only within permitted zones 
- 3000469: Check whether Application Load Balancer for VPC is configured with at least one VPC security group 
- 3000475: Check whether Virtual Private Cloud (VPC) security groups have inbound ports that are open only to permitted IPs 
- 3000476: Check whether Virtual Private Cloud (VPC) security groups have outbound ports that are open only to permitted IPs 
- 3000478: Check whether a security group in Virtual Private Cloud, other than the default, is attached to all virtual private endpoints 
- 3000510: Check whether Hyper Protect Crypto Services is accessible only through private endpoints 
- 3000526: Check whether Hyper Protect DBaaS for MongoDB is accessible only using private endpoints 
- 3000534: Check whether Hyper Protect DBaaS for PostgreSQL is accessible only using private endpoints 
- 3000625: Check whether Container Registry image pushes and pulls take place only over private endpoints 
- 3000704: Check whether App ID redirect URIs are not using localhost or 127.0.0.1 
- 3000705: Check whether App ID redirect URIs are not using wildcards (*) 
- 3000902: Check whether OpenShift clusters are accessible only by using private endpoints 

## NIST supplemental guidance
{: #nist-supplemental-guidance}

This control enhancement applies to both inbound and outbound network communications traffic. A deny-all, permit-by-exception network communications traffic policy ensures that only those connections which are essential and approved are allowed.





