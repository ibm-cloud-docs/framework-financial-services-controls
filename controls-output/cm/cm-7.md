---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# CM-7 - Least Functionality
{: #cm-7}

## Control requirements
{: #control-requirements}



### CM-7 (a)


Configure the system to provide only _[Assignment: organization-defined mission essential capabilities]_.


### CM-7 (b)


Prohibit or restrict the use of the following functions, ports, protocols, software, and/or services: _[Assignment: organization-defined prohibited or restricted functions, system ports, protocols, software, and/or services]_.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

Container Security Requirements:
• Images must be restricted to only utilizing necessary features to reduce the attack surface and potential vulnerabilities (for example: only necessary libraries must be implemented).







## NIST supplemental guidance
{: #nist-supplemental-guidance}

Systems provide a wide variety of functions and services. Some of the functions and services routinely provided by default may not be necessary to support essential organizational missions, functions, or operations. Additionally, it is sometimes convenient to provide multiple services from a single system component, but doing so increases risk over limiting the services provided by that single component. Where feasible, organizations limit component functionality to a single function per component. Organizations consider removing unused or unnecessary software and disabling unused or unnecessary physical and logical ports and protocols to prevent unauthorized connection of components, transfer of information, and tunneling. Organizations employ network scanning tools, intrusion detection and prevention systems, and end-point protection technologies, such as firewalls and host-based intrusion detection systems, to identify and prevent the use of prohibited functions, protocols, ports, and services. Least functionality can also be achieved as part of the fundamental design and development of the system (see SA-8, SC-2, and SC-3).
