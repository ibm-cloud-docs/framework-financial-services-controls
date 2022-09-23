---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-23"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# SC-7 - Boundary Protection
{: #sc-7}

## Requirements
{: #requirements}

The information system:

(a) Monitors and controls communications at the external boundary of the system and at key internal boundaries within the system;

(b) Implements subnetworks for publicly accessible system components that are [physically; logically] separated from internal organizational networks; and

(c) Connects to external networks or information systems only through managed interfaces consisting of boundary protection devices arranged in accordance with an organizational security architecture.

## Additional IBM Cloud for Financial Services specifications
{: #additional-fs-cloud-specifications}

The organization &#34;service delivery&#34; and &#34;corporate&#34; environments must be maintained as separate environments. That is, clear physical and/or logical boundaries separating the two environments must exist.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement | Goals |
|-------------|-------|
| Part a | - 3000020: Check whether authorized IP ranges are configured for the account \n - 3000022: Check whether Cloud Object Storage public access is disabled in IAM settings (not applicable to ACLs managed using S3 APIs) \n - 3000105: Check whether Cloud Object Storage is accessible only by using private endpoints \n - 3000107: Check whether Cloud Object Storage network access is restricted to a specific IP range \n - 3000306: Check whether Event Streams is accessible only by using private endpoints \n - 3000307: Check whether Event Streams network access is restricted to a specific IP range \n - 3000406: Check whether Virtual Private Cloud (VPC) has no rules in the default security group \n - 3000408: Check whether Flow Logs for VPC are enabled \n - 3000412: Check whether all virtual server instances have at least one Virtual Private Cloud (VPC) security group attached \n - 3000413: Check whether all network interfaces of a virtual server instance have at least one Virtual Private Cloud (VPC) security group attached \n - 3000418: Check whether account has at least one VPN or Direct Link configured \n - 3000427: Check whether Application Load Balancer for VPC has public access disabled \n - 3000444: Check whether Security Groups for VPC contains no outbound rules in security groups that specify source IP 8.8.8.8/32 to DNS port \n - 3000447: Check whether Virtual Private Cloud (VPC) classic access is disabled \n - 3000448: Check whether Virtual Private Cloud (VPC) has no public gateways attached at the time of provisioning \n - 3000449: Check whether Virtual Private Cloud (VPC) has no public gateways attached \n - 3000451: Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to any port \n - 3000452: Check whether Virtual Private Cloud (VPC) network access control lists don't allow egress from 0.0.0.0/0 to any port \n - 3000453: Check whether Virtual Servers for VPC instance has the minimum # interfaces \n - 3000454: Check whether Virtual Servers for VPC instance doesn't have a floating IP \n - 3000455: Check whether Virtual Servers for VPC instance has all interfaces with IP-spoofing disabled \n - 3000467: Check whether Virtual Private Cloud (VPC) has no subnet with public gateway attached \n - 3000468: Check whether Virtual Private Cloud (VPC) is configured with public gateways that are provisionable only within permitted zones \n - 3000469: Check whether Application Load Balancer for VPC is configured with at least one VPC security group \n - 3000475: Check whether Virtual Private Cloud (VPC) security groups have inbound ports that are open only to permitted IPs \n - 3000476: Check whether Virtual Private Cloud (VPC) security groups have outbound ports that are open only to permitted IPs \n - 3000510: Check whether Hyper Protect Crypto Services is accessible only through private endpoints \n - 3000526: Check whether Hyper Protect DBaaS for MongoDB is accessible only using private endpoints \n - 3000534: Check whether Hyper Protect DBaaS for PostgreSQL is accessible only using private endpoints \n - 3000625: Check whether Container Registry image pushes and pulls take place only over private endpoints \n - 3000704: Check whether App ID redirect URIs are not using localhost or 127.0.0.1 \n - 3000705: Check whether App ID redirect URIs are not using wildcards (*) \n - 3000902: Check whether OpenShift clusters are accessible only by using private endpoints  | 
| Part b | - 3000020: Check whether authorized IP ranges are configured for the account \n - 3000022: Check whether Cloud Object Storage public access is disabled in IAM settings (not applicable to ACLs managed using S3 APIs) \n - 3000105: Check whether Cloud Object Storage is accessible only by using private endpoints \n - 3000107: Check whether Cloud Object Storage network access is restricted to a specific IP range \n - 3000306: Check whether Event Streams is accessible only by using private endpoints \n - 3000307: Check whether Event Streams network access is restricted to a specific IP range \n - 3000406: Check whether Virtual Private Cloud (VPC) has no rules in the default security group \n - 3000412: Check whether all virtual server instances have at least one Virtual Private Cloud (VPC) security group attached \n - 3000413: Check whether all network interfaces of a virtual server instance have at least one Virtual Private Cloud (VPC) security group attached \n - 3000418: Check whether account has at least one VPN or Direct Link configured \n - 3000427: Check whether Application Load Balancer for VPC has public access disabled \n - 3000447: Check whether Virtual Private Cloud (VPC) classic access is disabled \n - 3000451: Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to any port \n - 3000453: Check whether Virtual Servers for VPC instance has the minimum # interfaces \n - 3000454: Check whether Virtual Servers for VPC instance doesn't have a floating IP \n - 3000455: Check whether Virtual Servers for VPC instance has all interfaces with IP-spoofing disabled \n - 3000469: Check whether Application Load Balancer for VPC is configured with at least one VPC security group \n - 3000475: Check whether Virtual Private Cloud (VPC) security groups have inbound ports that are open only to permitted IPs \n - 3000510: Check whether Hyper Protect Crypto Services is accessible only through private endpoints \n - 3000526: Check whether Hyper Protect DBaaS for MongoDB is accessible only using private endpoints \n - 3000534: Check whether Hyper Protect DBaaS for PostgreSQL is accessible only using private endpoints \n - 3000625: Check whether Container Registry image pushes and pulls take place only over private endpoints \n - 3000704: Check whether App ID redirect URIs are not using localhost or 127.0.0.1 \n - 3000705: Check whether App ID redirect URIs are not using wildcards (*) \n - 3000902: Check whether OpenShift clusters are accessible only by using private endpoints  | 
| Part c | - 3000406: Check whether Virtual Private Cloud (VPC) has no rules in the default security group \n - 3000412: Check whether all virtual server instances have at least one Virtual Private Cloud (VPC) security group attached \n - 3000413: Check whether all network interfaces of a virtual server instance have at least one Virtual Private Cloud (VPC) security group attached \n - 3000418: Check whether account has at least one VPN or Direct Link configured \n - 3000444: Check whether Security Groups for VPC contains no outbound rules in security groups that specify source IP 8.8.8.8/32 to DNS port \n - 3000447: Check whether Virtual Private Cloud (VPC) classic access is disabled \n - 3000448: Check whether Virtual Private Cloud (VPC) has no public gateways attached at the time of provisioning \n - 3000449: Check whether Virtual Private Cloud (VPC) has no public gateways attached \n - 3000452: Check whether Virtual Private Cloud (VPC) network access control lists don't allow egress from 0.0.0.0/0 to any port \n - 3000453: Check whether Virtual Servers for VPC instance has the minimum # interfaces \n - 3000467: Check whether Virtual Private Cloud (VPC) has no subnet with public gateway attached \n - 3000468: Check whether Virtual Private Cloud (VPC) is configured with public gateways that are provisionable only within permitted zones \n - 3000476: Check whether Virtual Private Cloud (VPC) security groups have outbound ports that are open only to permitted IPs | 
{: caption="Goals for SC-7" caption-side="top"}

## NIST supplemental guidance
{: #supplemental-guidance}

Managed interfaces include, for example, gateways, routers, firewalls, guards, network-based malicious code analysis and virtualization systems, or encrypted tunnels implemented within a security architecture (e.g., routers protecting firewalls or application gateways residing on protected subnetworks). Subnetworks that are physically or logically separated from internal networks are referred to as demilitarized zones or DMZs. Restricting or prohibiting interfaces within organizational information systems includes, for example, restricting external web traffic to designated web servers within managed interfaces and prohibiting external traffic that appears to be spoofing internal addresses. Organizations consider the shared nature of commercial telecommunications services in the implementation of security controls associated with the use of such services. Commercial telecommunications services are commonly based on network components and consolidated management systems shared by all attached commercial customers, and may also include third party-provided access lines and other service elements. Such transmission services may represent sources of increased risk despite contract security provisions.

