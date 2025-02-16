---

copyright:
  years: 2020, 2025

lastupdated: "2025-02-16"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}


# SC-7 - Boundary Protection
{: #sc-7}

## Control requirements
{: #control-requirements}

The information system:

SC-7 (a)
    : Monitors and controls communications at the external boundary of the system and at key internal boundaries within the system;

SC-7 (b)
    : Implements subnetworks for publicly accessible system components that are _[Selection: physically; logically]_ separated from internal organizational networks; and

SC-7 (c)
    : Connects to external networks or information systems only through managed interfaces consisting of boundary protection devices arranged in accordance with an organizational security architecture.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- The organization "service delivery" and "corporate" environments must be maintained as separate environments. That is, clear physical and/or logical boundaries separating the two environments must exist.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Accessing the public internet](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-to-internet)
- [Connecting application provider to the management VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-management)
- [Connectivity to {{site.data.keyword.cloud_notm}} services with private endpoints](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-to-services)
- [Consumer connectivity to workload VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-workload)
- [Creating and connecting the management and workload VPCs](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-create-vpcs)
- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Rules |
|----------------|-------|
| SC-7 (a) | - Check whether Security Groups for VPC contains no outbound rules in security groups that specify source IP 8.8.8.8/32 to DNS port \n - Check whether Event Streams network access is restricted to a specific IP range \n - Check whether Virtual Servers for VPC instance doesn't have a floating IP \n - Check whether Application Load Balancer for VPC has public access disabled \n - Check whether Flow Logs for VPC are enabled \n - Check whether OpenShift clusters are accessible only by using private endpoints \n - Check whether authorized IP ranges are configured for the account \n - Check whether Virtual Private Cloud (VPC) security groups have inbound ports that are open only to permitted IP addresses \n - Check whether Hyper Protect DBaaS for MongoDB is accessible only using private endpoints \n - Check whether Event Streams is accessible only by using private endpoints \n - Check whether Hyper Protect DBaaS for PostgreSQL is accessible only using private endpoints \n - Check whether Virtual Private Cloud (VPC) has no public gateways attached \n - Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to any port \n - Check whether all virtual server instances have at least one Virtual Private Cloud (VPC) security group attached \n - Check whether Virtual Private Cloud (VPC) has no public gateways attached at the time of provisioning \n - Check whether App ID redirect URIs are not using wildcards (*) \n - Check whether Virtual Servers for VPC instance has all interfaces with IP-spoofing disabled \n - Check whether Cloud Object Storage network access is restricted to a specific IP range \n - Check whether account has at least one VPN or Direct Link configured \n - Check whether Virtual Private Cloud (VPC) classic access is disabled \n - Check whether Virtual Private Cloud (VPC) has no rules in the default security group \n - Check whether all network interfaces of a virtual server instance have at least one Virtual Private Cloud (VPC) security group attached \n - Check whether Container Registry image pushes and pulls take place only over private endpoints \n - Check whether Virtual Servers for VPC instance has the minimum # interfaces \n - Check whether Virtual Private Cloud (VPC) has no subnet with public gateway attached \n - Check whether Hyper Protect Crypto Services is accessible only through private endpoints \n - Check whether Virtual Private Cloud (VPC) security groups have outbound ports that are open only to permitted IP addresses \n - Check whether Virtual Private Cloud (VPC) is configured with public gateways that are provisionable only within permitted zones \n - Check whether Cloud Object Storage public access is disabled in IAM settings (not applicable to ACLs managed using S3 APIs) \n - Check whether a security group other than the default for Virtual Private Cloud is attached to all endpoints \n - Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to RDP port \n - Check whether App ID redirect URIs are not using localhost or 127.0.0.1 \n - Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to SSH port \n - Check whether Virtual Private Cloud (VPC) network access control lists don't allow egress from 0.0.0.0/0 to any port |
| SC-7 (b) | - Check whether Security Groups for VPC contains no outbound rules in security groups that specify source IP 8.8.8.8/32 to DNS port \n - Check whether Event Streams network access is restricted to a specific IP range \n - Check whether Virtual Servers for VPC instance doesn't have a floating IP \n - Check whether OpenShift clusters are accessible only by using private endpoints \n - Check whether Hyper Protect DBaaS for MongoDB is accessible only using private endpoints \n - Check whether Event Streams is accessible only by using private endpoints \n - Check whether Hyper Protect DBaaS for PostgreSQL is accessible only using private endpoints \n - Check whether Virtual Private Cloud (VPC) has no public gateways attached \n - Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to any port \n - Check whether all virtual server instances have at least one Virtual Private Cloud (VPC) security group attached \n - Check whether Virtual Private Cloud (VPC) has no public gateways attached at the time of provisioning \n - Check whether App ID redirect URIs are not using wildcards (*) \n - Check whether Virtual Servers for VPC instance has all interfaces with IP-spoofing disabled \n - Check whether Cloud Object Storage network access is restricted to a specific IP range \n - Check whether account has at least one VPN or Direct Link configured \n - Check whether Virtual Private Cloud (VPC) classic access is disabled \n - Check whether Virtual Private Cloud (VPC) has no rules in the default security group \n - Check whether all network interfaces of a virtual server instance have at least one Virtual Private Cloud (VPC) security group attached \n - Check whether Container Registry image pushes and pulls take place only over private endpoints \n - Check whether Virtual Servers for VPC instance has the minimum # interfaces \n - Check whether Hyper Protect Crypto Services is accessible only through private endpoints \n - Check whether Cloud Object Storage public access is disabled in IAM settings (not applicable to ACLs managed using S3 APIs) \n - Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to RDP port \n - Check whether App ID redirect URIs are not using localhost or 127.0.0.1 \n - Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to SSH port |
| SC-7 (c) | - Check whether Virtual Private Cloud (VPC) security groups have inbound ports that are open only to permitted IP addresses \n - Check whether Virtual Private Cloud (VPC) has no public gateways attached \n - Check whether all virtual server instances have at least one Virtual Private Cloud (VPC) security group attached \n - Check whether Virtual Private Cloud (VPC) has no public gateways attached at the time of provisioning \n - Check whether account has at least one VPN or Direct Link configured \n - Check whether Virtual Private Cloud (VPC) classic access is disabled \n - Check whether Virtual Private Cloud (VPC) has no rules in the default security group \n - Check whether all network interfaces of a virtual server instance have at least one Virtual Private Cloud (VPC) security group attached \n - Check whether Virtual Servers for VPC instance has the minimum # interfaces \n - Check whether Virtual Private Cloud (VPC) has no subnet with public gateway attached \n - Check whether Virtual Private Cloud (VPC) security groups have outbound ports that are open only to permitted IP addresses \n - Check whether Virtual Private Cloud (VPC) is configured with public gateways that are provisionable only within permitted zones \n - Check whether Virtual Private Cloud (VPC) network access control lists don't allow egress from 0.0.0.0/0 to any port |
{: caption="Rules for SC-7 in IBM Cloud for Financial Services v1.2.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Managed interfaces include, for example, gateways, routers, firewalls, guards, network-based malicious code analysis and virtualization systems, or encrypted tunnels implemented within a security architecture (e.g., routers protecting firewalls or application gateways residing on protected subnetworks). Subnetworks that are physically or logically separated from internal networks are referred to as demilitarized zones or DMZs. Restricting or prohibiting interfaces within organizational information systems includes, for example, restricting external web traffic to designated web servers within managed interfaces and prohibiting external traffic that appears to be spoofing internal addresses. Organizations consider the shared nature of commercial telecommunications services in the implementation of security controls associated with the use of such services. Commercial telecommunications services are commonly based on network components and consolidated management systems shared by all attached commercial customers, and may also include third party-provided access lines and other service elements. Such transmission services may represent sources of increased risk despite contract security provisions.
