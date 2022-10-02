---

copyright:
  years: 2020, 2022

lastupdated: "2022-10-02"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# AU-5 - Response to Audit Processing Failures
{: #au-5}

## Control requirements
{: #control-requirements}

The information system:

AU-5 (a)
    : Alerts _[organization-defined personnel or roles]_ in the event of an audit processing failure; and

AU-5 (b)
    : Takes the following additional actions: _[organization-defined actions to be taken (overwrite oldest record)]_.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- The status of all security audit log sources must be monitored for integrity and functionality as designed, at least hourly, and following policy changes, patch updates, and changes.

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Audit processing failures include, for example, software/hardware errors, failures in the audit capturing mechanisms, and audit storage capacity being reached or exceeded. Organizations may choose to define additional actions for different audit processing failures (e.g., by type, by location, by severity, or a combination of such factors). This control applies to each audit data storage repository (i.e., distinct information system component where audit records are stored), the total audit storage capacity of organizations (i.e., all audit data storage repositories combined), or both.



