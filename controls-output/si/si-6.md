---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-02"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# SI-6 - Security Function Verification
{: #si-6}

## Requirements
{: #requirements}

The information system:

- \[a.\] Verifies the correct operation of [organization-defined security functions];

- \[b.\] Performs this verification [to include upon system startup and/or restart and at least monthly];

- \[c.\] Notifies [to include system administrators and security personnel] of failed security verification tests; and

- \[d.\] [shuts the information system down; restarts the information system; to include notification of system administrators and security personnel] when anomalies are discovered.

## Control Supplemental Guidance
{: #supplemental-guidance}

Transitional states for information systems include, for example, system startup, restart, shutdown, and abort. Notifications provided by information systems include, for example, electronic alerts to system administrators, messages to local computer consoles, and/or hardware indications such as lights.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| si-6_prm_1 |  | organization-defined security functions |
| si-6_prm_2 | to include upon system startup and/or restart and at least monthly | Choose one or more: organization-defined system transitional states; upon command by user with appropriate privilege; organization-defined frequency |
| si-6_prm_3 |  | organization-defined system transitional states |
| si-6_prm_4 |  | organization-defined frequency |
| si-6_prm_5 | to include system administrators and security personnel | organization-defined personnel or roles |
| si-6_prm_6 |  | Choose one or more: shuts the information system down; restarts the information system; to include notification of system administrators and security personnel |
| si-6_prm_7 | to include notification of system administrators and security personnel | organization-defined alternative action(s) |

