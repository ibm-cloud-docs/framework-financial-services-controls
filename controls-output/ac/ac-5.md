---

copyright:
  years: 2020, 2022

lastupdated: "2022-10-02"

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
    : Separates _[organization-defined duties of individuals]_;

AC-5 (b)
    : Documents separation of duties of individuals; and

AC-5 (c)
    : Defines information system access authorizations to support separation of duties.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- Ensure segregation exists such that no one individual has the authority/ability to develop, compile and/or move object code from non-production environments into production environments.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.6.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Goals |
|----------------|-------|
| AC-5 (c) | - 3000009: Check whether IAM roles are used to create IAM policies for IBM resources \n - 3000015: Check whether IAM users are attached to at least one access group \n - 3000016: Check whether IAM policies for users are attached only to groups or roles \n - 3000027: Check whether permissions for API key creation are limited and configured in IAM settings for the account owner \n - 3000035: Check whether account service access is managed only by IAM access groups \n - 3000106: Check whether Cloud Object Storage bucket access is restricted by using IAM and S3 access control \n - 3000707: Check whether App ID user profile updates from client apps is disabled \n - 3000708: Check whether App ID Cloud Directory users aren't able to update their own accounts \n - 3000709: Check whether App ID Cloud Directory users aren't able to self-sign up to applications | 
{: caption="Goals for AC-5 in IBM Cloud for Financial Services v0.6.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Separation of duties addresses the potential for abuse of authorized privileges and helps to reduce the risk of malevolent activity without collusion. Separation of duties includes, for example: (i) dividing mission functions and information system support functions among different individuals and/or roles; (ii) conducting information system support functions with different individuals (e.g., system management, programming, configuration management, quality assurance and testing, and network security); and (iii) ensuring security personnel administering access control functions do not also administer audit functions.



