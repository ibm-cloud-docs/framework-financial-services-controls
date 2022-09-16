---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-16"
keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# AC-2 - Account Management
{: #ac-2}

## Requirements
{: #requirements}

The organization:

- \[a.\] Identifies and selects the following types of information system accounts to support organizational missions/business functions: [organization-defined information system account types];

- \[b.\] Assigns account managers for information system accounts;

- \[c.\] Establishes conditions for group and role membership;

- \[d.\] Specifies authorized users of the information system, group and role membership, and access authorizations (i.e., privileges) and other attributes (as required) for each account;

- \[e.\] Requires approvals by [organization-defined personnel or roles] for requests to create information system accounts;

- \[f.\] Creates, enables, modifies, disables, and removes information system accounts in accordance with [organization-defined procedures or conditions];

- \[g.\] Monitors the use of information system accounts;

- \[h.\] Notifies account managers:

  - \[1.\] When accounts are no longer required;
  - \[2.\] When users are terminated or transferred; and
  - \[3.\] When individual information system usage or need-to-know changes;

- \[i.\] Authorizes access to the information system based on:

  - \[1.\] A valid access authorization;
  - \[2.\] Intended system usage; and
  - \[3.\] Other attributes as required by the organization or associated missions/business functions;

- \[j.\] Reviews accounts for compliance with account management requirements [quarterly for privileged access; quarterly for any access to regulated systems, as specified by FS-ready public cloud customer vendor managers; annually for all other access]; and

- \[k.\] Establishes a process for reissuing shared/group account credentials (if deployed) when individuals are removed from the group.

## Additional IBM Cloud for Financial Services specifications
{: #additional-fs-cloud-specifications}

Prior to production access, users must be onboarded and registered in the customer&#39;s access management system.  

The organization must be able to export all current customer end users and permissions within the organization’s application/system.

Access activity/logs should be reported to the customer daily, as required.

Access activity/logs should contain the following content: user ID, associated roles and permissions, business/job function, last logon date.

Account managers must include the individual&#39;s or system&#39;s manager and account owner.

## NIST supplemental guidance
{: #supplemental-guidance}

Information system account types include, for example, individual, shared, group, system, guest/anonymous, emergency, developer/manufacturer/vendor, temporary, and service. Some of the account management requirements listed above can be implemented by organizational information systems. The identification of authorized users of the information system and the specification of access privileges reflects the requirements in other security controls in the security plan. Users requiring administrative privileges on information system accounts receive additional scrutiny by appropriate organizational personnel (e.g., system owner, mission/business owner, or chief information security officer) responsible for approving such accounts and privileged access. Organizations may choose to define access privileges or other attributes by account, by type of account, or a combination of both. Other attributes required for authorizing access include, for example, restrictions on time-of-day, day-of-week, and point-of-origin. In defining other account attributes, organizations consider system-related requirements (e.g., scheduled maintenance, system upgrades) and mission/business requirements, (e.g., time zone differences, customer requirements, remote access to support travel requirements). Failure to consider these factors could affect information system availability. Temporary and emergency accounts are accounts intended for short-term use. Organizations establish temporary accounts as a part of normal account activation procedures when there is a need for short-term accounts without the demand for immediacy in account activation. Organizations establish emergency accounts in response to crisis situations and with the need for rapid account activation. Therefore, emergency account activation may bypass normal account authorization processes. Emergency and temporary accounts are not to be confused with infrequently used accounts (e.g., local logon accounts used for special tasks defined by organizations or when network resources are unavailable). Such accounts remain available and are not subject to automatic disabling or removal dates. Conditions for disabling or deactivating accounts include, for example: (i) when shared/group, emergency, or temporary accounts are no longer required; or (ii) when individuals are transferred or terminated. Some types of information system accounts may require specialized training.

<staging>

## Part a.
{: #part-a}

#


## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Audit logging of {{site.data.keyword.cloud_notm}} events](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit)
- [Audit logging of application provider events and SIEM](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit-provider)
- [Handling and securing secrets](/docs/framework-financial-services?topic=framework-financial-services-shared-secrets)
- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)
- [Consumer accounts for application provider workloads](/docs/framework-financial-services?topic=framework-financial-services-shared-account-consumer)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

### Part a.
{: #part-a-scc-fs-cloud-profile}

- 3000059: IBM Cloud accounts are one of the account types used to support your applications

### Part d.
{: #part-d-scc-fs-cloud-profile}

- 3000009: Check whether IAM roles are used to create IAM policies for IBM resources
- 3000015: Check whether IAM users are attached to at least one access group
- 3000016: Check whether IAM policies for users are attached only to groups or roles
- 3000023: Check whether the account owner does not have an IBM Cloud API key created in IAM
- 3000027: Check whether permissions for API key creation are limited and configured in IAM settings for the account owner

### Part g.
{: #part-g-scc-fs-cloud-profile}

- 3000118: Check that there is an Activity Tracker event route defined to collect global events generated by IBM Cloud services
