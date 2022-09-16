---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-16"
keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# AC-6 - Least Privilege
{: #ac-6}

## Requirements
{: #requirements}

The organization employs the principle of least privilege, allowing only authorized accesses for users (or processes acting on behalf of users) which are necessary to accomplish assigned tasks in accordance with organizational missions and business functions.

## Additional IBM Cloud for Financial Services specifications
{: #additional-fs-cloud-specifications}

Individual users are not permitted to interact with system-to-system service accounts.

## NIST supplemental guidance
{: #supplemental-guidance}

Organizations employ least privilege for specific duties and information systems. The principle of least privilege is also applied to information system processes, ensuring that the processes operate at privilege levels no higher than necessary to accomplish required organizational missions/business functions. Organizations consider the creation of additional processes, roles, and information system accounts as necessary, to achieve least privilege. Organizations also apply least privilege to the development, implementation, and operation of organizational information systems.


## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Organizing {{site.data.keyword.cloud_notm}} accounts and resources](/docs/framework-financial-services?topic=framework-financial-services-shared-account-organization)
- [Consumer accounts for application provider workloads](/docs/framework-financial-services?topic=framework-financial-services-shared-account-consumer)
- [Access management in {{site.data.keyword.cloud_notm}}](/docs/framework-financial-services?topic=framework-financial-services-shared-account-access-management)

## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- 3000009: Check whether IAM roles are used to create IAM policies for IBM resources
- 3000015: Check whether IAM users are attached to at least one access group
- 3000016: Check whether IAM policies for users are attached only to groups or roles
- 3000022: Check whether Cloud Object Storage public access is disabled in IAM settings (not applicable to ACLs managed using S3 APIs)
- 3000023: Check whether the account owner does not have an IBM Cloud API key created in IAM
- 3000026: Check whether user list visibility restrictions are configured in IAM settings for the account owner
- 3000027: Check whether permissions for API key creation are limited and configured in IAM settings for the account owner
- 3000028: Check whether permissions for service ID creation are limited and configured in IAM settings for the account owner
- 3000035: Check whether account service access is managed only by IAM access groups
- 3000106: Check whether Cloud Object Storage bucket access is restricted by using IAM and S3 access control
- 3000708: Check whether App ID Cloud Directory users aren't able to update their own accounts
