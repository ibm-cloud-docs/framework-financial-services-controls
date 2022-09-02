---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-02"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# AC-7 - Unsuccessful Logon Attempts
{: #ac-7}

## Requirements
{: #requirements}

The information system:

- \[a.\] Enforces a limit of [not more than five (5)] consecutive invalid logon attempts by a user during a [fifteen (15) minutes]; and

- \[b.\] Automatically [locks the account/node for a thirty (30) minutes] when the maximum number of unsuccessful attempts is exceeded.

## Control Supplemental Guidance
{: #supplemental-guidance}

This control applies regardless of whether the logon occurs via a local or network connection. Due to the potential for denial of service, automatic lockouts initiated by information systems are usually temporary and automatically release after a predetermined time period established by organizations. If a delay algorithm is selected, organizations may choose to employ different algorithms for different information system components based on the capabilities of those components. Responses to unsuccessful logon attempts may be implemented at both the operating system and the application levels.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| ac-7_prm_1 | not more than five (5) | organization-defined number |
| ac-7_prm_2 | fifteen (15) minutes | organization-defined time period |
| ac-7_prm_3 | locks the account/node for a thirty (30) minutes | Choose : locks the account/node for an organization-defined time period; locks the account/node until released by an administrator; delays next logon prompt according to organization-defined delay algorithm |
| ac-7_prm_4 |  | organization-defined time period |
| ac-7_prm_5 |  | organization-defined delay algorithm |

