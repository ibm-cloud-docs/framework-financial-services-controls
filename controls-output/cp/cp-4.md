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


# CP-4 - CONTINGENCY PLAN TESTING

## Requirements
{: #requirements}

The organization:

- \[a.\] Tests the contingency plan for the information system [at least annually] using [functional exercises] to determine the effectiveness of the plan and the organizational readiness to execute the plan;

- \[b.\] Reviews the contingency plan test results; and

- \[c.\] Initiates corrective actions, if needed.

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

Tests should be conducted in as close to an operational environment as possible.  If feasible, an actual test of the components or systems used to conduct daily operations should be used.

Test documentation must ensure contingency planning metrics such as the RTO, RPO and maximum tolerable downtime (MTD) are verified during testing.

Contingency Plan test reports must be completed within 30 days after completing the Contingency Plan Test.

If lessons learned result in any necessary improvements to existing processes, ensure they are incorporated into the contingency plan no later than 30 days following all contingency events and exercises.

Critical issues discovered during contingency plan testing must be addressed within 45 calendars day.

Contingency plan tests should increase in scope over time in order to validate the operability of the plan and system components in an operational environment.

The organization must participate in customers&#39; and other third parties&#39; contingency plan tests as required.

## Control Supplemental Guidance
{: #supplemental_guidance}

Methods for testing contingency plans to determine the effectiveness of the plans and to identify potential weaknesses in the plans include, for example, walk-through and tabletop exercises, checklists, simulations (parallel, full interrupt), and comprehensive exercises. Organizations conduct testing based on the continuity requirements in contingency plans and include a determination of the effects on organizational operations, assets, and individuals arising due to contingency operations. Organizations have flexibility and discretion in the breadth, depth, and timelines of corrective actions.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| cp-4_prm_1 | at least annually | organization-defined frequency |
| cp-4_prm_2 | functional exercises | organization-defined tests |