---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-14"
keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# TEST AC-2 - Account Management
{: #test-ac-2}

## Requirements
{: #requirements}

This control has the following requirements:

Part A
    : Identifies and selects the following types of information system accounts to support organizational missions/business functions: [organization-defined information system account types].

Part B
    : Assigns account managers for information system accounts.

Part C
    : Establishes conditions for group and role membership.

Part D 
    : Specifies authorized users of the information system, group and role membership, and access authorizations (that is, privileges) and other attributes (as required) for each account.

Part E 
    : Requires approvals by [organization-defined personnel or roles] for requests to create information system accounts.

Part F
    : Creates, enables, modifies, disables, and removes information system accounts in accordance with [organization-defined procedures or conditions];

Part G
    : Monitors the use of information system accounts;

Part H
    : Notifies account managers:
    1. When accounts are no longer required.
    2. When users are terminated or transferred.
    3. When individual information system usage or need-to-know changes.

Part I
    : Authorizes access to the information system based on:
    1. A valid access authorization.
    2. Intended system usage.
    3. Other attributes as required by the organization or associated missions/business functions.

Part J
    : Reviews accounts for compliance with account management requirements [quarterly for privileged access; quarterly for any access to regulated systems, as specified by FS-ready public cloud customer vendor managers; annually for all other access]; and

Part K
    : Establishes a process for reissuing shared/group account credentials (if deployed) when individuals are removed from the group.

## Additional specifications for Financial Services Cloud
{: #additional-fs-cloud-specifications}

The following specifications are required to be Financial Services Cloud compliant: 

- Prior to production access, users must be onboarded and registered in the customer's access management system.  
- The organization must be able to export all current customer end users and permissions within the organization's application/system.
- Access activity/logs should be reported to the customer daily, as required.
- Access activity/logs should contain the following content: user ID, associated roles and permissions, business/job function, last logon date.
- Account managers must include the individual's or system's manager and account owner.

## Supplemental guidance
{: #supplemental-guidance}

Information system account types include, for example, individual, shared, group, system, guest/anonymous, emergency, developer/manufacturer/vendor, temporary, and service. Some of the account management requirements listed above can be implemented by organizational information systems. The identification of authorized users of the information system and the specification of access privileges reflects the requirements in other security controls in the security plan. 

Users requiring administrative privileges on information system accounts receive additional scrutiny by appropriate organizational personnel (e.g., system owner, mission/business owner, or chief information security officer) responsible for approving such accounts and privileged access. Organizations may choose to define access privileges or other attributes by account, by type of account, or a combination of both. Other attributes required for authorizing access include, for example, restrictions on time-of-day, day-of-week, and point-of-origin. In defining other account attributes, organizations consider system-related requirements (for example, scheduled maintenance, system upgrades) and mission/business requirements, (for example, time zone differences, customer requirements, remote access to support travel requirements). Failure to consider these factors could affect information system availability. 

Temporary and emergency accounts are accounts intended for short-term use. Organizations establish temporary accounts as a part of normal account activation procedures when there is a need for short-term accounts without the demand for immediacy in account activation. Organizations establish emergency accounts in response to crisis situations and with the need for rapid account activation. Therefore, emergency account activation may bypass normal account authorization processes. Emergency and temporary accounts are not to be confused with infrequently used accounts (for example, local logon accounts used for special tasks defined by organizations or when network resources are unavailable). Such accounts remain available and are not subject to automatic disabling or removal dates. Conditions for disabling or deactivating accounts include, for example: (i) when shared/group, emergency, or temporary accounts are no longer required; or (ii) when individuals are transferred or terminated. Some types of information system accounts may require specialized training.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| ac-2_prm_1 |  | organization-defined information system account types |
| ac-2_prm_2 |  | organization-defined personnel or roles |
| ac-2_prm_3 |  | organization-defined procedures or conditions |
| ac-2_prm_4 | quarterly for privileged access; quarterly for any access to regulated systems, as specified by FS-ready public cloud customer vendor managers; annually for all other access | organization-defined frequency |

## Part A

### Implementation guidance

Identify types of accounts to support organizational missions/business functions.  When specifying account types, the provider considers the following account types that apply for their IBM Cloud accounts, host operating systems, and applications: individual, shared, group, system, guest/anonymous, emergency, developer/manufacturer/vendor, temporary, service accounts, privileged administrator accounts, domain administrator accounts, local device accounts, and customer privileged administrative accounts.

An IBM Cloud account is required to create and manage IBM Cloud resources. Within an account, the account owner or their delegate can create an access group to organize a set of users and service IDs into a single entity and easily assign permissions. Accesses can be grouped into policies and applied to groups of users instead of assigning the same access multiple times per individual user or service ID.

Those individuals who are responsible for the development and operation of the production environment where provider is hosting the application should be assigned to an access group that is separate from the users who can order and configure services from the IBM Cloud console, command line interface (CLI), or application programming interface (PI) (e.g., the admin that is responsible for the configuration of encryption should not have the ability to write data within the environment because they could turn off encryption, write data, or turn on encryption (and thereby bypass encrypting data at rest and/or  the administrator that is responsible for setting audit levels should not be able to perform actions within the application such as  turning on/off audit or dump data.   provider should have RBAC configured for all its staff enforcing separation of duties (SOD).
For additional information on IBM Cloud accounts, please refer to Overview of accounts, identity management, and access control.

The following provides additional context for the domains mentioned above:

Provider operators:

IBM Cloud account users
    : Includes administrators whose function is to order resources to be used in the providers deployment such as
virtual private clouds (VPC), virtual servers, etc. and operators who need to access cloud resources for operations. IBM Cloud IAM can federate to the providers identity provider (IdP).

Operating System (OS) operator/application account users
    : This is the domain that defines provider users with fewer privileges than administrators described above. These users may be operators who only need access to the OS level of the virtual machines (VM)/containers, application developers, testers, and other less-privileged roles relative to the operation of the IBM Cloud deployment itself.

Consumer users
    : This domain is where the consumer end users are defined. provider may assist the consumer with integration of the consumer's IdP.  Doing this enables application users to consume the consumer service using single sign-on.
    : Provider is also responsible for identifying account types for their internal operators within the application, as well as providing the capability for the consumer to implement RBAC within the application.
    : The consumer is responsible for managing their own external end user accounts for the consumer application.

Service Accounts and credentials (e.g., Service IDs, system to system application credentials, certificates, tokens, etc.)
    :  provider shall maintain service accounts and ensure rotation of such accounts minimally on an annual basis.  Such credentials are usually maintained in a vault.
    
    Guidance on Service IDs is available.
    {: note}

Application Programming Interfaces (API)
    : provider is to create identifiers/API Keys to be used by provider APIs, when applicable, that interact with components within the consumer application and audit their use.  Provider APIs may also be called by consumers, and their use should be logged.

### Evidence guidance

List of all account types identified and established for the provider environment (IBM Cloud account, provider admin accounts for both the environment and the application), including roles, authorized privileges, and functions performed for each account type.

System demos/walkthroughs of all account management systems (IBM Cloud, provider corporate IdP, etc.).

List of all service accounts including the following:
- account name
- account function
- users with access to service account

## Part B

### Implementation guidance

The provider assigns account managers for IBM Cloud, and provider IdP accounts used by DevOps and other operations staff.  Account managers include the individual&#39;s or system&#39;s manager and account owner.

### Evidence guidance

Identified account managers for all accounts supporting the provider application (IBM Cloud, application)

## Part C

### Implementation guidance

The provider establishes conditions for group and role membership to enable fine grained role-based access controls for all IBM Cloud and application accounts used to support their application.

For IBM Cloud accounts, access management is handled by IBM Cloud IAM. Every user with access to the IBM Cloud account is assigned an access policy (via access group) with IAM user roles defined.  For additional information on managing IBM Cloud IAM access groups and roles, refer to Access management in IBM Cloud.

### Evidence guidance

Established requirements and conditions for group and role membership for all accounts (e.g., IBM Cloud, application environment) used to support the provider application.
Specifically, for IBM Cloud accounts, system generated lists of IAM user roles and allowable actions applied to the IBM Cloud account/instance, IAM access policies, access groups, and resource groups.
For provider application accounts, system generated lists of roles/permissions and groups/users defined (includes service accounts).

## Part D

### Implementation guidance

The provider specifies authorized users, group and role membership, access privileges, and other attributes (as required) for each IBM Cloud account and application environment account used to support the provider application.  Users are authorized access based on their job function/role, intended system usage, and responsibilities for mission/business functions.

### Evidence guidance

System generated list of all accounts with access to the provider environment, including IBM Cloud  and application accounts, including the following details:

-	account name
-	username
-	account status (active, disabled, etc.)
- user group and role
- access privileges
- account owner

## Part E

### Implementation guidance

Designated personnel or roles formally approve requests to create any account used to support the provider application.  Upon required approvals, accounts are created on valid access authorizations.

### Evidence guidance

Account creation tickets or other evidence for users with access to the provider environment including the following details:

- approval (date approved and who approved)
- role and permissions the user was granted

## Part F

### Implementation guidance

All accounts are created, enabled, modified, disabled, and removed in accordance with personnel security requirements that include onboarding, termination, transfer, and sanctions.

Prior to production access, the consumers users are onboarded and registered in the consumer&#39;s access management system, as required by the consumer.

The provider is to be able to export all provider operators/operators and permissions for production environments and enable consumer to export current users and permissions within the provider application/system, as required by the customer.

### Evidence guidance

System generated list of all IBM Cloud and application accounts with access to the provider environment, including the following details:

- account name
- username
- account status (active, disabled, etc.)
- account creation date
- account disabled date
- account owner

System generated list of employees/contractors hired in the past 12 months, including the following details:

- account name
- username
- hire date
- role

Account creation tickets or other evidence for users with access to the provider environment, including the following details:

- approval (date approved and who approved)
- role and permissions the user was granted

System generated list of employees/contractors terminated/transferred in the past 12 months, including the following details:

- account name
- username
- termination date
- role

Account termination tickets or other evidence for terminated users, including the following details:

- when account access to the provider environment was removed (within 24 hours of termination date)
- who was notified of account removal

Account modification tickets or other evidence for modified/transferred users, including the following details:

- approval (date approved and who approved)
- review and modification of access where account permissions were modified, when individual information system usage or need-to-know changes
- who was notified of account modification/transfer

## Part G

### Implementation guidance

Account usage is logged and monitored in accordance with AU-12, capturing the events defined in AU-2(d).  Event logs are used to explicitly capture privileged user actions and the execution of privileged functions, such as, access granted to existing objects; creating a user account; deleting a user account; changing a user account; security enabled group change; etc.

The provider configures IBM Cloud platform events to be stored on Cloud Object Storage (COS) service to track how their operators interact with IBM Cloud.  See Audit logging of IBM Cloud events for more information.

For application user activity, associated account usage is to be logged and monitored as well.  Application access activity/logs is reported to the consumer daily, if required by the consumer.  Access activity/logs should contain the following content at a minimum: user ID, associated roles and permissions, business/job function, last logon date.
Once deployed, audit logging tool(s) are connected and configured to send logs to a security information and event monitoring (SIEM) tool, to monitor account usage in real time.

### Evidence guidance

Configuration settings of audit logging tool(s) and/or other monitoring tool(s) including the security information and event monitoring (SIEM) tool, showing the events that are monitored for system components.  Periodic review of events to be monitored to ensure they remain current with new and evolving threats.
Security alerts notifications from the audit logging tool(s) and/or other monitoring tools (SIEM), including how Provider-defined personnel are alerted of account usage events of interest such as account creation or deletion actions.

## Part H

### Implementation guidance

In the event of personnel termination, transfer, or access change, the providers management notifies the account manager.  After notification, an assigned administrator is responsible for disabling/deleting or modifying system access within 24 hours of notification.

### Evidence guidance

Account termination tickets or other evidence for terminated users, including the following details:

- when account access to the provider environment was removed
- who was notified of account removal?

Account modification tickets or other evidence for modified/transferred users, including the following details:

- approval (date approved and who approved)
- review and modification of access where account permissions were modified.
- who was notified of account modification/transfer?

## Part I

### Implementation guidance

Access to the information system is granted based upon least privilege and separation of duties principles.  Access that has not been explicitly permitted is denied by default.  Users are authorized access based on their job function/role, intended system usage, and responsibilities for mission/business functions.

### Evidence guidance

System generated list of all accounts with access to the provider environment, including IBM Cloud, and application accounts, with the following details:

- account name
- username
- account status (active, disabled, etc.)
- user group and role*
- access privileges
- account owner+

Implemented group and role membership must align with documented least privilege and segregation of duties policies, matrices, etc.
{: note}

Account creation tickets or other evidence for users with access to the provider environment, including the following details:
- approval (date approved and who approved)
- role and permissions the user was granted.

## Part J

### Implementation guidance

The provider reviews user accounts, privileges, and access authorizations for compliance with account management requirements at least quarterly for privileged access, quarterly for any access to regulated systems, as specified by the consumers vendor managers, and annually for all other access.  All access review actions are documented and maintained.

### Evidence guidance

Evidence of quarterly privileged account reviews and other annual account reviews showing that accounts and privileges that were incorrect or unnecessary were removed.

## Part K

### Implementation guidance

The provider manages shared/group accounts by only permitting them for certain defined conditions and establishing a process for terminating and reissuing shared/group account credentials when individuals are removed from the group.

### Evidence guidance

List of all shared/group accounts including the following:

- account name
- account function
- users with access to shared/group account
- last credential change date
- Evidence of process for reissuing of shared account credentials


## Related resources
{: #related_resources}

See the resources that follow to learn more about how to implement this control.

- [Audit logging of {{site.data.keyword.cloud_notm}} events](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit)
- [Audit logging of application provider events and SIEM](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit-provider)
- [Handling and securing secrets](/docs/framework-financial-services?topic=framework-financial-services-shared-secrets)
- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)
- [Consumer accounts for application provider workloads](/docs/framework-financial-services?topic=framework-financial-services-shared-account-consumer)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

### Part A
{: #scc-fs-cloud-profile-a}

- [3000059: IBM Cloud accounts are one of the account types used to support your applications](https://cloud.ibm.com/security-compliance/goals/3000059?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}

### Part D
{: #scc-fs-cloud-profile-d}

- [3000009: Check whether IAM roles are used to create IAM policies for IBM resources](https://cloud.ibm.com/security-compliance/goals/3000009?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000015: Check whether IAM users are attached to at least one access group](https://cloud.ibm.com/security-compliance/goals/3000015?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000016: Check whether IAM policies for users are attached only to groups or roles](https://cloud.ibm.com/security-compliance/goals/3000016?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000023: Check whether the account owner does not have an IBM Cloud API key created in IAM](https://cloud.ibm.com/security-compliance/goals/3000023?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000027: Check whether permissions for API key creation are limited and configured in IAM settings for the account owner](https://cloud.ibm.com/security-compliance/goals/3000027?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}

### Part G
{: #scc-fs-cloud-profile-g}

- [3000118: Check that there is an Activity Tracker event route defined to collect global events generated by IBM Cloud services](https://cloud.ibm.com/security-compliance/goals/3000118?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
