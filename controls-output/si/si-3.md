---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-24"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# SI-3 - Malicious Code Protection
{: #si-3}

## Requirements
{: #requirements}

The organization:

(a) Employs malicious code protection mechanisms at information system entry and exit points to detect and eradicate malicious code;

(b) Updates malicious code protection mechanisms whenever new releases are available in accordance with organizational configuration management policy and procedures;

(c) Configures malicious code protection mechanisms to:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(1) Perform periodic scans of the information system [at least weekly] and real-time scans of files from external sources at [to include endpoints, including removable media and devices (e.g., USB drives, CD/DVDs)] as the files are downloaded, opened, or executed in accordance with organizational security policy; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(2) [to include alerting administrator or defined security personnel] in response to malicious code detection; and

(d) Addresses the receipt of false positives during malicious code detection and eradication and the resulting potential impact on the availability of the information system.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement | Goals |
|-------------|-------|
| Part a | - 3000601: Check whether Container Registry Vulnerability Advisor scans for critical or high vulnerabilities in the system at least every # day(s) \n - 3000611: Check whether Container Registry Vulnerability Advisor scans images for OS vulnerability detection | 
{: caption="Goals for SI-3" caption-side="top"}

## NIST supplemental guidance
{: #supplemental-guidance}

Information system entry and exit points include, for example, firewalls, electronic mail servers, web servers, proxy servers, remote-access servers, workstations, notebook computers, and mobile devices. Malicious code includes, for example, viruses, worms, Trojan horses, and spyware. Malicious code can also be encoded in various formats (e.g., UUENCODE, Unicode), contained within compressed or hidden files, or hidden in files using steganography. Malicious code can be transported by different means including, for example, web accesses, electronic mail, electronic mail attachments, and portable storage devices. Malicious code insertions occur through the exploitation of information system vulnerabilities. Malicious code protection mechanisms include, for example, anti-virus signature definitions and reputation-based technologies. A variety of technologies and methods exist to limit or eliminate the effects of malicious code. Pervasive configuration management and comprehensive software integrity controls may be effective in preventing execution of unauthorized code. In addition to commercial off-the-shelf software, malicious code may also be present in custom-built software. This could include, for example, logic bombs, back doors, and other types of cyber attacks that could affect organizational missions/business functions. Traditional malicious code protection mechanisms cannot always detect such code. In these situations, organizations rely instead on other safeguards including, for example, secure coding practices, configuration management and control, trusted procurement processes, and monitoring practices to help ensure that software does not perform functions other than the functions intended. Organizations may determine that in response to the detection of malicious code, different actions may be warranted. For example, organizations can define actions in response to malicious code detection during periodic scans, actions in response to detection of malicious downloads, and/or actions in response to detection of maliciousness when attempting to open or execute files.

