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


# SI-6 - Security Function Verification
{: #si-6}

## Requirements
{: #requirements}

The information system:

- \[a.\] Verifies the correct operation of [organization-defined security functions];

- \[b.\] Performs this verification [to include upon system startup and/or restart and at least monthly];

- \[c.\] Notifies [to include system administrators and security personnel] of failed security verification tests; and

- \[d.\] [shuts the information system down; restarts the information system; to include notification of system administrators and security personnel] when anomalies are discovered.

## Control Supplemental Guidance
{: #supplemental_guidance}

Transitional states for information systems include, for example, system startup, restart, shutdown, and abort. Notifications provided by information systems include, for example, electronic alerts to system administrators, messages to local computer consoles, and/or hardware indications such as lights.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| si-6_prm_1 |  | organization-defined security functions |
| si-6_prm_2 | to include upon system startup and/or restart and at least monthly | Choose one or more: organization-defined system transitional states; upon command by user with appropriate privilege; organization-defined frequency |
| si-6_prm_3 |  | organization-defined system transitional states |
| si-6_prm_4 |  | organization-defined frequency |
| si-6_prm_5 | to include system administrators and security personnel | organization-defined personnel or roles |
| si-6_prm_6 |  | Choose one or more: shuts the information system down; restarts the information system; to include notification of system administrators and security personnel |
| si-6_prm_7 | to include notification of system administrators and security personnel | organization-defined alternative action(s) |