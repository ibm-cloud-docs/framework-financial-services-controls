---

copyright:
  years: 2020, 2023

lastupdated: "2023-04-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# RA-5 (3) - Breadth / Depth of Coverage
{: #ra-5.3}

## Control requirements
{: #control-requirements}

RA-5 (3) - 0
    : The organization employs vulnerability scanning procedures that can identify the breadth and depth of coverage (i.e., information system components scanned and vulnerabilities checked).

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





