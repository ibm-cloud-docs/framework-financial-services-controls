---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-29"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# SC-8 (1) - Cryptographic or Alternate Physical Protection
{: #sc-8.1}

## Control requirements
{: #control-requirements}

SC-8 (1) - 0
    : The information system implements cryptographic mechanisms to [prevent unauthorized disclosure of information] during transmission unless otherwise protected by [none].

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- The organization must encrypt customer data in transit regardless of the transport mechanism and/or digital media type used, except in the cases of DNS, NTP, BGP, ICMP, ARP, DHCP, TFTP, NFS v3, heartbeat, SNMP read-only, and logging (such as rsyslog/fluentd) traffic assessed as very low risk from a confidentiality/integrity standpoint. For web-based applications, the organization will ensure that transmitted data is protected in accordance with the recommendations of the Open Web Application Security Project (OWASP).

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Data encryption in transit](/docs/framework-financial-services?topic=framework-financial-services-shared-encryption-in-transit)
- [Creating and connecting the management and workload VPCs](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-create-vpcs)
- [Consumer connectivity to workload VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-workload)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.6.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- 3000103: Check whether Cloud Object Storage is accessible only through HTTPS 
- 3000407: Check whether Virtual Private Cloud (VPC) is configured with at least TLS v1.2 for all inbound traffic through a load balancer 
- 3000432: Check whether Application Load Balancer for VPC pool uses the HTTPS protocol for HTTPS listeners 
- 3000433: Check whether Application Load Balancer for VPC is configured to convert HTTP client requests to HTTPS 
- 3000434: Check whether Application Load Balancer for VPC uses HTTPS (SSL & TLS) instead of HTTP 
- 3000470: Check whether Cloud Internet Services (CIS) has TLS mode set to End-to-End CA signed 
- 3000701: Check whether App ID webhooks are using HTTPS only 
- 3000702: Check whether App ID email dispatchers are using HTTPS only 
- 3000703: Check whether App ID redirect URIs are using HTTPS only 
- 3000906: Check whether OpenShift Ingress is configured with at least TLS v1.2 for all inbound traffic

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Encrypting information for transmission protects information from unauthorized disclosure and modification. Cryptographic mechanisms implemented to protect information integrity include, for example, cryptographic hash functions which have common application in digital signatures, checksums, and message authentication codes. Alternative physical security safeguards include, for example, protected distribution systems.



