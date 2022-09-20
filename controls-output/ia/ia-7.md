---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-20"

keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# IA-7 - Cryptographic Module Authentication
{: #ia-7}

## Requirements
{: #requirements}

The information system implements mechanisms for authentication to a cryptographic module that meet the requirements of applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance for such authentication.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- 3000009: Check whether IAM roles are used to create IAM policies for IBM resources
- 3000015: Check whether IAM users are attached to at least one access group
- 3000016: Check whether IAM policies for users are attached only to groups or roles
- 3000017: Check whether multifactor authentication (MFA) is enabled at the account level
- 3000234: Check whether Hyper Protect Crypto Services instance is enabled with a dual authorization deletion policy
- 3000510: Check whether Hyper Protect Crypto Services is accessible only through private endpoints

## NIST supplemental guidance
{: #supplemental-guidance}

Authentication mechanisms may be required within a cryptographic module to authenticate an operator accessing the module and to verify that the operator is authorized to assume the requested role and perform services within that role.

