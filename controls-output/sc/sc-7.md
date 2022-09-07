---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-07"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# SC-7 - Boundary Protection
{: #sc-7}

## Requirements
{: #requirements}

The information system:

- \[a.\] Monitors and controls communications at the external boundary of the system and at key internal boundaries within the system;

- \[b.\] Implements subnetworks for publicly accessible system components that are [physically; logically] separated from internal organizational networks; and

- \[c.\] Connects to external networks or information systems only through managed interfaces consisting of boundary protection devices arranged in accordance with an organizational security architecture.

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

The organization &#34;service delivery&#34; and &#34;corporate&#34; environments must be maintained as separate environments. That is, clear physical and/or logical boundaries separating the two environments must exist.

## Control Supplemental Guidance
{: #supplemental-guidance}

Managed interfaces include, for example, gateways, routers, firewalls, guards, network-based malicious code analysis and virtualization systems, or encrypted tunnels implemented within a security architecture (e.g., routers protecting firewalls or application gateways residing on protected subnetworks). Subnetworks that are physically or logically separated from internal networks are referred to as demilitarized zones or DMZs. Restricting or prohibiting interfaces within organizational information systems includes, for example, restricting external web traffic to designated web servers within managed interfaces and prohibiting external traffic that appears to be spoofing internal addresses. Organizations consider the shared nature of commercial telecommunications services in the implementation of security controls associated with the use of such services. Commercial telecommunications services are commonly based on network components and consolidated management systems shared by all attached commercial customers, and may also include third party-provided access lines and other service elements. Such transmission services may represent sources of increased risk despite contract security provisions.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| sc-7_prm_1 |  | Choose : physically; logically |


## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

### Part a
{: #scc-fs-cloud-profile-a}

- [3000020: Check whether authorized IP ranges are configured for the account](https://cloud.ibm.com/security-compliance/goals/3000020?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000022: Check whether Cloud Object Storage public access is disabled in IAM settings (not applicable to ACLs managed using S3 APIs)](https://cloud.ibm.com/security-compliance/goals/3000022?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000105: Check whether Cloud Object Storage is accessible only by using private endpoints](https://cloud.ibm.com/security-compliance/goals/3000105?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000107: Check whether Cloud Object Storage network access is restricted to a specific IP range](https://cloud.ibm.com/security-compliance/goals/3000107?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000306: Check whether Event Streams is accessible only by using private endpoints](https://cloud.ibm.com/security-compliance/goals/3000306?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000307: Check whether Event Streams network access is restricted to a specific IP range](https://cloud.ibm.com/security-compliance/goals/3000307?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000406: Check whether Virtual Private Cloud (VPC) has no rules in the default security group](https://cloud.ibm.com/security-compliance/goals/3000406?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000408: Check whether Flow Logs for VPC are enabled](https://cloud.ibm.com/security-compliance/goals/3000408?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000412: Check whether all virtual server instances have at least one Virtual Private Cloud (VPC) security group attached](https://cloud.ibm.com/security-compliance/goals/3000412?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000413: Check whether all network interfaces of a virtual server instance have at least one Virtual Private Cloud (VPC) security group attached](https://cloud.ibm.com/security-compliance/goals/3000413?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000418: Check whether account has at least one VPN or Direct Link configured](https://cloud.ibm.com/security-compliance/goals/3000418?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000427: Check whether Application Load Balancer for VPC has public access disabled](https://cloud.ibm.com/security-compliance/goals/3000427?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000444: Check whether Security Groups for VPC contains no outbound rules in security groups that specify source IP 8.8.8.8/32 to DNS port](https://cloud.ibm.com/security-compliance/goals/3000444?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000447: Check whether Virtual Private Cloud (VPC) classic access is disabled](https://cloud.ibm.com/security-compliance/goals/3000447?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000448: Check whether Virtual Private Cloud (VPC) has no public gateways attached at the time of provisioning](https://cloud.ibm.com/security-compliance/goals/3000448?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000449: Check whether Virtual Private Cloud (VPC) has no public gateways attached](https://cloud.ibm.com/security-compliance/goals/3000449?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000451: Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to any port](https://cloud.ibm.com/security-compliance/goals/3000451?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000452: Check whether Virtual Private Cloud (VPC) network access control lists don't allow egress from 0.0.0.0/0 to any port](https://cloud.ibm.com/security-compliance/goals/3000452?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000453: Check whether Virtual Servers for VPC instance has the minimum # interfaces](https://cloud.ibm.com/security-compliance/goals/3000453?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000454: Check whether Virtual Servers for VPC instance doesn't have a floating IP](https://cloud.ibm.com/security-compliance/goals/3000454?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000455: Check whether Virtual Servers for VPC instance has all interfaces with IP-spoofing disabled](https://cloud.ibm.com/security-compliance/goals/3000455?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000467: Check whether Virtual Private Cloud (VPC) has no subnet with public gateway attached](https://cloud.ibm.com/security-compliance/goals/3000467?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000468: Check whether Virtual Private Cloud (VPC) is configured with public gateways that are provisionable only within permitted zones](https://cloud.ibm.com/security-compliance/goals/3000468?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000469: Check whether Application Load Balancer for VPC is configured with at least one VPC security group](https://cloud.ibm.com/security-compliance/goals/3000469?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000475: Check whether Virtual Private Cloud (VPC) security groups have inbound ports that are open only to permitted IPs](https://cloud.ibm.com/security-compliance/goals/3000475?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000476: Check whether Virtual Private Cloud (VPC) security groups have outbound ports that are open only to permitted IPs](https://cloud.ibm.com/security-compliance/goals/3000476?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000510: Check whether Hyper Protect Crypto Services is accessible only through private endpoints](https://cloud.ibm.com/security-compliance/goals/3000510?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000526: Check whether Hyper Protect DBaaS for MongoDB is accessible only using private endpoints](https://cloud.ibm.com/security-compliance/goals/3000526?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000534: Check whether Hyper Protect DBaaS for PostgreSQL is accessible only using private endpoints](https://cloud.ibm.com/security-compliance/goals/3000534?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000625: Check whether Container Registry image pushes and pulls take place only over private endpoints](https://cloud.ibm.com/security-compliance/goals/3000625?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000704: Check whether App ID redirect URIs are not using localhost or 127.0.0.1](https://cloud.ibm.com/security-compliance/goals/3000704?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000705: Check whether App ID redirect URIs are not using wildcards (*)](https://cloud.ibm.com/security-compliance/goals/3000705?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000902: Check whether OpenShift clusters are accessible only by using private endpoints ](https://cloud.ibm.com/security-compliance/goals/3000902?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}

### Part b
{: #scc-fs-cloud-profile-b}

- [3000020: Check whether authorized IP ranges are configured for the account](https://cloud.ibm.com/security-compliance/goals/3000020?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000022: Check whether Cloud Object Storage public access is disabled in IAM settings (not applicable to ACLs managed using S3 APIs)](https://cloud.ibm.com/security-compliance/goals/3000022?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000105: Check whether Cloud Object Storage is accessible only by using private endpoints](https://cloud.ibm.com/security-compliance/goals/3000105?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000107: Check whether Cloud Object Storage network access is restricted to a specific IP range](https://cloud.ibm.com/security-compliance/goals/3000107?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000306: Check whether Event Streams is accessible only by using private endpoints](https://cloud.ibm.com/security-compliance/goals/3000306?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000307: Check whether Event Streams network access is restricted to a specific IP range](https://cloud.ibm.com/security-compliance/goals/3000307?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000406: Check whether Virtual Private Cloud (VPC) has no rules in the default security group](https://cloud.ibm.com/security-compliance/goals/3000406?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000412: Check whether all virtual server instances have at least one Virtual Private Cloud (VPC) security group attached](https://cloud.ibm.com/security-compliance/goals/3000412?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000413: Check whether all network interfaces of a virtual server instance have at least one Virtual Private Cloud (VPC) security group attached](https://cloud.ibm.com/security-compliance/goals/3000413?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000418: Check whether account has at least one VPN or Direct Link configured](https://cloud.ibm.com/security-compliance/goals/3000418?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000427: Check whether Application Load Balancer for VPC has public access disabled](https://cloud.ibm.com/security-compliance/goals/3000427?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000447: Check whether Virtual Private Cloud (VPC) classic access is disabled](https://cloud.ibm.com/security-compliance/goals/3000447?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000451: Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to any port](https://cloud.ibm.com/security-compliance/goals/3000451?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000453: Check whether Virtual Servers for VPC instance has the minimum # interfaces](https://cloud.ibm.com/security-compliance/goals/3000453?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000454: Check whether Virtual Servers for VPC instance doesn't have a floating IP](https://cloud.ibm.com/security-compliance/goals/3000454?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000455: Check whether Virtual Servers for VPC instance has all interfaces with IP-spoofing disabled](https://cloud.ibm.com/security-compliance/goals/3000455?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000469: Check whether Application Load Balancer for VPC is configured with at least one VPC security group](https://cloud.ibm.com/security-compliance/goals/3000469?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000475: Check whether Virtual Private Cloud (VPC) security groups have inbound ports that are open only to permitted IPs](https://cloud.ibm.com/security-compliance/goals/3000475?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000510: Check whether Hyper Protect Crypto Services is accessible only through private endpoints](https://cloud.ibm.com/security-compliance/goals/3000510?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000526: Check whether Hyper Protect DBaaS for MongoDB is accessible only using private endpoints](https://cloud.ibm.com/security-compliance/goals/3000526?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000534: Check whether Hyper Protect DBaaS for PostgreSQL is accessible only using private endpoints](https://cloud.ibm.com/security-compliance/goals/3000534?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000625: Check whether Container Registry image pushes and pulls take place only over private endpoints](https://cloud.ibm.com/security-compliance/goals/3000625?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000704: Check whether App ID redirect URIs are not using localhost or 127.0.0.1](https://cloud.ibm.com/security-compliance/goals/3000704?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000705: Check whether App ID redirect URIs are not using wildcards (*)](https://cloud.ibm.com/security-compliance/goals/3000705?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000902: Check whether OpenShift clusters are accessible only by using private endpoints ](https://cloud.ibm.com/security-compliance/goals/3000902?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}

### Part c
{: #scc-fs-cloud-profile-c}

- [3000406: Check whether Virtual Private Cloud (VPC) has no rules in the default security group](https://cloud.ibm.com/security-compliance/goals/3000406?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000412: Check whether all virtual server instances have at least one Virtual Private Cloud (VPC) security group attached](https://cloud.ibm.com/security-compliance/goals/3000412?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000413: Check whether all network interfaces of a virtual server instance have at least one Virtual Private Cloud (VPC) security group attached](https://cloud.ibm.com/security-compliance/goals/3000413?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000418: Check whether account has at least one VPN or Direct Link configured](https://cloud.ibm.com/security-compliance/goals/3000418?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000444: Check whether Security Groups for VPC contains no outbound rules in security groups that specify source IP 8.8.8.8/32 to DNS port](https://cloud.ibm.com/security-compliance/goals/3000444?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000447: Check whether Virtual Private Cloud (VPC) classic access is disabled](https://cloud.ibm.com/security-compliance/goals/3000447?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000448: Check whether Virtual Private Cloud (VPC) has no public gateways attached at the time of provisioning](https://cloud.ibm.com/security-compliance/goals/3000448?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000449: Check whether Virtual Private Cloud (VPC) has no public gateways attached](https://cloud.ibm.com/security-compliance/goals/3000449?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000452: Check whether Virtual Private Cloud (VPC) network access control lists don't allow egress from 0.0.0.0/0 to any port](https://cloud.ibm.com/security-compliance/goals/3000452?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000453: Check whether Virtual Servers for VPC instance has the minimum # interfaces](https://cloud.ibm.com/security-compliance/goals/3000453?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000467: Check whether Virtual Private Cloud (VPC) has no subnet with public gateway attached](https://cloud.ibm.com/security-compliance/goals/3000467?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000468: Check whether Virtual Private Cloud (VPC) is configured with public gateways that are provisionable only within permitted zones](https://cloud.ibm.com/security-compliance/goals/3000468?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000476: Check whether Virtual Private Cloud (VPC) security groups have outbound ports that are open only to permitted IPs](https://cloud.ibm.com/security-compliance/goals/3000476?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
