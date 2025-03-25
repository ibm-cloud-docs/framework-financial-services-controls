---
copyright:
  years: 2020, 2025

lastupdated: "2025-03-02"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# AC-2 - Account Management
{: #ac-2}

## Control requirements
{: #control-requirements}



### AC-2 (a)


Define and document the types of accounts allowed and specifically prohibited for use within the system.


### AC-2 (b)


Assign account managers.


### AC-2 (c)


Require _[Assignment: organization-defined prerequisites and criteria]_ for group and role membership.


### AC-2 (d)


Specify:
1. Authorized users of the system;
2. Group and role membership; and
3. Access authorizations (i.e., privileges) and _[Assignment: organization-defined attributes (as required)]_ for each account.


### AC-2 (e)


Require approvals by _[Assignment: organization-defined personnel or roles]_ for requests to create accounts.


### AC-2 (f)


Create, enable, modify, disable, and remove accounts in accordance with _[Assignment: organization-defined policy, procedures, prerequisites, and criteria]_.


### AC-2 (g)


Monitor the use of accounts.


### AC-2 (h)


Notify account managers and _[Assignment: organization-defined personnel or roles]_ within:
1. _[IBM Assignment: twenty-four (24) hours]_ when accounts are no longer required;
2. _[IBM Assignment: eight (8) hours]_ when users are terminated or transferred; and
3. _[IBM Assignment: eight (8) hours]_ when system usage or need-to-know changes for an individual.


### AC-2 (i)


Authorize access to the system based on:
1. A valid access authorization;
2. Intended system usage; and
3. _[Assignment: organization-defined attributes (as required)]_.


### AC-2 (j)


Review accounts for compliance with account management requirements _[IBM Assignment: quarterly for privileged access; quarterly for any access to regulated systems, as specified by FS-ready public cloud customer vendor managers; annually for all other access]_.


### AC-2 (k)


Establish and implement a process for changing shared or group account authenticators (if deployed) when individuals are removed from the group.


### AC-2 (l)


Align account management processes with personnel termination and transfer processes.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

Prior to production access, users must be onboarded and registered in the customer's access management system.  

The organization must be able to export all current customer end users and permissions within the organization’s application/system.

Access activity/logs should be reported to the customer daily, as required.

Access activity/logs should contain the following content: user ID, associated roles and permissions, business/job function, last logon date.

Account managers must include the individual's or system's manager and account owner.




## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.


- [Audit logging of {{site.data.keyword.cloud_notm}} events](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit)


- [Audit logging of application provider events and SIEM](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit-provider)


- [Handling and securing secrets](/docs/framework-financial-services?topic=framework-financial-services-shared-secrets)


- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)


- [Consumer accounts for application provider workloads](/docs/framework-financial-services?topic=framework-financial-services-shared-account-consumer)






## NIST supplemental guidance
{: #nist-supplemental-guidance}

Examples of system account types include individual, shared, group, system, guest, anonymous, emergency, developer, temporary, and service. Identification of authorized system users and the specification of access privileges reflect the requirements in other controls in the security plan. Users requiring administrative privileges on system accounts receive additional scrutiny by organizational personnel responsible for approving such accounts and privileged access, including system owner, mission or business owner, senior agency information security officer, or senior agency official for privacy. Types of accounts that organizations may wish to prohibit due to increased risk include shared, group, emergency, anonymous, temporary, and guest accounts.
Where access involves personally identifiable information, security programs collaborate with the senior agency official for privacy to establish the specific conditions for group and role membership; specify authorized users, group and role membership, and access authorizations for each account; and create, adjust, or remove system accounts in accordance with organizational policies. Policies can include such information as account expiration dates or other factors that trigger the disabling of accounts. Organizations may choose to define access privileges or other attributes by account, type of account, or a combination of the two. Examples of other attributes required for authorizing access include restrictions on time of day, day of week, and point of origin. In defining other system account attributes, organizations consider system-related requirements and mission/business requirements. Failure to consider these factors could affect system availability.
Temporary and emergency accounts are intended for short-term use. Organizations establish temporary accounts as part of normal account activation procedures when there is a need for short-term accounts without the demand for immediacy in account activation. Organizations establish emergency accounts in response to crisis situations and with the need for rapid account activation. Therefore, emergency account activation may bypass normal account authorization processes. Emergency and temporary accounts are not to be confused with infrequently used accounts, including local logon accounts used for special tasks or when network resources are unavailable (may also be known as accounts of last resort). Such accounts remain available and are not subject to automatic disabling or removal dates. Conditions for disabling or deactivating accounts include when shared/group, emergency, or temporary accounts are no longer required and when individuals are transferred or terminated. Changing shared/group authenticators when members leave the group is intended to ensure that former group members do not retain access to the shared or group account. Some types of system accounts may require specialized training.
