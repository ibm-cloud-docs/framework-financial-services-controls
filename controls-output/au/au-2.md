---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-29"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# AU-2 - Audit Events
{: #au-2}

## Control requirements
{: #control-requirements}

The organization:

AU-2 (a)
    : Determines that the information system is capable of auditing the following events: _[for required audit events, refer to Additional FS-ready public cloud Guidance]_;

AU-2 (b)
    : Coordinates the security audit function with other organizational entities requiring audit-related information to enhance mutual support and to help guide the selection of auditable events;

AU-2 (c)
    : Provides a rationale for why the auditable events are deemed to be adequate to support after-the-fact investigations of security incidents; and

AU-2 (d)
    : Determines that the following events are to be audited within the information system: _[auditable events defined in AU-2 a. to be audited continually for each identified event]_.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

The following events are to be audited within the system:
- Access, downloading, revisions to Confidential information
- Access to or update to any financial transaction data
- Any changes to customer accounts
- Login/logoff event, success/failure
- Changes to a system that impact business logic or work flow, examples include but are not limited to, changing call routing, interest rates offered for a class of customer, a web site flow a customer uses
- Any changes to customer systems including but not limited to: software install/removal, configuration changes, directory/file moves/adds/deletes, configuration changes, port turn ups, MAC’s, routing changes, etc.
- Each command action taken, both successful and unsuccessful, by a privileged account including but not limited to:
    - All changes, additions, or deletions to any account such as lock, unlock, password reset, permission changes,
    - Modification to system time / time-synchronization configuration,
    - Log files: access to logs files; initialization, stopping or pausing of logging, log modification, changes to access permission on log files,
    - Files and system level objects creation and deletion,
    - Attempts to perform unauthorized functions or access data the user is not authorized to access,
    - Modification of security rules,
    - Application and related systems start-ups and shut-downs
- For privileged accounts:
    - Attempts to execute privilege elevation
    - System errors relevant to security events, including but not limited to SQL errors that indicate a SQL injection, fuzzing, multiple failed logins, failed configuration change, failed/disabled anti-virus software, service failures
    - Web access events in extended log format

The above security audit logging events are required for all environments, e.g., production, development, user acceptance testing.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.6.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Goals |
|----------------|-------|
| AU-2 (a) | - 3000118: Check that there is an Activity Tracker event route defined to collect global events generated by IBM Cloud services \n - 3000710: Check whether App ID runtime activity capture is enabled | 
| AU-2 (d) | - 3000118: Check that there is an Activity Tracker event route defined to collect global events generated by IBM Cloud services \n - 3000710: Check whether App ID runtime activity capture is enabled | 
{: caption="Goals for AU-2 in IBM Cloud for Financial Services v0.6.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

An event is any observable occurrence in an organizational information system. Organizations identify audit events as those events which are significant and relevant to the security of information systems and the environments in which those systems operate in order to meet specific and ongoing audit needs. Audit events can include, for example, password changes, failed logons, or failed accesses related to information systems, administrative privilege usage, PIV credential usage, or third-party credential usage. In determining the set of auditable events, organizations consider the auditing appropriate for each of the security controls to be implemented. To balance auditing requirements with other information system needs, this control also requires identifying that subset of auditable events that are audited at a given point in time. For example, organizations may determine that information systems must have the capability to log every file access both successful and unsuccessful, but not activate that capability except for specific circumstances due to the potential burden on system performance. Auditing requirements, including the need for auditable events, may be referenced in other security controls and control enhancements. Organizations also include auditable events that are required by applicable federal laws, Executive Orders, directives, policies, regulations, and standards. Audit records can be generated at various levels of abstraction, including at the packet level as information traverses the network. Selecting the appropriate level of abstraction is a critical aspect of an audit capability and can facilitate the identification of root causes to problems. Organizations consider in the definition of auditable events, the auditing necessary to cover related events such as the steps in distributed, transaction-based processes (e.g., processes that are distributed across multiple organizations) and actions that occur in service-oriented architectures.


