---

copyright:
  years: 2020, 2023

lastupdated: "2023-04-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# AC-7 - Unsuccessful Logon Attempts
{: #ac-7}

## Control requirements
{: #control-requirements}

The information system:

AC-7 (a)
    : Enforces a limit of _[IBM Assignment: not more than five (5)]_ consecutive invalid logon attempts by a user during a _[IBM Assignment: fifteen (15) minutes]_; and

AC-7 (b)
    : Automatically _[IBM Assignment: locks the account/node for a thirty (30) minutes]_ when the maximum number of unsuccessful attempts is exceeded.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- Internal privileged accounts must remain locked until released by an administrator.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Rules |
|----------------|-------|
| AC-7 (a) | - IBMid enforces a limit of 5 consecutive unsuccessful sign in attempts \n - Check whether App ID lockout policy after failed # of sign-in attempts is enabled \n - Check whether App ID lockout policy after failed # of sign-in attempts is enabled \n - Check whether App ID lockout policy after failed # of sign-in attempts is enabled \n - Check whether App ID avoid password reuse policy is enabled | 
| AC-7 (b) | - Check whether App ID lockout policy after failed # of sign-in attempts is enabled \n - Check whether App ID lockout policy after failed # of sign-in attempts is enabled \n - IBMid automatically locks an account for 30 minutes after 5 consecutive unsuccessful sign in attempts \n - Check whether App ID avoid password reuse policy is enabled \n - Check whether App ID lockout policy after a maximum specified time is set to # minute(s) | 
{: caption="Rules for AC-7 in IBM Cloud for Financial Services v1.2.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

This control applies regardless of whether the logon occurs via a local or network connection. Due to the potential for denial of service, automatic lockouts initiated by information systems are usually temporary and automatically release after a predetermined time period established by organizations. If a delay algorithm is selected, organizations may choose to employ different algorithms for different information system components based on the capabilities of those components. Responses to unsuccessful logon attempts may be implemented at both the operating system and the application levels.





