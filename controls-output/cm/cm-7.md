---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-16"
keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# CM-7 - Least Functionality
{: #cm-7}

## Requirements
{: #requirements}

The organization:

- \[a.\] Configures the information system to provide only essential capabilities; and

- \[b.\] Prohibits or restricts the use of the following functions, ports, protocols, and/or services: [limiting, disabling, and/or controlling services, features, applications, functions, ports, and protocols not explicitly required to support business functionality].

## NIST supplemental guidance
{: #supplemental-guidance}

Information systems can provide a wide variety of functions and services. Some of the functions and services, provided by default, may not be necessary to support essential organizational operations (e.g., key missions, functions). Additionally, it is sometimes convenient to provide multiple services from single information system components, but doing so increases risk over limiting the services provided by any one component. Where feasible, organizations limit component functionality to a single function per device (e.g., email servers or web servers, but not both). Organizations review functions and services provided by information systems or individual components of information systems, to determine which functions and services are candidates for elimination (e.g., Voice Over Internet Protocol, Instant Messaging, auto-execute, and file sharing). Organizations consider disabling unused or unnecessary physical and logical ports/protocols (e.g., Universal Serial Bus, File Transfer Protocol, and Hyper Text Transfer Protocol) on information systems to prevent unauthorized connection of devices, unauthorized transfer of information, or unauthorized tunneling. Organizations can utilize network scanning tools, intrusion detection and prevention systems, and end-point protections such as firewalls and host-based intrusion detection systems to identify and prevent the use of prohibited functions, ports, protocols, and services.


## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

### Part a.
{: #part-a-scc-fs-cloud-profile}

- 3000022: Check whether Cloud Object Storage public access is disabled in IAM settings (not applicable to ACLs managed using S3 APIs)
- 3000103: Check whether Cloud Object Storage is accessible only through HTTPS
- 3000105: Check whether Cloud Object Storage is accessible only by using private endpoints
- 3000406: Check whether Virtual Private Cloud (VPC) has no rules in the default security group
- 3000407: Check whether Virtual Private Cloud (VPC) is configured with at least TLS v1.2 for all inbound traffic through a load balancer
- 3000412: Check whether all virtual server instances have at least one Virtual Private Cloud (VPC) security group attached
- 3000413: Check whether all network interfaces of a virtual server instance have at least one Virtual Private Cloud (VPC) security group attached
- 3000427: Check whether Application Load Balancer for VPC has public access disabled
- 3000432: Check whether Application Load Balancer for VPC pool uses the HTTPS protocol for HTTPS listeners
- 3000433: Check whether Application Load Balancer for VPC is configured to convert HTTP client requests to HTTPS
- 3000434: Check whether Application Load Balancer for VPC uses HTTPS (SSL & TLS) instead of HTTP
- 3000444: Check whether Security Groups for VPC contains no outbound rules in security groups that specify source IP 8.8.8.8/32 to DNS port
- 3000447: Check whether Virtual Private Cloud (VPC) classic access is disabled
- 3000448: Check whether Virtual Private Cloud (VPC) has no public gateways attached at the time of provisioning
- 3000449: Check whether Virtual Private Cloud (VPC) has no public gateways attached
- 3000451: Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to any port
- 3000452: Check whether Virtual Private Cloud (VPC) network access control lists don't allow egress from 0.0.0.0/0 to any port
- 3000453: Check whether Virtual Servers for VPC instance has the minimum # interfaces
- 3000454: Check whether Virtual Servers for VPC instance doesn't have a floating IP
- 3000455: Check whether Virtual Servers for VPC instance has all interfaces with IP-spoofing disabled
- 3000470: Check whether Cloud Internet Services (CIS) has TLS mode set to End-to-End CA signed
- 3000475: Check whether Virtual Private Cloud (VPC) security groups have inbound ports that are open only to permitted IPs
- 3000476: Check whether Virtual Private Cloud (VPC) security groups have outbound ports that are open only to permitted IPs
- 3000701: Check whether App ID webhooks are using HTTPS only
- 3000702: Check whether App ID email dispatchers are using HTTPS only
- 3000703: Check whether App ID redirect URIs are using HTTPS only
- 3000704: Check whether App ID redirect URIs are not using localhost or 127.0.0.1
- 3000705: Check whether App ID redirect URIs are not using wildcards (*)
- 3000707: Check whether App ID user profile updates from client apps is disabled
- 3000708: Check whether App ID Cloud Directory users aren't able to update their own accounts
- 3000709: Check whether App ID Cloud Directory users aren't able to self-sign up to applications
- 3000711: Check whether App ID social identity providers are disabled
- 3000712: Check whether App ID anonymous authentication is disabled
- 3000715: Check whether App ID avoid password reuse policy is enabled
- 3000902: Check whether OpenShift clusters are accessible only by using private endpoints 
- 3000906: Check whether OpenShift Ingress is configured with at least TLS v1.2 for all inbound traffic

### Part b.
{: #part-b-scc-fs-cloud-profile}

- 3000022: Check whether Cloud Object Storage public access is disabled in IAM settings (not applicable to ACLs managed using S3 APIs)
- 3000103: Check whether Cloud Object Storage is accessible only through HTTPS
- 3000105: Check whether Cloud Object Storage is accessible only by using private endpoints
- 3000406: Check whether Virtual Private Cloud (VPC) has no rules in the default security group
- 3000407: Check whether Virtual Private Cloud (VPC) is configured with at least TLS v1.2 for all inbound traffic through a load balancer
- 3000412: Check whether all virtual server instances have at least one Virtual Private Cloud (VPC) security group attached
- 3000413: Check whether all network interfaces of a virtual server instance have at least one Virtual Private Cloud (VPC) security group attached
- 3000427: Check whether Application Load Balancer for VPC has public access disabled
- 3000432: Check whether Application Load Balancer for VPC pool uses the HTTPS protocol for HTTPS listeners
- 3000433: Check whether Application Load Balancer for VPC is configured to convert HTTP client requests to HTTPS
- 3000434: Check whether Application Load Balancer for VPC uses HTTPS (SSL & TLS) instead of HTTP
- 3000444: Check whether Security Groups for VPC contains no outbound rules in security groups that specify source IP 8.8.8.8/32 to DNS port
- 3000447: Check whether Virtual Private Cloud (VPC) classic access is disabled
- 3000448: Check whether Virtual Private Cloud (VPC) has no public gateways attached at the time of provisioning
- 3000449: Check whether Virtual Private Cloud (VPC) has no public gateways attached
- 3000451: Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to any port
- 3000452: Check whether Virtual Private Cloud (VPC) network access control lists don't allow egress from 0.0.0.0/0 to any port
- 3000453: Check whether Virtual Servers for VPC instance has the minimum # interfaces
- 3000454: Check whether Virtual Servers for VPC instance doesn't have a floating IP
- 3000455: Check whether Virtual Servers for VPC instance has all interfaces with IP-spoofing disabled
- 3000470: Check whether Cloud Internet Services (CIS) has TLS mode set to End-to-End CA signed
- 3000701: Check whether App ID webhooks are using HTTPS only
- 3000702: Check whether App ID email dispatchers are using HTTPS only
- 3000703: Check whether App ID redirect URIs are using HTTPS only
- 3000704: Check whether App ID redirect URIs are not using localhost or 127.0.0.1
- 3000705: Check whether App ID redirect URIs are not using wildcards (*)
- 3000707: Check whether App ID user profile updates from client apps is disabled
- 3000708: Check whether App ID Cloud Directory users aren't able to update their own accounts
- 3000709: Check whether App ID Cloud Directory users aren't able to self-sign up to applications
- 3000712: Check whether App ID anonymous authentication is disabled
- 3000715: Check whether App ID avoid password reuse policy is enabled
- 3000902: Check whether OpenShift clusters are accessible only by using private endpoints 
- 3000906: Check whether OpenShift Ingress is configured with at least TLS v1.2 for all inbound traffic
