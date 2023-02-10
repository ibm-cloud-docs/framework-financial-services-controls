---

copyright:
  years: 2020, 2023

lastupdated: "2023-02-08"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# IA-7 - Cryptographic Module Authentication
{: #ia-7}

## Control requirements
{: #control-requirements}

IA-7 - 0
    : The information system implements mechanisms for authentication to a cryptographic module that meet the requirements of applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance for such authentication.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.1.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- Check whether multifactor authentication (MFA) is enabled at the account level 
- Check whether IAM roles are used to create IAM policies for IBM resources 
- Check whether IAM users are attached to at least one access group 
- Check whether Hyper Protect Crypto Services is accessible only through private endpoints 
- Check whether Hyper Protect Crypto Services instance is enabled with a dual authorization deletion policy

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Authentication mechanisms may be required within a cryptographic module to authenticate an operator accessing the module and to verify that the operator is authorized to assume the requested role and perform services within that role.





