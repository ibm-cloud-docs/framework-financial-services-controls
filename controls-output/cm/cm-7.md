---

copyright:
  years: 2020, 2023

lastupdated: "2023-04-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# CM-7 - Least Functionality
{: #cm-7}

## Control requirements
{: #control-requirements}

The organization:

CM-7 (a)
    : Configures the information system to provide only essential capabilities; and

CM-7 (b)
    : Prohibits or restricts the use of the following functions, ports, protocols, and/or services: _[IBM Assignment: limiting, disabling, and/or controlling services, features, applications, functions, ports, and protocols not explicitly required to support business functionality]_.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Rules |
|----------------|-------|
| CM-7 (a) | - Check whether Security Groups for VPC contains no outbound rules in security groups that specify source IP 8.8.8.8/32 to DNS port \n - Check whether Virtual Servers for VPC instance doesn't have a floating IP \n - Check whether App ID Cloud Directory users aren't able to update their own accounts \n - Check whether App ID email dispatchers are using HTTPS only \n - Check whether Application Load Balancer for VPC has public access disabled \n - Check whether Cloud Object Storage is accessible only through HTTPS \n - Check whether OpenShift clusters are accessible only by using private endpoints \n - Check whether Virtual Private Cloud (VPC) security groups have inbound ports that are open only to permitted IP addresses \n - Check whether App ID lockout policy after failed # of sign-in attempts is enabled \n - Check whether App ID social identity providers are disabled \n - Check whether Virtual Private Cloud (VPC) has no public gateways attached \n - Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to any port \n - Check whether Application Load Balancer for VPC is configured to convert HTTP client requests to HTTPS \n - Check whether all virtual server instances have at least one Virtual Private Cloud (VPC) security group attached \n - Check whether Virtual Private Cloud (VPC) has no public gateways attached at the time of provisioning \n - Check whether App ID redirect URIs are not using wildcards (*) \n - Check whether App ID webhooks are using HTTPS only \n - Check whether Virtual Servers for VPC instance has all interfaces with IP-spoofing disabled \n - Check whether Virtual Private Cloud (VPC) classic access is disabled \n - Check whether Virtual Private Cloud (VPC) has no rules in the default security group \n - Check whether App ID Cloud Directory users aren't able to self-sign up to applications \n - Check whether all network interfaces of a virtual server instance have at least one Virtual Private Cloud (VPC) security group attached \n - Check whether Virtual Servers for VPC instance has the minimum # interfaces \n - Check whether App ID redirect URIs are using HTTPS only \n - Check whether Cloud Internet Services (CIS) has TLS mode set to End-to-End CA signed \n - Check whether Virtual Private Cloud (VPC) security groups have outbound ports that are open only to permitted IP addresses \n - Check whether Application Load Balancer for VPC pool uses the HTTPS protocol for HTTPS listeners \n - Check whether Application Load Balancer for VPC uses HTTPS (SSL & TLS) instead of HTTP \n - Check whether Cloud Object Storage public access is disabled in IAM settings (not applicable to ACLs managed using S3 APIs) \n - Check whether App ID anonymous authentication is disabled \n - Check whether App ID avoid password reuse policy is enabled \n - Check whether App ID user profile updates from client apps is disabled \n - Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to RDP port \n - Check whether App ID redirect URIs are not using localhost or 127.0.0.1 \n - Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to SSH port \n - Check whether Virtual Private Cloud (VPC) network access control lists don't allow egress from 0.0.0.0/0 to any port | 
| CM-7 (b) | - Check whether Security Groups for VPC contains no outbound rules in security groups that specify source IP 8.8.8.8/32 to DNS port \n - Check whether Virtual Servers for VPC instance doesn't have a floating IP \n - Check whether App ID Cloud Directory users aren't able to update their own accounts \n - Check whether App ID email dispatchers are using HTTPS only \n - Check whether Application Load Balancer for VPC has public access disabled \n - Check whether Cloud Object Storage is accessible only through HTTPS \n - Check whether OpenShift clusters are accessible only by using private endpoints \n - Check whether App ID lockout policy after failed # of sign-in attempts is enabled \n - Check whether Virtual Private Cloud (VPC) has no public gateways attached \n - Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to any port \n - Check whether Application Load Balancer for VPC is configured to convert HTTP client requests to HTTPS \n - Check whether all virtual server instances have at least one Virtual Private Cloud (VPC) security group attached \n - Check whether Virtual Private Cloud (VPC) has no public gateways attached at the time of provisioning \n - Check whether App ID redirect URIs are not using wildcards (*) \n - Check whether DevSecOps Toolchain validates code against Center for Internet Security (CIS) Docker benchmarks to ensure container runtimes are configured securely \n - Check whether App ID webhooks are using HTTPS only \n - Check whether Virtual Servers for VPC instance has all interfaces with IP-spoofing disabled \n - Check whether Virtual Private Cloud (VPC) classic access is disabled \n - Check whether DevSecOps Toolchain passes dynamic code scan to identify vulnerabilities in deployed artifacts \n - Check whether Virtual Private Cloud (VPC) has no rules in the default security group \n - Check whether App ID Cloud Directory users aren't able to self-sign up to applications \n - Check whether all network interfaces of a virtual server instance have at least one Virtual Private Cloud (VPC) security group attached \n - Check whether DevSecOps Toolchain passes static code scan to identify vulnerabilities in source code \n - Check whether Virtual Servers for VPC instance has the minimum # interfaces \n - Check whether App ID redirect URIs are using HTTPS only \n - Check whether Cloud Internet Services (CIS) has TLS mode set to End-to-End CA signed \n - Check whether Application Load Balancer for VPC pool uses the HTTPS protocol for HTTPS listeners \n - Check whether Application Load Balancer for VPC uses HTTPS (SSL & TLS) instead of HTTP \n - Check whether Cloud Object Storage public access is disabled in IAM settings (not applicable to ACLs managed using S3 APIs) \n - Check whether App ID anonymous authentication is disabled \n - Check whether App ID avoid password reuse policy is enabled \n - Check whether App ID user profile updates from client apps is disabled \n - Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to RDP port \n - Check whether App ID redirect URIs are not using localhost or 127.0.0.1 \n - Check whether Virtual Private Cloud (VPC) network access control lists don't allow ingress from 0.0.0.0/0 to SSH port \n - Check whether Virtual Private Cloud (VPC) network access control lists don't allow egress from 0.0.0.0/0 to any port | 
{: caption="Rules for CM-7 in IBM Cloud for Financial Services v1.2.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Information systems can provide a wide variety of functions and services. Some of the functions and services, provided by default, may not be necessary to support essential organizational operations (e.g., key missions, functions). Additionally, it is sometimes convenient to provide multiple services from single information system components, but doing so increases risk over limiting the services provided by any one component. Where feasible, organizations limit component functionality to a single function per device (e.g., email servers or web servers, but not both). Organizations review functions and services provided by information systems or individual components of information systems, to determine which functions and services are candidates for elimination (e.g., Voice Over Internet Protocol, Instant Messaging, auto-execute, and file sharing). Organizations consider disabling unused or unnecessary physical and logical ports/protocols (e.g., Universal Serial Bus, File Transfer Protocol, and Hyper Text Transfer Protocol) on information systems to prevent unauthorized connection of devices, unauthorized transfer of information, or unauthorized tunneling. Organizations can utilize network scanning tools, intrusion detection and prevention systems, and end-point protections such as firewalls and host-based intrusion detection systems to identify and prevent the use of prohibited functions, ports, protocols, and services.





