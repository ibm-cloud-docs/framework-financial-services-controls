---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-02"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# SI-4 - Information System Monitoring
{: #si-4}

## Requirements
{: #requirements}

The organization:

- \[a.\] Monitors the information system to detect:

  - \[1.\] Attacks and indicators of potential attacks in accordance with [organization-defined monitoring objectives]; and
  - \[2.\] Unauthorized local, network, and remote connections;

- \[b.\] Identifies unauthorized use of the information system through [organization-defined techniques and methods];

- \[c.\] Deploys monitoring devices:

  - \[1.\] Strategically within the information system to collect organization-determined essential information; and
  - \[2.\] At ad hoc locations within the system to track specific types of transactions of interest to the organization;

- \[d.\] Protects information obtained from intrusion-monitoring tools from unauthorized access, modification, and deletion;

- \[e.\] Heightens the level of information system monitoring activity whenever there is an indication of increased risk to organizational operations and assets, individuals, other organizations, or the Nation based on law enforcement information, intelligence information, or other credible sources of information;

- \[f.\] Obtains legal opinion with regard to information system monitoring activities in accordance with applicable federal laws, Executive Orders, directives, policies, or regulations; and

- \[g.\] Provides [organization-defined information system monitoring information] to [organization-defined personnel or roles] [as needed; organization-defined frequency].

## Control Supplemental Guidance
{: #supplemental-guidance}

Information system monitoring includes external and internal monitoring. External monitoring includes the observation of events occurring at the information system boundary (i.e., part of perimeter defense and boundary protection). Internal monitoring includes the observation of events occurring within the information system. Organizations can monitor information systems, for example, by observing audit activities in real time or by observing other system aspects such as access patterns, characteristics of access, and other actions. The monitoring objectives may guide determination of the events. Information system monitoring capability is achieved through a variety of tools and techniques (e.g., intrusion detection systems, intrusion prevention systems, malicious code protection software, scanning tools, audit record monitoring software, network monitoring software). Strategic locations for monitoring devices include, for example, selected perimeter locations and near server farms supporting critical applications, with such devices typically being employed at the managed interfaces associated with controls SC-7 and AC-17. Einstein network monitoring devices from the Department of Homeland Security can also be included as monitoring devices. The granularity of monitoring information collected is based on organizational monitoring objectives and the capability of information systems to support such objectives. Specific types of transactions of interest include, for example, Hyper Text Transfer Protocol (HTTP) traffic that bypasses HTTP proxies. Information system monitoring is an integral part of organizational continuous monitoring and incident response programs. Output from system monitoring serves as input to continuous monitoring and incident response programs. A network connection is any connection with a device that communicates through a network (e.g., local area network, Internet). A remote connection is any connection with a device communicating through an external network (e.g., the Internet). Local, network, and remote connections can be either wired or wireless.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| si-4_prm_1 |  | organization-defined monitoring objectives |
| si-4_prm_2 |  | organization-defined techniques and methods |
| si-4_prm_3 |  | organization-defined information system monitoring information |
| si-4_prm_4 |  | organization-defined personnel or roles |
| si-4_prm_5 |  | Choose one or more: as needed; organization-defined frequency |
| si-4_prm_6 |  | organization-defined frequency |

