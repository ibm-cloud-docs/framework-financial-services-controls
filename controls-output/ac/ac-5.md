---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-25"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

         
# AC-5 - Separation Of Duties
{: #ac-5}

## Requirements
{: #requirements}

The organization:

- (a) Separates _[organization-defined duties of individuals]_;
- (b) Documents separation of duties of individuals; and
- (c) Defines information system access authorizations to support separation of duties.

## Additional IBM Cloud for Financial Services specifications
{: #additional-fs-cloud-specifications}

- Ensure segregation exists such that no one individual has the authority/ability to develop, compile and/or move object code from non-production environments into production environments.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Organizing {{site.data.keyword.cloud_notm}} accounts and resources](/docs/framework-financial-services?topic=framework-financial-services-shared-account-organization)
- [Consumer accounts for application provider workloads](/docs/framework-financial-services?topic=framework-financial-services-shared-account-consumer)
- [Access management in {{site.data.keyword.cloud_notm}}](/docs/framework-financial-services?topic=framework-financial-services-shared-account-access-management)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement | Goals |
|-------------|-------|
| Part c | - 3000009: Check whether IAM roles are used to create IAM policies for IBM resources \n - 3000015: Check whether IAM users are attached to at least one access group \n - 3000016: Check whether IAM policies for users are attached only to groups or roles \n - 3000023: Check whether the account owner does not have an IBM Cloud API key created in IAM \n - 3000027: Check whether permissions for API key creation are limited and configured in IAM settings for the account owner \n - 3000035: Check whether account service access is managed only by IAM access groups \n - 3000106: Check whether Cloud Object Storage bucket access is restricted by using IAM and S3 access control \n - 3000707: Check whether App ID user profile updates from client apps is disabled \n - 3000708: Check whether App ID Cloud Directory users aren't able to update their own accounts \n - 3000709: Check whether App ID Cloud Directory users aren't able to self-sign up to applications | 
{: caption="Goals for AC-5" caption-side="top"}

## NIST supplemental guidance
{: #supplemental-guidance}

Separation of duties addresses the potential for abuse of authorized privileges and helps to reduce the risk of malevolent activity without collusion. Separation of duties includes, for example: (i) dividing mission functions and information system support functions among different individuals and/or roles; (ii) conducting information system support functions with different individuals (e.g., system management, programming, configuration management, quality assurance and testing, and network security); and (iii) ensuring security personnel administering access control functions do not also administer audit functions.



