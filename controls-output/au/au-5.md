---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-02"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# AU-5 - Response To Audit Processing Failures
{: #au-5}

## Requirements
{: #requirements}

The information system:

- \[a.\] Alerts [organization-defined personnel or roles] in the event of an audit processing failure; and

- \[b.\] Takes the following additional actions: [organization-defined actions to be taken (overwrite oldest record)].

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

The status of all security audit log sources must be monitored for integrity and functionality as designed, at least hourly, and following policy changes, patch updates, and changes.

## Control Supplemental Guidance
{: #supplemental-guidance}

Audit processing failures include, for example, software/hardware errors, failures in the audit capturing mechanisms, and audit storage capacity being reached or exceeded. Organizations may choose to define additional actions for different audit processing failures (e.g., by type, by location, by severity, or a combination of such factors). This control applies to each audit data storage repository (i.e., distinct information system component where audit records are stored), the total audit storage capacity of organizations (i.e., all audit data storage repositories combined), or both.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| au-5_prm_1 |  | organization-defined personnel or roles |
| au-5_prm_2 | organization-defined actions to be taken (overwrite oldest record) | organization-defined actions to be taken (e.g., shut down information system, overwrite oldest audit records, stop generating audit records) |

