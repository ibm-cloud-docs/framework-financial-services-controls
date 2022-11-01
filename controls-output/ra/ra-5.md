---

copyright:
  years: 2020, 2022

lastupdated: "2022-11-01"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# RA-5 - Vulnerability Scanning
{: #ra-5}

## Control requirements
{: #control-requirements}

The organization:

RA-5 (a)
    : Scans for vulnerabilities in the information system and hosted applications _[[Assignment: organization-defined frequency and/or randomly in accordance with organization-defined process]_] and when new vulnerabilities potentially affecting the system/applications are identified and reported;

RA-5 (b)
    : Employs vulnerability scanning tools and techniques that facilitate interoperability among tools and automate parts of the vulnerability management process by using standards for:
      1. Enumerating platforms, software flaws, and improper configurations;
      2. Formatting checklists and test procedures; and
      3. Measuring vulnerability impact;

RA-5 (c)
    : Analyzes vulnerability scan reports and results from security control assessments;

RA-5 (d)
    : Remediates legitimate vulnerabilities _[[Assignment: organization-defined response times]_] in accordance with an organizational assessment of risk; and

RA-5 (e)
    : Shares information obtained from the vulnerability scanning process and security control assessments with _[[Assignment: organization-defined personnel or roles]_] to help eliminate similar vulnerabilities in other information systems (i.e., systemic weaknesses or deficiencies).

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- The organization must remediate all Priority 1 (critical/high risk) and Priority 2 (moderate risk) vulnerabilities identified in new applications, releases, or public-facing systems before rolling out to production.
- All software/technology is upgraded to the most up to date supported version.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Development processes and software integrity](/docs/framework-financial-services?topic=framework-financial-services-shared-development-processes)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.6.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Goals |
|----------------|-------|
| RA-5 (a) | - 3000601: Check whether Container Registry Vulnerability Advisor scans for critical or high vulnerabilities in the system at least every # day(s) \n - 3000611: Check whether Container Registry Vulnerability Advisor scans images for OS vulnerability detection | 
{: caption="Goals for RA-5 in IBM Cloud for Financial Services v0.6.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Security categorization of information systems guides the frequency and comprehensiveness of vulnerability scans. Organizations determine the required vulnerability scanning for all information system components, ensuring that potential sources of vulnerabilities such as networked printers, scanners, and copiers are not overlooked. Vulnerability analyses for custom software applications may require additional approaches such as static analysis, dynamic analysis, binary analysis, or a hybrid of the three approaches. Organizations can employ these analysis approaches in a variety of tools (e.g., web-based application scanners, static analysis tools, binary analyzers) and in source code reviews. Vulnerability scanning includes, for example: (i) scanning for patch levels; (ii) scanning for functions, ports, protocols, and services that should not be accessible to users or devices; and (iii) scanning for improperly configured or incorrectly operating information flow control mechanisms. Organizations consider using tools that express vulnerabilities in the Common Vulnerabilities and Exposures (CVE) naming convention and that use the Open Vulnerability Assessment Language (OVAL) to determine/test for the presence of vulnerabilities. Suggested sources for vulnerability information include the Common Weakness Enumeration (CWE) listing and the National Vulnerability Database (NVD). In addition, security control assessments such as red team exercises provide other sources of potential vulnerabilities for which to scan. Organizations also consider using tools that express vulnerability impact by the Common Vulnerability Scoring System (CVSS).





