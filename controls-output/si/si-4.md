---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# SI-4 - System Monitoring
{: #si-4}

## Control requirements
{: #control-requirements}



### SI-4 (a)


Monitor the system to detect:
1. Attacks and indicators of potential attacks in accordance with the following monitoring objectives: _[Assignment: organization-defined monitoring objectives]_; and
2. Unauthorized local, network, and remote connections.


### SI-4 (b)


Identify unauthorized use of the system through the following techniques and methods: _[Assignment: organization-defined techniques and methods]_.


### SI-4 (c)


Invoke internal monitoring capabilities or deploy monitoring devices:
1. Strategically within the system to collect organization-determined essential information; and
2. At ad hoc locations within the system to track specific types of transactions of interest to the organization.


### SI-4 (d)


Analyze detected events and anomalies.


### SI-4 (e)


Adjust the level of system monitoring activity when there is a change in risk to organizational operations and assets, individuals, other organizations, or the Nation.


### SI-4 (f)


Obtain legal opinion regarding system monitoring activities.


### SI-4 (g)


Provide _[Assignment: organization-defined system monitoring information]_ to _[Assignment: organization-defined personnel or roles]_ _[Selection (one or more): as needed; _[Assignment: organization-defined frequency]_]_.












## NIST supplemental guidance
{: #nist-supplemental-guidance}

System monitoring includes external and internal monitoring. External monitoring includes the observation of events occurring at external interfaces to the system. Internal monitoring includes the observation of events occurring within the system. Organizations monitor systems by observing audit activities in real time or by observing other system aspects such as access patterns, characteristics of access, and other actions. The monitoring objectives guide and inform the determination of the events. System monitoring capabilities are achieved through a variety of tools and techniques, including intrusion detection and prevention systems, malicious code protection software, scanning tools, audit record monitoring software, and network monitoring software.
Depending on the security architecture, the distribution and configuration of monitoring devices may impact throughput at key internal and external boundaries as well as at other locations across a network due to the introduction of network throughput latency. If throughput management is needed, such devices are strategically located and deployed as part of an established organization-wide security architecture. Strategic locations for monitoring devices include selected perimeter locations and near key servers and server farms that support critical applications. Monitoring devices are typically employed at the managed interfaces associated with controls SC-7 and AC-17. The information collected is a function of the organizational monitoring objectives and the capability of systems to support such objectives. Specific types of transactions of interest include Hypertext Transfer Protocol (HTTP) traffic that bypasses HTTP proxies. System monitoring is an integral part of organizational continuous monitoring and incident response programs, and output from system monitoring serves as input to those programs. System monitoring requirements, including the need for specific types of system monitoring, may be referenced in other controls (e.g., AC-2g, AC-2(7), AC-2(12)(a), AC-17(1), AU-13, AU-13(1), AU-13(2), CM-3f, CM-6d, MA-3a, MA-4a, SC-5(3)(b), SC-7a, SC-7(24)(b), SC-18b, SC-43b). Adjustments to levels of system monitoring are based on law enforcement information, intelligence information, or other sources of information. The legality of system monitoring activities is based on applicable laws, executive orders, directives, regulations, policies, standards, and guidelines.
