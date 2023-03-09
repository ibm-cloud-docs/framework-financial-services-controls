---

copyright:
  years: 2020, 2023

lastupdated: "2023-03-08"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# SC-8 (1) - Cryptographic or Alternate Physical Protection
{: #sc-8.1}

## Control requirements
{: #control-requirements}

SC-8 (1) - 0
    : The information system implements cryptographic mechanisms to [IBM Assignment: prevent unauthorized disclosure of information] during transmission unless otherwise protected by [IBM Assignment: none].

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- The organization must encrypt customer data in transit regardless of the transport mechanism and/or digital media type used, except in the cases of DNS, NTP, BGP, ICMP, ARP, DHCP, TFTP, NFS v3, heartbeat, SNMP read-only, and logging (such as rsyslog/fluentd) traffic assessed as very low risk from a confidentiality/integrity standpoint. For web-based applications, the organization will ensure that transmitted data is protected in accordance with the recommendations of the Open Web Application Security Project (OWASP).

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Connecting application provider to the management VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-management)
- [Consumer connectivity to workload VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-workload)
- [Creating and connecting the management and workload VPCs](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-create-vpcs)
- [Data encryption in transit](/docs/framework-financial-services?topic=framework-financial-services-shared-encryption-in-transit)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.1.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- Check whether App ID email dispatchers are using HTTPS only 
- Check whether Cloud Object Storage is accessible only through HTTPS 
- Check whether Application Load Balancer for VPC is configured to convert HTTP client requests to HTTPS 
- Check whether App ID webhooks are using HTTPS only 
- Check whether App ID redirect URIs are using HTTPS only 
- Check whether Cloud Internet Services (CIS) has TLS mode set to End-to-End CA signed 
- Check whether Application Load Balancer for VPC pool uses the HTTPS protocol for HTTPS listeners 
- Check whether Application Load Balancer for VPC uses HTTPS (SSL & TLS) instead of HTTP

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Encrypting information for transmission protects information from unauthorized disclosure and modification. Cryptographic mechanisms implemented to protect information integrity include, for example, cryptographic hash functions which have common application in digital signatures, checksums, and message authentication codes. Alternative physical security safeguards include, for example, protected distribution systems.





