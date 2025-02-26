---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# SI-3 - Malicious Code Protection
{: #si-3}

## Control requirements
{: #control-requirements}



### SI-3 (a)


Implement _[Selection (one or more): signature based; non-signature based]_ malicious code protection mechanisms at system entry and exit points to detect and eradicate malicious code.


### SI-3 (b)


Automatically update malicious code protection mechanisms as new releases are available in accordance with organizational configuration management policy and procedures.


### SI-3 (c)


Configure malicious code protection mechanisms to:
1. Perform periodic scans of the system _[IBM Assignment: at least weekly]_ and real-time scans of files from external sources at _[IBM Assignment: to include endpoints, including removable media and devices (e.g., USB drives, CD/DVDs)]_ as the files are downloaded, opened, or executed in accordance with organizational policy; and
2. _[IBM Assignment: to include alerting administrator or defined security personnel]_; and send alert to __##1 in response to malicious code detection.


### SI-3 (d)


Address the receipt of false positives during malicious code detection and eradication and the resulting potential impact on the availability of the system.












## NIST supplemental guidance
{: #nist-supplemental-guidance}

System entry and exit points include firewalls, remote access servers, workstations, electronic mail servers, web servers, proxy servers, notebook computers, and mobile devices. Malicious code includes viruses, worms, Trojan horses, and spyware. Malicious code can also be encoded in various formats contained within compressed or hidden files or hidden in files using techniques such as steganography. Malicious code can be inserted into systems in a variety of ways, including by electronic mail, the world-wide web, and portable storage devices. Malicious code insertions occur through the exploitation of system vulnerabilities. A variety of technologies and methods exist to limit or eliminate the effects of malicious code.
Malicious code protection mechanisms include both signature- and nonsignature-based technologies. Nonsignature-based detection mechanisms include artificial intelligence techniques that use heuristics to detect, analyze, and describe the characteristics or behavior of malicious code and to provide controls against such code for which signatures do not yet exist or for which existing signatures may not be effective. Malicious code for which active signatures do not yet exist or may be ineffective includes polymorphic malicious code (i.e., code that changes signatures when it replicates). Nonsignature-based mechanisms also include reputation-based technologies. In addition to the above technologies, pervasive configuration management, comprehensive software integrity controls, and anti-exploitation software may be effective in preventing the execution of unauthorized code. Malicious code may be present in commercial off-the-shelf software as well as custom-built software and could include logic bombs, backdoors, and other types of attacks that could affect organizational mission and business functions.
In situations where malicious code cannot be detected by detection methods or technologies, organizations rely on other types of controls, including secure coding practices, configuration management and control, trusted procurement processes, and monitoring practices to ensure that software does not perform functions other than the functions intended. Organizations may determine that, in response to the detection of malicious code, different actions may be warranted. For example, organizations can define actions in response to malicious code detection during periodic scans, the detection of malicious downloads, or the detection of maliciousness when attempting to open or execute files.
