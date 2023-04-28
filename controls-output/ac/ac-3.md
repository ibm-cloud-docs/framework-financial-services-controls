---

copyright:
  years: 2020, 2023

lastupdated: "2023-04-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# AC-3 - Access Enforcement
{: #ac-3}

## Control requirements
{: #control-requirements}

AC-3 - 0
    : The information system enforces approved authorizations for logical access to information and system resources in accordance with applicable access control policies.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- Customer consent must be obtained prior to releasing any data outside its intended use.
- Authorized individuals include Federal Regulators in the event of insolvency.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Access management in {{site.data.keyword.cloud_notm}}](/docs/framework-financial-services?topic=framework-financial-services-shared-account-access-management)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- Check whether permissions for service ID creation are limited and configured in IAM settings for the account owner 
- Check whether permissions for API key creation are limited and configured in IAM settings for the account owner 
- Check whether permissions for API key creation are limited and configured in IAM settings for the account owner 
- Check whether user list visibility restrictions are configured in IAM settings for the account owner 
- Check whether IAM roles are used to create IAM policies for IBM resources 
- Check whether IAM users are attached to at least one access group 
- Check whether Cloud Object Storage public access is disabled in IAM settings (not applicable to ACLs managed using S3 APIs)

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Access control policies (e.g., identity-based policies, role-based policies, control matrices, cryptography) control access between active entities or subjects (i.e., users or processes acting on behalf of users) and passive entities or objects (e.g., devices, files, records, domains) in information systems. In addition to enforcing authorized access at the information system level and recognizing that information systems can host many applications and services in support of organizational missions and business operations, access enforcement mechanisms can also be employed at the application and service level to provide increased information security.





