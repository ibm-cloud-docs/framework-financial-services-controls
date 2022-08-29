---
copyright:
  years: 2020, 2022
lastupdated: "2022-08-29"
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


# CP-2 - Contingency Plan
{: #cp-2}

## Requirements
{: #requirements}

The organization:

- \[a.\] Develops a contingency plan for the information system that:

  - \[1.\] Identifies essential missions and business functions and associated contingency requirements;
  - \[2.\] Provides recovery objectives, restoration priorities, and metrics;
  - \[3.\] Addresses contingency roles, responsibilities, assigned individuals with contact information;
  - \[4.\] Addresses maintaining essential missions and business functions despite an information system disruption, compromise, or failure;
  - \[5.\] Addresses eventual, full information system restoration without deterioration of the security safeguards originally planned and implemented; and
  - \[6.\] Is reviewed and approved by [designated senior management personnel who is not an author or contributor to the plan];

- \[b.\] Distributes copies of the contingency plan to [organization-defined key contingency personnel (identified by name and/or by role) and organizational elements];

- \[c.\] Coordinates contingency planning activities with incident handling activities;

- \[d.\] Reviews the contingency plan for the information system [annually or within 90 calendar days of significant changes];

- \[e.\] Updates the contingency plan to address changes to the organization, information system, or environment of operation and problems encountered during contingency plan implementation, execution, or testing;

- \[f.\] Communicates contingency plan changes to [organization-defined key contingency personnel (identified by name and/or by role) and organizational elements]; and

- \[g.\] Protects the contingency plan from unauthorized disclosure and modification.

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

Documentation includes plan and playbook(s).

The organization must provide required pre-test documentation prior to test initiation. The customer must provide the organization with what is included in pre-test documentation.

## Control Supplemental Guidance
{: #supplemental_guidance}

Contingency planning for information systems is part of an overall organizational program for achieving continuity of operations for mission/business functions. Contingency planning addresses both information system restoration and implementation of alternative mission/business processes when systems are compromised. The effectiveness of contingency planning is maximized by considering such planning throughout the phases of the system development life cycle. Performing contingency planning on hardware, software, and firmware development can be an effective means of achieving information system resiliency. Contingency plans reflect the degree of restoration required for organizational information systems since not all systems may need to fully recover to achieve the level of continuity of operations desired. Information system recovery objectives reflect applicable laws, Executive Orders, directives, policies, standards, regulations, and guidelines. In addition to information system availability, contingency plans also address other security-related events resulting in a reduction in mission and/or business effectiveness, such as malicious attacks compromising the confidentiality or integrity of information systems. Actions addressed in contingency plans include, for example, orderly/graceful degradation, information system shutdown, fallback to a manual mode, alternate information flows, and operating in modes reserved for when systems are under attack. By closely coordinating contingency planning with incident handling activities, organizations can ensure that the necessary contingency planning activities are in place and activated in the event of a security incident.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| cp-2_prm_1 | designated senior management personnel who is not an author or contributor to the plan | organization-defined personnel or roles |
| cp-2_prm_2 |  | organization-defined key contingency personnel (identified by name and/or by role) and organizational elements |
| cp-2_prm_3 | annually or within 90 calendar days of significant changes | organization-defined frequency |
| cp-2_prm_4 |  | organization-defined key contingency personnel (identified by name and/or by role) and organizational elements |