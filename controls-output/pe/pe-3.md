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


# PE-3 - Physical Access Control
{: #pe-3}

## Requirements
{: #requirements}

The organization:

- \[a.\] Enforces physical access authorizations at [organization-defined entry/exit points to the facility where the information system resides] by;

  - \[1.\] Verifying individual access authorizations before granting access to the facility; and
  - \[2.\] Controlling ingress/egress to the facility using [locks, guards, badge systems, and video cameras];

- \[b.\] Maintains physical access audit logs for [organization-defined entry/exit points];

- \[c.\] Provides [organization-defined security safeguards] to control access to areas within the facility officially designated as publicly accessible;

- \[d.\] Escorts visitors and monitors visitor activity [in all circumstances within restricted access area where the information system resides];

- \[e.\] Secures keys, combinations, and other physical access devices;

- \[f.\] Inventories [organization-defined physical access devices] every [at least annually]; and

- \[g.\] Changes combinations and keys [at least annually] and/or when keys are lost, combinations are compromised, or individuals are transferred or terminated.

## Control Supplemental Guidance
{: #supplemental_guidance}

This control applies to organizational employees and visitors. Individuals (e.g., employees, contractors, and others) with permanent physical access authorization credentials are not considered visitors. Organizations determine the types of facility guards needed including, for example, professional physical security staff or other personnel such as administrative staff or information system users. Physical access devices include, for example, keys, locks, combinations, and card readers. Safeguards for publicly accessible areas within organizational facilities include, for example, cameras, monitoring by guards, and isolating selected information systems and/or system components in secured areas. Physical access control systems comply with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance. The Federal Identity, Credential, and Access Management Program provides implementation guidance for identity, credential, and access management capabilities for physical access control systems. Organizations have flexibility in the types of audit logs employed. Audit logs can be procedural (e.g., a written log of individuals accessing the facility and when such access occurred), automated (e.g., capturing ID provided by a PIV card), or some combination thereof. Physical access points can include facility access points, interior access points to information systems and/or components requiring supplemental access controls, or both. Components of organizational information systems (e.g., workstations, terminals) may be located in areas designated as publicly accessible with organizations safeguarding access to such devices.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| pe-3_prm_1 |  | organization-defined entry/exit points to the facility where the information system resides |
| pe-3_prm_2 | locks, guards, badge systems, and video cameras | Choose one or more: organization-defined physical access control systems/devices; guards |
| pe-3_prm_3 |  | organization-defined physical access control systems/devices |
| pe-3_prm_4 |  | organization-defined entry/exit points |
| pe-3_prm_5 |  | organization-defined security safeguards |
| pe-3_prm_6 | in all circumstances within restricted access area where the information system resides | organization-defined circumstances requiring visitor escorts and monitoring |
| pe-3_prm_7 |  | organization-defined physical access devices |
| pe-3_prm_8 | at least annually | organization-defined frequency |
| pe-3_prm_9 | at least annually | organization-defined frequency |