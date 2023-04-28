---

copyright:
  years: 2020, 2023

lastupdated: "2023-04-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# SI-2 (2) - Automated Flaw Remediation Status
{: #si-2.2}

## Control requirements
{: #control-requirements}

SI-2 (2) - 0
    : The organization employs automated mechanisms [IBM Assignment: at least monthly] to determine the state of information system components with regard to flaw remediation.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Compliance monitoring](/docs/framework-financial-services?topic=framework-financial-services-shared-monitoring-compliance)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- Check whether DevSecOps Toolchain scans build artifacts to identify vulnerabilities 
- Check whether DevSecOps Toolchain verifies source code branch protection rules to enforce security policies 
- Check whether Container Registry Vulnerability Advisor scans for critical or high vulnerabilities in the system at least every # day(s) 
- Check whether OpenShift worker nodes are updated to the latest image to ensure patching of vulnerabilities 
- Check whether DevSecOps Toolchain validates code against Center for Internet Security (CIS) Docker benchmarks to ensure container runtimes are configured securely 
- Check whether DevSecOps Toolchain passes dynamic code scan to identify vulnerabilities in deployed artifacts 
- Check whether DevSecOps Toolchain scans source code and their dependencies to identify vulnerabilities 
- Check whether DevSecOps Toolchain source code contains no secrets 
- Check whether DevSecOps Toolchain passes static code scan to identify vulnerabilities in source code 
- Check whether DevSecOps Toolchain collects software bills of materials (SBOM) to provide transparency in build artifacts 
- Check whether DevSecOps Toolchain passes unit tests to validate all code changes 
- Check whether OpenShift version is up-to-date 
- Check whether DevSecOps Toolchain passes acceptance tests to validate every deployment 
- Check whether DevSecOps Toolchain signs build artifacts to attest their provenance 
- Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis





