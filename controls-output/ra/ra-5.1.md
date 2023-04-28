---

copyright:
  years: 2020, 2023

lastupdated: "2023-04-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# RA-5 (1) - Update Tool Capability
{: #ra-5.1}

## Control requirements
{: #control-requirements}

RA-5 (1) - 0
    : The organization employs vulnerability scanning tools that include the capability to readily update the information system vulnerabilities to be scanned.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- Check whether DevSecOps Toolchain scans build artifacts to identify vulnerabilities 
- Check whether Container Registry Vulnerability Advisor scans for critical or high vulnerabilities in the system at least every # day(s) 
- Check whether DevSecOps Toolchain validates code against Center for Internet Security (CIS) Docker benchmarks to ensure container runtimes are configured securely 
- Check whether DevSecOps Toolchain passes dynamic code scan to identify vulnerabilities in deployed artifacts 
- Check whether DevSecOps Toolchain scans source code and their dependencies to identify vulnerabilities 
- Check whether DevSecOps Toolchain source code contains no secrets 
- Check whether DevSecOps Toolchain passes static code scan to identify vulnerabilities in source code

## NIST supplemental guidance
{: #nist-supplemental-guidance}

The vulnerabilities to be scanned need to be readily updated as new vulnerabilities are discovered, announced, and scanning methods developed. This updating process helps to ensure that potential vulnerabilities in the information system are identified and addressed as quickly as possible.





