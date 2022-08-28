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


# CM-3 - CONFIGURATION CHANGE CONTROL

## Requirements
{: #requirements}

The organization:

- \[a.\] Determines the types of changes to the information system that are configuration-controlled;

- \[b.\] Reviews proposed configuration-controlled changes to the information system and approves or disapproves such changes with explicit consideration for security impact analyses;

- \[c.\] Documents configuration change decisions associated with the information system;

- \[d.\] Implements approved configuration-controlled changes to the information system;

- \[e.\] Retains records of configuration-controlled changes to the information system for [in accordance with record retention policies and procedures];

- \[f.\] Audits and reviews activities associated with configuration-controlled changes to the information system; and

- \[g.\] Coordinates and provides oversight for configuration change control activities through [organization-defined configuration change control element (e.g., committee, board)] that convenes [organization-defined frequency; organization-defined configuration change conditions].

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

The organization must notify impacted customers prior to implementing any changes.  The organization must validate changes after they have been implemented.

All changes to the systems / applications / processes used by the customer must be under a formal change management/control process and must be communicated to the customer prior to implementation. 

All changes to the customer environment (including supporting process) must be configuration-controlled.

The organization&#39;s change management process must address emergency changes.

The organization shall ensure that changes to customer data are subject to change control per customer requirements.  Changes of any type should be communicated to the customer as they arise.

Each change request must be properly documented to  ITIL v3 - Request for Change (RFC) Standards:  Each RFC must have the following fields: 
Unique ID :
Date of submission :
Change Owner :
Initiator of the RFC :
(if not identical with Change Owner)
Proposed Change priority :
 Low
 Normal
 High
 Very High (Emergency Change)
(may be overruled by Change Management during Change assessment)
Reference to Change Proposal
(if the Change is related to a Change Proposal submitted at an earlier stage)
Description of the Change being applied for :
Summary description :
Business case :
Reason for the Change to be implemented :
Consequences if the Change is not implemented :
References (e.g. to a Problem Record triggering this RFC) :
Business areas on the client-side affected by the Change :
Services affected by the Change :
IT infrastructure components (CIs) affected by the Change :
Technology aspects (is a new technology being introduced?) :
Risks : (Risks during the implementation of the Change)
Identified risks :
Counter-measures :
(e.g. reversion procedure)
Back-out strategy for the case of a failed Change implementation :
Time schedule :
(Predicted/suggested time schedule for the implementation)
Estimate of resources for the implementation :
Required personnel resources :
(from which areas?)
Additional supporting documents :
(If applicable, index of additional supporting documents, e.g. the Service Design Package for major additions or modifications to services)
Approval or rejection :
Date :
Person/ body in charge of the approval :
(Change Manager/ CAB/ ECAB)
Change reviewers :
Priority assigned by Change Management :
Restrictions :
If applicable, reasons for rejecting the RFC :.

## Control Supplemental Guidance
{: #supplemental_guidance}

Configuration change controls for organizational information systems involve the systematic proposal, justification, implementation, testing, review, and disposition of changes to the systems, including system upgrades and modifications. Configuration change control includes changes to baseline configurations for components and configuration items of information systems, changes to configuration settings for information technology products (e.g., operating systems, applications, firewalls, routers, and mobile devices), unscheduled/unauthorized changes, and changes to remediate vulnerabilities. Typical processes for managing configuration changes to information systems include, for example, Configuration Control Boards that approve proposed changes to systems. For new development information systems or systems undergoing major upgrades, organizations consider including representatives from development organizations on the Configuration Control Boards. Auditing of changes includes activities before and after changes are made to organizational information systems and the auditing activities required to implement such changes.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| cm-3_prm_1 | in accordance with record retention policies and procedures | organization-defined time period |
| cm-3_prm_2 |  | organization-defined configuration change control element (e.g., committee, board) |
| cm-3_prm_3 |  | Choose one or more: organization-defined frequency; organization-defined configuration change conditions |
| cm-3_prm_4 |  | organization-defined frequency |
| cm-3_prm_5 |  | organization-defined configuration change conditions |