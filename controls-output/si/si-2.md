---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# SI-2 - Flaw Remediation
{: #si-2}

## Control requirements
{: #control-requirements}



### SI-2 (a)


Identify, report, and correct system flaws.


### SI-2 (b)


Test software and firmware updates related to flaw remediation for effectiveness and potential side effects before installation.


### SI-2 (c)


Install security-relevant software and firmware updates within _[IBM Assignment: RA-5 (d) timeframes]_ of the release of the updates.


### SI-2 (d)


Incorporate flaw remediation into the organizational configuration management process.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

The organization must remediate vulnerability findings in accordance with customer remediation requirements.  

All software/technology is upgraded to the most up to date supported version.




## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.


- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)






## NIST supplemental guidance
{: #nist-supplemental-guidance}

The need to remediate system flaws applies to all types of software and firmware. Organizations identify systems affected by software flaws, including potential vulnerabilities resulting from those flaws, and report this information to designated organizational personnel with information security and privacy responsibilities. Security-relevant updates include patches, service packs, and malicious code signatures. Organizations also address flaws discovered during assessments, continuous monitoring, incident response activities, and system error handling. By incorporating flaw remediation into configuration management processes, required remediation actions can be tracked and verified.
Organization-defined time periods for updating security-relevant software and firmware may vary based on a variety of risk factors, including the security category of the system, the criticality of the update (i.e., severity of the vulnerability related to the discovered flaw), the organizational risk tolerance, the mission supported by the system, or the threat environment. Some types of flaw remediation may require more testing than other types. Organizations determine the type of testing needed for the specific type of flaw remediation activity under consideration and the types of changes that are to be configuration-managed. In some situations, organizations may determine that the testing of software or firmware updates is not necessary or practical, such as when implementing simple malicious code signature updates. In testing decisions, organizations consider whether security-relevant software or firmware updates are obtained from authorized sources with appropriate digital signatures.
