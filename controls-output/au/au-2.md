---
copyright:
  years: 2020, 2022
lastupdated: "2022-08-28"
keywords: 
subcollection: controls
---


{:android: data-hd-operatingsystem="android"}
{:api: .ph data-hd-interface="api"}
{:audio: .audio}
{:authenticated-content: .authenticated-content}
{:beta: .beta}
{:c#: .ph data-hd-programlang="c#"}
{:cli: .ph data-hd-interface="cli"}
{:codeblock: .codeblock}
{:curl: .ph data-hd-programlang="curl"}
{:deprecated: .deprecated}
{:dotnet-standard: .ph data-hd-programlang="dotnet-standard"}
{:experimental: .experimental}
{:external: .external target="_blank"}
{:faq: data-hd-content-type="faq"}
{:generic: data-hd-programlang="generic"}
{:go: .ph data-hd-programlang="go"}
{:help: data-hd-content-type="help"}
{:here: .ph data-hd-vposition="here"}
{:hide-dashboard: .hide-dashboard}
{:hide-in-docs: .hide-in-docs}
{:important: .important}
{:ios: data-hd-operatingsystem="ios"}
{:java: .ph data-hd-programlang="java"}
{:javascript: .ph data-hd-programlang="javascript"}
{:middle: .ph data-hd-position="middle"}
{:node: .ph data-hd-programlang="node"}
{:note: .note}
{:objectc: .ph data-hd-programlang="Objective C"}
{:php: .ph data-hd-programlang="PHP"}
{:pre: .pre}
{:preview: .preview}
{:python: .ph data-hd-programlang="python"}
{:release-note: data-hd-content-type="release-note"}
{:right: .ph data-hd-position="right"}
{:row-headers: .row-headers}
{:ruby: .ph data-hd-programlang="ruby"}
{:screen: .screen}
{:shortdesc: .shortdesc}
{:step: data-tutorial-type="step"}
{:support: data-reuse="support"}
{:swift: .ph data-hd-programlang="swift"}
{:term: .term}
{:terraform: .ph data-hd-interface="terraform"}
{:tip: .tip}
{:troubleshoot: data-hd-content-type="troubleshoot"}
{:tsCauses: .tsCauses}
{:tsResolve: .tsResolve}
{:tsSymptoms: .tsSymptoms}
{:tutorial: data-hd-content-type="tutorial"}
{:ui: .ph data-hd-interface="ui"}
{:unity: .ph data-hd-programlang="unity"}
{:vbnet: .ph data-hd-programlang="vb.net"}
{:video: .video}


# AU-2 - AUDIT EVENTS

## Requirements
{: #requirements}

The organization:

- \[a.\] Determines that the information system is capable of auditing the following events: [for required audit events, refer to Additional FS-ready public cloud Guidance];

- \[b.\] Coordinates the security audit function with other organizational entities requiring audit-related information to enhance mutual support and to help guide the selection of auditable events;

- \[c.\] Provides a rationale for why the auditable events are deemed to be adequate to support after-the-fact investigations of security incidents; and

- \[d.\] Determines that the following events are to be audited within the information system: [auditable events defined in AU-2 a. to be audited continually for each identified event].

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

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

## Control Supplemental Guidance
{: #supplemental_guidance}

An event is any observable occurrence in an organizational information system. Organizations identify audit events as those events which are significant and relevant to the security of information systems and the environments in which those systems operate in order to meet specific and ongoing audit needs. Audit events can include, for example, password changes, failed logons, or failed accesses related to information systems, administrative privilege usage, PIV credential usage, or third-party credential usage. In determining the set of auditable events, organizations consider the auditing appropriate for each of the security controls to be implemented. To balance auditing requirements with other information system needs, this control also requires identifying that subset of auditable events that are audited at a given point in time. For example, organizations may determine that information systems must have the capability to log every file access both successful and unsuccessful, but not activate that capability except for specific circumstances due to the potential burden on system performance. Auditing requirements, including the need for auditable events, may be referenced in other security controls and control enhancements. Organizations also include auditable events that are required by applicable federal laws, Executive Orders, directives, policies, regulations, and standards. Audit records can be generated at various levels of abstraction, including at the packet level as information traverses the network. Selecting the appropriate level of abstraction is a critical aspect of an audit capability and can facilitate the identification of root causes to problems. Organizations consider in the definition of auditable events, the auditing necessary to cover related events such as the steps in distributed, transaction-based processes (e.g., processes that are distributed across multiple organizations) and actions that occur in service-oriented architectures.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| au-2_prm_1 | for required audit events, refer to Additional FS-ready public cloud Guidance | organization-defined auditable events |
| au-2_prm_2 | auditable events defined in AU-2 a. to be audited continually for each identified event | organization-defined audited events (the subset of the auditable events defined in AU-2 a.) along with the frequency of (or situation requiring) auditing for each identified event |