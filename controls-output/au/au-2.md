---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# AU-2 - Event Logging
{: #au-2}

## Control requirements
{: #control-requirements}



### AU-2 (a)


Identify the types of events that the system is capable of logging in support of the audit function: _[IBM Assignment: for required audit events, refer to Additional FS-ready public cloud Guidance]_.


### AU-2 (b)


Coordinate the event logging function with other organizational entities requiring audit-related information to guide and inform the selection criteria for events to be logged.


### AU-2 (c)


Specify the following event types for logging within the system: _[IBM Assignment: auditable events defined in AU-2 a. to be audited continually for each identified event]_.


### AU-2 (d)


Provide a rationale for why the event types selected for logging are deemed to be adequate to support after-the-fact investigations of incidents.


### AU-2 (e)


Review and update the event types selected for logging _[IBM Assignment: annually and whenever there is a change in the threat environment]_.






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
     o All changes, additions, or deletions to any account such as lock, unlock, password reset, permission changes,
     o Modification to system time / time-synchronization configuration,
     o Log files: access to logs files; initialization, stopping or pausing of logging, log modification, changes to access permission on log files,
     o Files and system level objects creation and deletion,
     o Attempts to perform unauthorized functions or access data the user is not authorized to access,
     o Modification of security rules,
     o Application and related systems start-ups and shut-downs
- For privileged accounts:
     o Attempts to execute privilege elevation
     o System errors relevant to security events, including but not limited to SQL errors that indicate a SQL injection, fuzzing, multiple failed logins, failed configuration change, failed/disabled anti-virus software, service failures
     o Web access events in extended log format

The above security audit logging events are required for all environments, e.g., production, development, user acceptance testing.

Container Security Requirements: 
• Logging must be enabled for container runtimes.
• Log events such as process execution, network connections, privilege escalation, and storage activity within each container must be logged. 







## NIST supplemental guidance
{: #nist-supplemental-guidance}

An event is an observable occurrence in a system. The types of events that require logging are those events that are significant and relevant to the security of systems and the privacy of individuals. Event logging also supports specific monitoring and auditing needs. Event types include password changes, failed logons or failed accesses related to systems, security or privacy attribute changes, administrative privilege usage, PIV credential usage, data action changes, query parameters, or external credential usage. In determining the set of event types that require logging, organizations consider the monitoring and auditing appropriate for each of the controls to be implemented. For completeness, event logging includes all protocols that are operational and supported by the system.
To balance monitoring and auditing requirements with other system needs, event logging requires identifying the subset of event types that are logged at a given point in time. For example, organizations may determine that systems need the capability to log every file access successful and unsuccessful, but not activate that capability except for specific circumstances due to the potential burden on system performance. The types of events that organizations desire to be logged may change. Reviewing and updating the set of logged events is necessary to help ensure that the events remain relevant and continue to support the needs of the organization. Organizations consider how the types of logging events can reveal information about individuals that may give rise to privacy risk and how best to mitigate such risks. For example, there is the potential to reveal personally identifiable information in the audit trail, especially if the logging event is based on patterns or time of usage.
Event logging requirements, including the need to log specific event types, may be referenced in other controls and control enhancements. These include AC-2(4), AC-3(10), AC-6(9), AC-17(1), CM-3f, CM-5(1), IA-3(3.b), MA-4(1), MP-4(2), PE-3, PM-21, PT-7, RA-8, SC-7(9), SC-7(15), SI-3(8), SI-4(22), SI-7(8), and SI-10(1). Organizations include event types that are required by applicable laws, executive orders, directives, policies, regulations, standards, and guidelines. Audit records can be generated at various levels, including at the packet level as information traverses the network. Selecting the appropriate level of event logging is an important part of a monitoring and auditing capability and can identify the root causes of problems. When defining event types, organizations consider the logging necessary to cover related event types, such as the steps in distributed, transaction-based processes and the actions that occur in service-oriented architectures.
