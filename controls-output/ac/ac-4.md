---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-07"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# AC-4 - Information Flow Enforcement
{: #ac-4}

## Requirements
{: #requirements}

The information system enforces approved authorizations for controlling the flow of information within the system and between interconnected systems based on [organization-defined information flow control policies].

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

The organization must document all information flows that involve the transfer of customer data.  An information flow control policy must be developed and maintained that indicates the source and destination of each flow, the system of record and whether the information is altered during transmission. 

The organization shall maintain a catalog of all customer metadata processed and/or transmitted by the organization on behalf of the customer.  Metadata should be defined by each customer.

The organization &#34;service delivery&#34; and &#34;corporate&#34; environments must be maintained as separate environments. That is, clear physical and/or logical boundaries separating the two environments must exist.

## Control Supplemental Guidance
{: #supplemental-guidance}

Information flow control regulates where information is allowed to travel within an information system and between information systems (as opposed to who is allowed to access the information) and without explicit regard to subsequent accesses to that information. Flow control restrictions include, for example, keeping export-controlled information from being transmitted in the clear to the Internet, blocking outside traffic that claims to be from within the organization, restricting web requests to the Internet that are not from the internal web proxy server, and limiting information transfers between organizations based on data structures and content. Transferring information between information systems representing different security domains with different security policies introduces risk that such transfers violate one or more domain security policies. In such situations, information owners/stewards provide guidance at designated policy enforcement points between interconnected systems. Organizations consider mandating specific architectural solutions when required to enforce specific security policies. Enforcement includes, for example: (i) prohibiting information transfers between interconnected systems (i.e., allowing access only); (ii) employing hardware mechanisms to enforce one-way information flows; and (iii) implementing trustworthy regrading mechanisms to reassign security attributes and security labels. Organizations commonly employ information flow control policies and enforcement mechanisms to control the flow of information between designated sources and destinations (e.g., networks, individuals, and devices) within information systems and between interconnected systems. Flow control is based on the characteristics of the information and/or the information path. Enforcement occurs, for example, in boundary protection devices (e.g., gateways, routers, guards, encrypted tunnels, firewalls) that employ rule sets or establish configuration settings that restrict information system services, provide a packet-filtering capability based on header information, or message-filtering capability based on message content (e.g., implementing key word searches or using document characteristics). Organizations also consider the trustworthiness of filtering/inspection mechanisms (i.e., hardware, firmware, and software components) that are critical to information flow enforcement. Control enhancements 3 through 22 primarily address cross-domain solution needs which focus on more advanced filtering techniques, in-depth analysis, and stronger flow enforcement mechanisms implemented in cross-domain products, for example, high-assurance guards. Such capabilities are generally not available in commercial off-the-shelf information technology products.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| ac-4_prm_1 |  | organization-defined information flow control policies |


## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

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
- [3000471: Check that at least # Virtual Private Cloud(VPC)s have been created](https://cloud.ibm.com/security-compliance/goals/3000471?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000472: Check that at least # instances of Transit Gateway have been created](https://cloud.ibm.com/security-compliance/goals/3000472?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000475: Check whether Virtual Private Cloud (VPC) security groups have inbound ports that are open only to permitted IPs](https://cloud.ibm.com/security-compliance/goals/3000475?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000476: Check whether Virtual Private Cloud (VPC) security groups have outbound ports that are open only to permitted IPs](https://cloud.ibm.com/security-compliance/goals/3000476?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000510: Check whether Hyper Protect Crypto Services is accessible only through private endpoints](https://cloud.ibm.com/security-compliance/goals/3000510?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000526: Check whether Hyper Protect DBaaS for MongoDB is accessible only using private endpoints](https://cloud.ibm.com/security-compliance/goals/3000526?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000534: Check whether Hyper Protect DBaaS for PostgreSQL is accessible only using private endpoints](https://cloud.ibm.com/security-compliance/goals/3000534?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000625: Check whether Container Registry image pushes and pulls take place only over private endpoints](https://cloud.ibm.com/security-compliance/goals/3000625?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000704: Check whether App ID redirect URIs are not using localhost or 127.0.0.1](https://cloud.ibm.com/security-compliance/goals/3000704?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000705: Check whether App ID redirect URIs are not using wildcards (*)](https://cloud.ibm.com/security-compliance/goals/3000705?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000902: Check whether OpenShift clusters are accessible only by using private endpoints ](https://cloud.ibm.com/security-compliance/goals/3000902?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
