---

copyright:
  years: 2020, 2025

lastupdated: "2025-02-16"

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
- [Connectivity to {{site.data.keyword.cloud_notm}} services with private endpoints](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-to-services)
- [Consumer connectivity to workload VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-workload)
- [Creating and connecting the management and workload VPCs](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-create-vpcs)
- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)
- [Working with {{site.data.keyword.openshiftlong_notm}}](/docs/framework-financial-services?topic=framework-financial-services-shared-containers-openshift)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- Check whether Security Groups for VPC contains no outbound rules in security groups that specify source IP 8.8.8.8/32 to DNS port
- Check whether Event Streams network access is restricted to a specific IP range
- Check whether Virtual Servers for VPC instance doesn't have a floating IP
- Check whether Application Load Balancer for VPC has public access disabled
- Check whether OpenShift clusters are accessible only by using private endpoints
- Check whether authorized IP ranges are configured for the account
- Check whether Virtual Private Cloud (VPC) security groups have inbound ports that are open only to permitted IP addresses
- Check whether Hyper Protect DBaaS for MongoDB is accessible only using private endpoints
- Check whether Event Streams is accessible only by using private endpoints
- Check whether Hyper Protect DBaaS for PostgreSQL is accessible only using private endpoints
- Check whether Virtual Private Cloud (VPC) has no public gateways attached
- Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to any port
- Check whether all virtual server instances have at least one Virtual Private Cloud (VPC) security group attached
- Check whether Virtual Private Cloud (VPC) has no public gateways attached at the time of provisioning
- Check whether App ID redirect URIs are not using wildcards (*)
- Check whether Virtual Servers for VPC instance has all interfaces with IP-spoofing disabled
- Check whether account has at least one VPN or Direct Link configured
- Check whether Virtual Private Cloud (VPC) classic access is disabled
- Check whether Virtual Private Cloud (VPC) has no rules in the default security group
- Check whether all network interfaces of a virtual server instance have at least one Virtual Private Cloud (VPC) security group attached
- Check whether Container Registry image pushes and pulls take place only over private endpoints
- Check whether Virtual Servers for VPC instance has the minimum # interfaces
- Check whether Virtual Private Cloud (VPC) has no subnet with public gateway attached
- Check whether Hyper Protect Crypto Services is accessible only through private endpoints
- Check whether Virtual Private Cloud (VPC) security groups have outbound ports that are open only to permitted IP addresses
- Check whether Virtual Private Cloud (VPC) is configured with public gateways that are provisionable only within permitted zones
- Check whether a security group other than the default for Virtual Private Cloud is attached to all endpoints
- Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to RDP port
- Check whether App ID redirect URIs are not using localhost or 127.0.0.1
- Check whether Cloud Object Storage is accessible only by using private endpoints
- Check whether Virtual Private Cloud (VPC) network access control lists don't allow egress from 0.0.0.0/0 to any port

## NIST supplemental guidance
{: #nist-supplemental-guidance}

This control enhancement applies to both inbound and outbound network communications traffic. A deny-all, permit-by-exception network communications traffic policy ensures that only those connections which are essential and approved are allowed.
