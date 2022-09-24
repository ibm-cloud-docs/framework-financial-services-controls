---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-24"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

         
# AU-5 - Response To Audit Processing Failures
{: #au-5}

## Requirements
{: #requirements}

The information system:

- (a) Alerts _[organization-defined personnel or roles]_ in the event of an audit processing failure; and
- (b) Takes the following additional actions: _[organization-defined actions to be taken (overwrite oldest record)]_.

## Additional IBM Cloud for Financial Services specifications
{: #additional-fs-cloud-specifications}

- The status of all security audit log sources must be monitored for integrity and functionality as designed, at least hourly, and following policy changes, patch updates, and changes.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Audit logging of {{site.data.keyword.cloud_notm}} events](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit)
- [Audit logging of application provider events and SIEM](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit-provider)
- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)

## NIST supplemental guidance
{: #supplemental-guidance}

Audit processing failures include, for example, software/hardware errors, failures in the audit capturing mechanisms, and audit storage capacity being reached or exceeded. Organizations may choose to define additional actions for different audit processing failures (e.g., by type, by location, by severity, or a combination of such factors). This control applies to each audit data storage repository (i.e., distinct information system component where audit records are stored), the total audit storage capacity of organizations (i.e., all audit data storage repositories combined), or both.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| au-5_prm_1 |  | organization-defined personnel or roles |
| au-5_prm_2 | organization-defined actions to be taken (overwrite oldest record) | organization-defined actions to be taken (e.g., shut down information system, overwrite oldest audit records, stop generating audit records) |

