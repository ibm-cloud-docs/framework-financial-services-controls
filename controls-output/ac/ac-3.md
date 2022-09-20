---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-20"

keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# AC-3 - Access Enforcement
{: #ac-3}

## Requirements
{: #requirements}

The information system enforces approved authorizations for logical access to information and system resources in accordance with applicable access control policies.

## Additional IBM Cloud for Financial Services specifications
{: #additional-fs-cloud-specifications}

Customer consent must be obtained prior to releasing any data outside its intended use.  Note: See AC-21 for guidance/implementation details.

Authorized individuals include Federal Regulators in the event of insolvency.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Access management in {{site.data.keyword.cloud_notm}}](/docs/framework-financial-services?topic=framework-financial-services-shared-account-access-management)

## IBM Cloud for Financial Services profile
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

## NIST supplemental guidance
{: #supplemental-guidance}

Access control policies (e.g., identity-based policies, role-based policies, control matrices, cryptography) control access between active entities or subjects (i.e., users or processes acting on behalf of users) and passive entities or objects (e.g., devices, files, records, domains) in information systems. In addition to enforcing authorized access at the information system level and recognizing that information systems can host many applications and services in support of organizational missions and business operations, access enforcement mechanisms can also be employed at the application and service level to provide increased information security.

