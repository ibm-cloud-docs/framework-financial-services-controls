---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-08"
keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# SI-2 - Flaw Remediation
{: #si-2}

## Requirements
{: #requirements}

The organization:

- a. Identifies, reports, and corrects information system flaws;

- b. Tests software and firmware updates related to flaw remediation for effectiveness and potential side effects before installation;

- c. Installs security-relevant software and firmware updates within [RA-5 (d) timeframes] of the release of the updates; and

- d. Incorporates flaw remediation into the organizational configuration management process.

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

The organization must remediate vulnerability findings in accordance with customer remediation requirements.  

All software/technology is upgraded to a supported version and kept up to date.

## Control Supplemental Guidance
{: #supplemental-guidance}

Organizations identify information systems affected by announced software flaws including potential vulnerabilities resulting from those flaws, and report this information to designated organizational personnel with information security responsibilities. Security-relevant software updates include, for example, patches, service packs, hot fixes, and anti-virus signatures. Organizations also address flaws discovered during security assessments, continuous monitoring, incident response activities, and system error handling. Organizations take advantage of available resources such as the Common Weakness Enumeration (CWE) or Common Vulnerabilities and Exposures (CVE) databases in remediating flaws discovered in organizational information systems. By incorporating flaw remediation into ongoing configuration management processes, required/anticipated remediation actions can be tracked and verified. Flaw remediation actions that can be tracked and verified include, for example, determining whether organizations follow US-CERT guidance and Information Assurance Vulnerability Alerts. Organization-defined time periods for updating security-relevant software and firmware may vary based on a variety of factors including, for example, the security category of the information system or the criticality of the update (i.e., severity of the vulnerability related to the discovered flaw). Some types of flaw remediation may require more testing than other types. Organizations determine the degree and type of testing needed for the specific type of flaw remediation activity under consideration and also the types of changes that are to be configuration-managed. In some situations, organizations may determine that the testing of software and/or firmware updates is not necessary or practical, for example, when implementing simple anti-virus signature updates. Organizations may also consider in testing decisions, whether security-relevant software or firmware updates are obtained from authorized sources with appropriate digital signatures.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| si-2_prm_1 | RA-5 (d) timeframes | organization-defined time period |


## Related Resources
{: #related_resources}

See the resources that follow to learn more about how to implement this control.

- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)

