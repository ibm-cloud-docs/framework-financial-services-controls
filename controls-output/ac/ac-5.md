---

copyright:
  years: 2020, 2023

lastupdated: "2023-03-08"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# AC-5 - Separation of Duties
{: #ac-5}

## Control requirements
{: #control-requirements}

The organization:

AC-5 (a)
    : Separates _[Assignment: organization-defined duties of individuals]_;

AC-5 (b)
    : Documents separation of duties of individuals; and

AC-5 (c)
    : Defines information system access authorizations to support separation of duties.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- Ensure segregation exists such that no one individual has the authority/ability to develop, compile and/or move object code from non-production environments into production environments.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Access management in {{site.data.keyword.cloud_notm}}](/docs/framework-financial-services?topic=framework-financial-services-shared-account-access-management)
- [Consumer accounts for application provider workloads](/docs/framework-financial-services?topic=framework-financial-services-shared-account-consumer)
- [Organizing {{site.data.keyword.cloud_notm}} accounts and resources](/docs/framework-financial-services?topic=framework-financial-services-shared-account-organization)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.1.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Rules |
|----------------|-------|
| AC-5 (c) | - Check whether permissions for API key creation are limited and configured in IAM settings for the account owner \n - Check whether App ID Cloud Directory users aren't able to update their own accounts \n - Check whether IAM roles are used to create IAM policies for IBM resources \n - Check whether IAM users are attached to at least one access group \n - Check whether App ID Cloud Directory users aren't able to self-sign up to applications \n - Check whether App ID user profile updates from client apps is disabled | 
{: caption="Rules for AC-5 in IBM Cloud for Financial Services v1.1.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Separation of duties addresses the potential for abuse of authorized privileges and helps to reduce the risk of malevolent activity without collusion. Separation of duties includes, for example: (i) dividing mission functions and information system support functions among different individuals and/or roles; (ii) conducting information system support functions with different individuals (e.g., system management, programming, configuration management, quality assurance and testing, and network security); and (iii) ensuring security personnel administering access control functions do not also administer audit functions.





