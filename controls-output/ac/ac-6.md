---

copyright:
  years: 2020, 2023

lastupdated: "2023-02-08"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# AC-6 - Least Privilege
{: #ac-6}

## Control requirements
{: #control-requirements}

AC-6 - 0
    : The organization employs the principle of least privilege, allowing only authorized accesses for users (or processes acting on behalf of users) which are necessary to accomplish assigned tasks in accordance with organizational missions and business functions.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- Individual users are not permitted to interact with system-to-system service accounts.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Access management in {{site.data.keyword.cloud_notm}}](/docs/framework-financial-services?topic=framework-financial-services-shared-account-access-management)
- [Consumer accounts for application provider workloads](/docs/framework-financial-services?topic=framework-financial-services-shared-account-consumer)
- [Organizing {{site.data.keyword.cloud_notm}} accounts and resources](/docs/framework-financial-services?topic=framework-financial-services-shared-account-organization)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.1.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- Check whether permissions for service ID creation are limited and configured in IAM settings for the account owner 
- Check whether permissions for API key creation are limited and configured in IAM settings for the account owner 
- Check whether permissions for API key creation are limited and configured in IAM settings for the account owner 
- Check whether App ID Cloud Directory users aren't able to update their own accounts 
- Check whether user list visibility restrictions are configured in IAM settings for the account owner 
- Check whether IAM roles are used to create IAM policies for IBM resources 
- Check whether IAM users are attached to at least one access group 
- Check whether Cloud Object Storage public access is disabled in IAM settings (not applicable to ACLs managed using S3 APIs)

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Organizations employ least privilege for specific duties and information systems. The principle of least privilege is also applied to information system processes, ensuring that the processes operate at privilege levels no higher than necessary to accomplish required organizational missions/business functions. Organizations consider the creation of additional processes, roles, and information system accounts as necessary, to achieve least privilege. Organizations also apply least privilege to the development, implementation, and operation of organizational information systems.





