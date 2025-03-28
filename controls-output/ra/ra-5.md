---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# RA-5 - Vulnerability Monitoring and Scanning
{: #ra-5}

## Control requirements
{: #control-requirements}



### RA-5 (a)


Monitor and scan for vulnerabilities in the system and hosted applications _[IBM Assignment: weekly operating system/infrastructure and databases; weekly container images; quarterly web applications; annual source code/static analysis]_ and when new vulnerabilities potentially affecting the system are identified and reported.


### RA-5 (b)


Employ vulnerability monitoring tools and techniques that facilitate interoperability among tools and automate parts of the vulnerability management process by using standards for:
1. Enumerating platforms, software flaws, and improper configurations;
2. Formatting checklists and test procedures; and
3. Measuring vulnerability impact.


### RA-5 (c)


Analyze vulnerability scan reports and results from vulnerability monitoring.


### RA-5 (d)


Remediate legitimate vulnerabilities _[IBM Assignment: Priority 1 (very high), such as publicly known vulnerabilities with very high likelihood and impact, must be mitigated within four (4) days from date of discovery; Priority 2 (high), such as vulnerabilities with high likelihood and high impact, must be remediated within 45 days; Priority 3 (moderate), such as vulnerabilities with moderate likelihood and impact, must be remediated within 100 days; Priority 4 (low) and 5 (very low) have no specific remediation period unless otherwise directed.  Refer to table I-2 in NIST SP 800-30 for additional guidance on assessing risk]_ in accordance with an organizational assessment of risk.


### RA-5 (e)


Share information obtained from the vulnerability monitoring process and control assessments with _[Assignment: organization-defined personnel or roles]_ to help eliminate similar vulnerabilities in other systems.


### RA-5 (f)


Employ vulnerability monitoring tools that include the capability to readily update the vulnerabilities to be scanned.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

The organization must remediate all Priority 1 (critical/high risk) and Priority 2 (moderate risk) vulnerabilities identified in new applications, releases, or public-facing systems before rolling out to production.

All software/technology is upgraded to the most up to date supported version.




## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.


- [Development processes and software integrity](/docs/framework-financial-services?topic=framework-financial-services-shared-development-processes)






## NIST supplemental guidance
{: #nist-supplemental-guidance}

Security categorization of information and systems guides the frequency and comprehensiveness of vulnerability monitoring (including scans). Organizations determine the required vulnerability monitoring for system components, ensuring that the potential sources of vulnerabilities—such as infrastructure components (e.g., switches, routers, guards, sensors), networked printers, scanners, and copiers—are not overlooked. The capability to readily update vulnerability monitoring tools as new vulnerabilities are discovered and announced and as new scanning methods are developed helps to ensure that new vulnerabilities are not missed by employed vulnerability monitoring tools. The vulnerability monitoring tool update process helps to ensure that potential vulnerabilities in the system are identified and addressed as quickly as possible. Vulnerability monitoring and analyses for custom software may require additional approaches, such as static analysis, dynamic analysis, binary analysis, or a hybrid of the three approaches. Organizations can use these analysis approaches in source code reviews and in a variety of tools, including web-based application scanners, static analysis tools, and binary analyzers.
Vulnerability monitoring includes scanning for patch levels; scanning for functions, ports, protocols, and services that should not be accessible to users or devices; and scanning for flow control mechanisms that are improperly configured or operating incorrectly. Vulnerability monitoring may also include continuous vulnerability monitoring tools that use instrumentation to continuously analyze components. Instrumentation-based tools may improve accuracy and may be run throughout an organization without scanning. Vulnerability monitoring tools that facilitate interoperability include tools that are Security Content Automated Protocol (SCAP)-validated. Thus, organizations consider using scanning tools that express vulnerabilities in the Common Vulnerabilities and Exposures (CVE) naming convention and that employ the Open Vulnerability Assessment Language (OVAL) to determine the presence of vulnerabilities. Sources for vulnerability information include the Common Weakness Enumeration (CWE) listing and the National Vulnerability Database (NVD). Control assessments, such as red team exercises, provide additional sources of potential vulnerabilities for which to scan. Organizations also consider using scanning tools that express vulnerability impact by the Common Vulnerability Scoring System (CVSS).
Vulnerability monitoring includes a channel and process for receiving reports of security vulnerabilities from the public at-large. Vulnerability disclosure programs can be as simple as publishing a monitored email address or web form that can receive reports, including notification authorizing good-faith research and disclosure of security vulnerabilities. Organizations generally expect that such research is happening with or without their authorization and can use public vulnerability disclosure channels to increase the likelihood that discovered vulnerabilities are reported directly to the organization for remediation.
Organizations may also employ the use of financial incentives (also known as “bug bounties”) to further encourage external security researchers to report discovered vulnerabilities. Bug bounty programs can be tailored to the organization’s needs. Bounties can be operated indefinitely or over a defined period of time and can be offered to the general public or to a curated group. Organizations may run public and private bounties simultaneously and could choose to offer partially credentialed access to certain participants in order to evaluate security vulnerabilities from privileged vantage points.
