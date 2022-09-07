---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-07"
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


## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

### Part a
{: #scc-fs-cloud-profile-a}

- [3000053: IBMid enforces a limit of 5 consecutive unsuccessful sign in attempts](https://cloud.ibm.com/security-compliance/goals/3000053?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000716: Check whether App ID lockout policy after failed # of sign-in attempts is enabled](https://cloud.ibm.com/security-compliance/goals/3000716?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}

### Part b
{: #scc-fs-cloud-profile-b}

- [3000054: IBMid automatically locks an account for 30 minutes after 5 consecutive unsuccessful sign in attempts](https://cloud.ibm.com/security-compliance/goals/3000054?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000717: Check whether App ID lockout policy after a maximum specified time is set to # minute(s)](https://cloud.ibm.com/security-compliance/goals/3000717?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
