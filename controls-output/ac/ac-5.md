---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-07"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# AC-5 - Separation Of Duties
{: #ac-5}

## Requirements
{: #requirements}

The organization:

- \[a.\] Separates [organization-defined duties of individuals];

- \[b.\] Documents separation of duties of individuals; and

- \[c.\] Defines information system access authorizations to support separation of duties.

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

Ensure segregation exists such that no one individual has the authority/ability to develop, compile and/or move object code from non-production environments into production environments.

## Control Supplemental Guidance
{: #supplemental-guidance}

Separation of duties addresses the potential for abuse of authorized privileges and helps to reduce the risk of malevolent activity without collusion. Separation of duties includes, for example: (i) dividing mission functions and information system support functions among different individuals and/or roles; (ii) conducting information system support functions with different individuals (e.g., system management, programming, configuration management, quality assurance and testing, and network security); and (iii) ensuring security personnel administering access control functions do not also administer audit functions.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| ac-5_prm_1 |  | organization-defined duties of individuals |


## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

### Part c
{: #scc-fs-cloud-profile-c}

- [3000009: Check whether IAM roles are used to create IAM policies for IBM resources](https://cloud.ibm.com/security-compliance/goals/3000009?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000015: Check whether IAM users are attached to at least one access group](https://cloud.ibm.com/security-compliance/goals/3000015?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000016: Check whether IAM policies for users are attached only to groups or roles](https://cloud.ibm.com/security-compliance/goals/3000016?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000023: Check whether the account owner does not have an IBM Cloud API key created in IAM](https://cloud.ibm.com/security-compliance/goals/3000023?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000027: Check whether permissions for API key creation are limited and configured in IAM settings for the account owner](https://cloud.ibm.com/security-compliance/goals/3000027?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000035: Check whether account service access is managed only by IAM access groups](https://cloud.ibm.com/security-compliance/goals/3000035?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000106: Check whether Cloud Object Storage bucket access is restricted by using IAM and S3 access control](https://cloud.ibm.com/security-compliance/goals/3000106?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000707: Check whether App ID user profile updates from client apps is disabled](https://cloud.ibm.com/security-compliance/goals/3000707?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000708: Check whether App ID Cloud Directory users aren't able to update their own accounts](https://cloud.ibm.com/security-compliance/goals/3000708?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000709: Check whether App ID Cloud Directory users aren't able to self-sign up to applications](https://cloud.ibm.com/security-compliance/goals/3000709?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
