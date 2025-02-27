---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# SC-8 (1) -  Cryptographic Protection
{: #sc-8.1}

## Control requirements
{: #control-requirements}



### SC-8 (1) - 0


Implement cryptographic mechanisms to _[IBM Assignment: prevent unauthorized disclosure of information]_ during transmission.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

The organization must encrypt customer data in transit regardless of the transport mechanism and/or digital media type used, except in the cases of DNS, NTP, BGP, ICMP, ARP, DHCP, TFTP, NFS v3, heartbeat, SNMP read-only, and logging (such as rsyslog/fluentd) traffic assessed as very low risk from a confidentiality/integrity standpoint. For web-based applications, the organization will ensure that transmitted data is protected in accordance with the recommendations of the Open Web Application Security Project (OWASP).







## NIST supplemental guidance
{: #nist-supplemental-guidance}

Encryption protects information from unauthorized disclosure and modification during transmission. Cryptographic mechanisms that protect the confidentiality and integrity of information during transmission include TLS and IPSec. Cryptographic mechanisms used to protect information integrity include cryptographic hash functions that have applications in digital signatures, checksums, and message authentication codes.
