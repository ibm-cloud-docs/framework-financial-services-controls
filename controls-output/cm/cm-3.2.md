---

copyright:
  years: 2020, 2023

lastupdated: "2023-04-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# CM-3 (2) - Test / Validate / Document Changes
{: #cm-3.2}

## Control requirements
{: #control-requirements}

CM-3 (2) - 0
    : The organization tests, validates, and documents changes to the information system before implementing the changes on the operational system.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- Test programs, scripts, or code must not be placed into customer environments.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- Check whether DevSecOps Toolchain scans build artifacts to identify vulnerabilities 
- Check whether DevSecOps Toolchain verifies source code branch protection rules to enforce security policies 
- Check whether DevSecOps Toolchain validates code against Center for Internet Security (CIS) Docker benchmarks to ensure container runtimes are configured securely 
- Check whether DevSecOps Toolchain passes dynamic code scan to identify vulnerabilities in deployed artifacts 
- Check whether DevSecOps Toolchain scans source code and their dependencies to identify vulnerabilities 
- Check whether DevSecOps Toolchain source code contains no secrets 
- Check whether DevSecOps Toolchain passes static code scan to identify vulnerabilities in source code 
- Check whether DevSecOps Toolchain collects software bills of materials (SBOM) to provide transparency in build artifacts 
- Check whether DevSecOps Toolchain passes unit tests to validate all code changes 
- Check whether Toolchain is configured only with the allowed integration tools 
- Check whether DevSecOps Toolchain passes acceptance tests to validate every deployment 
- Check whether DevSecOps Toolchain signs build artifacts to attest their provenance 
- Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Changes to information systems include modifications to hardware, software, or firmware components and configuration settings defined in CM-6. Organizations ensure that testing does not interfere with information system operations. Individuals/groups conducting tests understand organizational security policies and procedures, information system security policies and procedures, and the specific health, safety, and environmental risks associated with particular facilities/processes. Operational systems may need to be taken off-line, or replicated to the extent feasible, before testing can be conducted. If information systems must be taken off-line for testing, the tests are scheduled to occur during planned system outages whenever possible. If testing cannot be conducted on operational systems, organizations employ compensating controls (e.g., testing on replicated systems).





