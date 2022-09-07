---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-07"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# AC-6 - Least Privilege
{: #ac-6}

## Requirements
{: #requirements}

The organization employs the principle of least privilege, allowing only authorized accesses for users (or processes acting on behalf of users) which are necessary to accomplish assigned tasks in accordance with organizational missions and business functions.

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

Individual users are not permitted to interact with system-to-system service accounts.

## Control Supplemental Guidance
{: #supplemental-guidance}

Organizations employ least privilege for specific duties and information systems. The principle of least privilege is also applied to information system processes, ensuring that the processes operate at privilege levels no higher than necessary to accomplish required organizational missions/business functions. Organizations consider the creation of additional processes, roles, and information system accounts as necessary, to achieve least privilege. Organizations also apply least privilege to the development, implementation, and operation of organizational information systems.



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
- [3000708: Check whether App ID Cloud Directory users aren't able to update their own accounts](https://cloud.ibm.com/security-compliance/goals/3000708?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
