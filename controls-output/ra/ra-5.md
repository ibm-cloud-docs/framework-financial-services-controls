---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-08"
keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# RA-5 - Vulnerability Scanning
{: #ra-5}

## Requirements
{: #requirements}

The organization:

- a. Scans for vulnerabilities in the information system and hosted applications [weekly operating system/infrastructure and databases; weekly container images; quarterly web applications; annual source code/static analysis] and when new vulnerabilities potentially affecting the system/applications are identified and reported;

- b. Employs vulnerability scanning tools and techniques that facilitate interoperability among tools and automate parts of the vulnerability management process by using standards for:

  - 1. Enumerating platforms, software flaws, and improper configurations;
  - 2. Formatting checklists and test procedures; and
  - 3. Measuring vulnerability impact;

- c. Analyzes vulnerability scan reports and results from security control assessments;

- d. Remediates legitimate vulnerabilities [Priority 1 (very high), such as publicly known vulnerabilities with very high likelihood and impact, must be mitigated within four (4) days from date of discovery; Priority 2 (high), such as vulnerabilities with high likelihood and high impact, must be remediated within 45 days; Priority 3 (moderate), such as vulnerabilities with moderate likelihood and impact, must be remediated within 100 days; Priority 4 (low) and 5 (very low) have no specific remediation period unless otherwise directed.  Refer to table I-2 in NIST SP 800-30 for additional guidance on assessing risk] in accordance with an organizational assessment of risk; and

- e. Shares information obtained from the vulnerability scanning process and security control assessments with [organization-defined personnel or roles] to help eliminate similar vulnerabilities in other information systems (i.e., systemic weaknesses or deficiencies).

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

The organization must remediate all Priority 1 (critical/high risk) and Priority 2 (moderate risk) vulnerabilities identified in new applications, releases, or public-facing systems before rolling out to production.

All software/technology is upgraded to a supported version and kept up to date.

## Control Supplemental Guidance
{: #supplemental-guidance}

Security categorization of information systems guides the frequency and comprehensiveness of vulnerability scans. Organizations determine the required vulnerability scanning for all information system components, ensuring that potential sources of vulnerabilities such as networked printers, scanners, and copiers are not overlooked. Vulnerability analyses for custom software applications may require additional approaches such as static analysis, dynamic analysis, binary analysis, or a hybrid of the three approaches. Organizations can employ these analysis approaches in a variety of tools (e.g., web-based application scanners, static analysis tools, binary analyzers) and in source code reviews. Vulnerability scanning includes, for example: (i) scanning for patch levels; (ii) scanning for functions, ports, protocols, and services that should not be accessible to users or devices; and (iii) scanning for improperly configured or incorrectly operating information flow control mechanisms. Organizations consider using tools that express vulnerabilities in the Common Vulnerabilities and Exposures (CVE) naming convention and that use the Open Vulnerability Assessment Language (OVAL) to determine/test for the presence of vulnerabilities. Suggested sources for vulnerability information include the Common Weakness Enumeration (CWE) listing and the National Vulnerability Database (NVD). In addition, security control assessments such as red team exercises provide other sources of potential vulnerabilities for which to scan. Organizations also consider using tools that express vulnerability impact by the Common Vulnerability Scoring System (CVSS).

| Parameter ID | Values | Label or Choices |
|---|---|---|
| ra-5_prm_1 | weekly operating system/infrastructure and databases; weekly container images; quarterly web applications; annual source code/static analysis | organization-defined frequency and/or randomly in accordance with organization-defined process |
| ra-5_prm_2 | Priority 1 (very high), such as publicly known vulnerabilities with very high likelihood and impact, must be mitigated within four (4) days from date of discovery; Priority 2 (high), such as vulnerabilities with high likelihood and high impact, must be remediated within 45 days; Priority 3 (moderate), such as vulnerabilities with moderate likelihood and impact, must be remediated within 100 days; Priority 4 (low) and 5 (very low) have no specific remediation period unless otherwise directed.  Refer to table I-2 in NIST SP 800-30 for additional guidance on assessing risk | organization-defined response times |
| ra-5_prm_3 |  | organization-defined personnel or roles |


## Related Resources
{: #related_resources}

See the resources that follow to learn more about how to implement this control.

- [Development processes and software integrity](/docs/framework-financial-services?topic=framework-financial-services-shared-development-processes)

