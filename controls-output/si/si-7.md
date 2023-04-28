---

copyright:
  years: 2020, 2023

lastupdated: "2023-04-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# SI-7 - Software, Firmware, and Information Integrity
{: #si-7}

## Control requirements
{: #control-requirements}

SI-7 - 0
    : The organization employs integrity verification tools to detect unauthorized changes to [Assignment: organization-defined software, firmware, and information].

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Development processes and software integrity](/docs/framework-financial-services?topic=framework-financial-services-shared-development-processes)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- Check whether DevSecOps Toolchain verifies source code branch protection rules to enforce security policies 
- Check whether DevSecOps Toolchain collects software bills of materials (SBOM) to provide transparency in build artifacts 
- Check whether DevSecOps Toolchain signs build artifacts to attest their provenance 
- Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Unauthorized changes to software, firmware, and information can occur due to errors or malicious activity (e.g., tampering). Software includes, for example, operating systems (with key internal components such as kernels, drivers), middleware, and applications. Firmware includes, for example, the Basic Input Output System (BIOS). Information includes metadata such as security attributes associated with information. State-of-the-practice integrity-checking mechanisms (e.g., parity checks, cyclical redundancy checks, cryptographic hashes) and associated tools can automatically monitor the integrity of information systems and hosted applications.





