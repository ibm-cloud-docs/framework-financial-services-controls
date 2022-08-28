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


# PL-2 - SYSTEM SECURITY PLAN

## Requirements
{: #requirements}

The organization:

- \[a.\] Develops a security plan for the information system that:

  - \[1.\] Is consistent with the organization’s enterprise architecture;
  - \[2.\] Explicitly defines the authorization boundary for the system;
  - \[3.\] Describes the operational context of the information system in terms of missions and business processes;
  - \[4.\] Provides the security categorization of the information system including supporting rationale;
  - \[5.\] Describes the operational environment for the information system and relationships with or connections to other information systems;
  - \[6.\] Provides an overview of the security requirements for the system;
  - \[7.\] Identifies any relevant overlays, if applicable;
  - \[8.\] Describes the security controls in place or planned for meeting those requirements including a rationale for the tailoring decisions; and
  - \[9.\] Is reviewed and approved by the authorizing official or designated representative prior to plan implementation;

- \[b.\] Distributes copies of the security plan and communicates subsequent changes to the plan to [organization-defined personnel or roles];

- \[c.\] Reviews the security plan for the information system [at least annually];

- \[d.\] Updates the plan to address changes to the information system/environment of operation or problems identified during plan implementation or security control assessments; and

- \[e.\] Protects the security plan from unauthorized disclosure and modification.

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

The organization shall maintain a catalog of all customer metadata processed and/or transmitted by the organization on behalf of the customer.  Metadata should be defined by each customer.

The organization must document all information flows that involve the transfer of customer data.  An information flow control policy must be developed and maintained that indicates the source and destination of each flow, the system of record and whether the information is altered during transmission.

## Control Supplemental Guidance
{: #supplemental_guidance}

Security plans relate security requirements to a set of security controls and control enhancements. Security plans also describe, at a high level, how the security controls and control enhancements meet those security requirements, but do not provide detailed, technical descriptions of the specific design or implementation of the controls/enhancements. Security plans contain sufficient information (including the specification of parameter values for assignment and selection statements either explicitly or by reference) to enable a design and implementation that is unambiguously compliant with the intent of the plans and subsequent determinations of risk to organizational operations and assets, individuals, other organizations, and the Nation if the plan is implemented as intended. Organizations can also apply tailoring guidance to the security control baselines in Appendix D and CNSS Instruction 1253 to develop overlays for community-wide use or to address specialized requirements, technologies, or missions/environments of operation (e.g., DoD-tactical, Federal Public Key Infrastructure, or Federal Identity, Credential, and Access Management, space operations). Appendix I provides guidance on developing overlays. Security plans need not be single documents; the plans can be a collection of various documents including documents that already exist. Effective security plans make extensive use of references to policies, procedures, and additional documents (e.g., design and implementation specifications) where more detailed information can be obtained. This reduces the documentation requirements associated with security programs and maintains security-related information in other established management/operational areas related to enterprise architecture, system development life cycle, systems engineering, and acquisition. For example, security plans do not contain detailed contingency plan or incident response plan information but instead provide explicitly or by reference, sufficient information to define what needs to be accomplished by those plans.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| pl-2_prm_1 |  | organization-defined personnel or roles |
| pl-2_prm_2 | at least annually | organization-defined frequency |