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


# CA-8 - Penetration Testing
{: #ca-8}

## Requirements
{: #requirements}

The organization conducts penetration testing [prior to production use, at least annually, and after significant changes] on [applications that are utilized by FS-ready public cloud customers or process customer’s data].

## Control Supplemental Guidance
{: #supplemental_guidance}

Penetration testing is a specialized type of assessment conducted on information systems or individual system components to identify vulnerabilities that could be exploited by adversaries. Such testing can be used to either validate vulnerabilities or determine the degree of resistance organizational information systems have to adversaries within a set of specified constraints (e.g., time, resources, and/or skills). Penetration testing attempts to duplicate the actions of adversaries in carrying out hostile cyber attacks against organizations and provides a more in-depth analysis of security-related weaknesses/deficiencies. Organizations can also use the results of vulnerability analyses to support penetration testing activities. Penetration testing can be conducted on the hardware, software, or firmware components of an information system and can exercise both physical and technical security controls. A standard method for penetration testing includes, for example: (i) pretest analysis based on full knowledge of the target system; (ii) pretest identification of potential vulnerabilities based on pretest analysis; and (iii) testing designed to determine exploitability of identified vulnerabilities. All parties agree to the rules of engagement before the commencement of penetration testing scenarios. Organizations correlate the penetration testing rules of engagement with the tools, techniques, and procedures that are anticipated to be employed by adversaries carrying out attacks. Organizational risk assessments guide decisions on the level of independence required for personnel conducting penetration testing.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| ca-8_prm_1 | prior to production use, at least annually, and after significant changes | organization-defined frequency |
| ca-8_prm_2 | applications that are utilized by FS-ready public cloud customers or process customer’s data | organization-defined information systems or system components |