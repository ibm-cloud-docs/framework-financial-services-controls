---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-08"
keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# AC-3 - Access Enforcement
{: #ac-3}

## Requirements
{: #requirements}

The information system enforces approved authorizations for logical access to information and system resources in accordance with applicable access control policies.

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

Customer consent must be obtained prior to releasing any data outside its intended use.  Note: See AC-21 for guidance/implementation details.

Authorized individuals include Federal Regulators in the event of insolvency.

## Control Supplemental Guidance
{: #supplemental-guidance}

Access control policies (e.g., identity-based policies, role-based policies, control matrices, cryptography) control access between active entities or subjects (i.e., users or processes acting on behalf of users) and passive entities or objects (e.g., devices, files, records, domains) in information systems. In addition to enforcing authorized access at the information system level and recognizing that information systems can host many applications and services in support of organizational missions and business operations, access enforcement mechanisms can also be employed at the application and service level to provide increased information security.


## Related Resources
{: #related_resources}

See the resources that follow to learn more about how to implement this control.

- [Access management in {{site.data.keyword.cloud_notm}}](/docs/framework-financial-services?topic=framework-financial-services-shared-account-access-management)

## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- [3000009: Check whether IAM roles are used to create IAM policies for IBM resources](https://cloud.ibm.com/security-compliance/goals/3000009?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000015: Check whether IAM users are attached to at least one access group](https://cloud.ibm.com/security-compliance/goals/3000015?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000016: Check whether IAM policies for users are attached only to groups or roles](https://cloud.ibm.com/security-compliance/goals/3000016?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000022: Check whether Cloud Object Storage public access is disabled in IAM settings (not applicable to ACLs managed using S3 APIs)](https://cloud.ibm.com/security-compliance/goals/3000022?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000023: Check whether the account owner does not have an IBM Cloud API key created in IAM](https://cloud.ibm.com/security-compliance/goals/3000023?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000026: Check whether user list visibility restrictions are configured in IAM settings for the account owner](https://cloud.ibm.com/security-compliance/goals/3000026?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000027: Check whether permissions for API key creation are limited and configured in IAM settings for the account owner](https://cloud.ibm.com/security-compliance/goals/3000027?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000028: Check whether permissions for service ID creation are limited and configured in IAM settings for the account owner](https://cloud.ibm.com/security-compliance/goals/3000028?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000035: Check whether account service access is managed only by IAM access groups](https://cloud.ibm.com/security-compliance/goals/3000035?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000106: Check whether Cloud Object Storage bucket access is restricted by using IAM and S3 access control](https://cloud.ibm.com/security-compliance/goals/3000106?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
