---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-08"
keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# SC-8 (1) - Cryptographic Or Alternate Physical Protection
{: #sc-8.1}

## Requirements
{: #requirements}

The information system implements cryptographic mechanisms to [prevent unauthorized disclosure of information, highest financial institution standard (FIPS140-2 L3) for Highly Restricted Confidential Information (HRCI)] during transmission unless otherwise protected by [none].

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

The organization must encrypt customer data in transit regardless of the transport mechanism and/or digital media type used. For web-based applications, the organization will ensure that transmitted data is protected in accordance with the recommendations of the Open Web Application Security Project (OWASP).

## Control Supplemental Guidance
{: #supplemental-guidance}

Encrypting information for transmission protects information from unauthorized disclosure and modification. Cryptographic mechanisms implemented to protect information integrity include, for example, cryptographic hash functions which have common application in digital signatures, checksums, and message authentication codes. Alternative physical security safeguards include, for example, protected distribution systems.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| sc-8.1_prm_1 | prevent unauthorized disclosure of information, highest financial institution standard (FIPS140-2 L3) for Highly Restricted Confidential Information (HRCI) | Choose one or more: prevent unauthorized disclosure of information; detect changes to information |
| sc-8.1_prm_2 | none | organization-defined alternative physical safeguards |


## Related Resources
{: #related_resources}

See the resources that follow to learn more about how to implement this control.

- [Data encryption in transit](/docs/framework-financial-services?topic=framework-financial-services-shared-encryption-in-transit)

## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- [3000103: Check whether Cloud Object Storage is accessible only through HTTPS](https://cloud.ibm.com/security-compliance/goals/3000103?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000407: Check whether Virtual Private Cloud (VPC) is configured with at least TLS v1.2 for all inbound traffic through a load balancer](https://cloud.ibm.com/security-compliance/goals/3000407?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000432: Check whether Application Load Balancer for VPC pool uses the HTTPS protocol for HTTPS listeners](https://cloud.ibm.com/security-compliance/goals/3000432?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000433: Check whether Application Load Balancer for VPC is configured to convert HTTP client requests to HTTPS](https://cloud.ibm.com/security-compliance/goals/3000433?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000434: Check whether Application Load Balancer for VPC uses HTTPS (SSL & TLS) instead of HTTP](https://cloud.ibm.com/security-compliance/goals/3000434?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000470: Check whether Cloud Internet Services (CIS) has TLS mode set to End-to-End CA signed](https://cloud.ibm.com/security-compliance/goals/3000470?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000701: Check whether App ID webhooks are using HTTPS only](https://cloud.ibm.com/security-compliance/goals/3000701?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000702: Check whether App ID email dispatchers are using HTTPS only](https://cloud.ibm.com/security-compliance/goals/3000702?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000703: Check whether App ID redirect URIs are using HTTPS only](https://cloud.ibm.com/security-compliance/goals/3000703?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000906: Check whether OpenShift Ingress is configured with at least TLS v1.2 for all inbound traffic](https://cloud.ibm.com/security-compliance/goals/3000906?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
