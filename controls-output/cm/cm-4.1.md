---

copyright:
  years: 2020, 2023

lastupdated: "2023-04-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# CM-4 (1) - Separate Test Environments
{: #cm-4.1}

## Control requirements
{: #control-requirements}

CM-4 (1) - 0
    : The organization analyzes changes to the information system in a separate test environment before implementation in an operational environment, looking for security impacts due to flaws, weaknesses, incompatibility, or intentional malice.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- The test environment must mirror the production environment.
- Customer data must not be placed into non-production environments.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- Check whether DevSecOps Toolchain scans build artifacts to identify vulnerabilities 
- Check whether DevSecOps Toolchain validates code against Center for Internet Security (CIS) Docker benchmarks to ensure container runtimes are configured securely 
- Check whether DevSecOps Toolchain passes dynamic code scan to identify vulnerabilities in deployed artifacts 
- Check whether DevSecOps Toolchain scans source code and their dependencies to identify vulnerabilities 
- Check whether DevSecOps Toolchain source code contains no secrets 
- Check whether DevSecOps Toolchain passes static code scan to identify vulnerabilities in source code 
- Check whether DevSecOps Toolchain passes acceptance tests to validate every deployment

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Separate test environment in this context means an environment that is physically or logically isolated and distinct from the operational environment. The separation is sufficient to ensure that activities in the test environment do not impact activities in the operational environment, and information in the operational environment is not inadvertently transmitted to the test environment. Separate environments can be achieved by physical or logical means. If physically separate test environments are not used, organizations determine the strength of mechanism required when implementing logical separation (e.g., separation achieved through virtual machines).





