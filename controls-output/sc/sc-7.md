---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# SC-7 - Boundary Protection
{: #sc-7}

## Control requirements
{: #control-requirements}



### SC-7 (a)


Monitor and control communications at the external managed interfaces to the system and at key internal managed interfaces within the system.


### SC-7 (b)


Implement subnetworks for publicly accessible system components that are _[Selection: physically; logically]_ separated from internal organizational networks.


### SC-7 (c)


Connect to external networks or systems only through managed interfaces consisting of boundary protection devices arranged in accordance with an organizational security and privacy architecture.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

The organization "service delivery" and "corporate" environments must be maintained as separate environments. That is, clear physical and/or logical boundaries separating the two environments must exist.

If Voice over Internet Protocol (VoIP) technology is in use, (a) establish usage restrictions and implementation guidance based on the potential to cause damage to the information system if used maliciously; and (b) authorize, monitor, and control the use of VoIP within the information system.




## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.


- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)


- [Connectivity to {{site.data.keyword.cloud_notm}} services with Satellite Link](/docs/framework-financial-services?topic=framework-financial-services-satellite-architecture-connectivity-to-services)


- [Ensuring isolation between {{site.data.keyword.satelliteshort}} management functions and workload functions](/docs/framework-financial-services?topic=framework-financial-services-satellite-architecture-connectivity-management-isolation)


- [Accessing external resources from the {{site.data.keyword.satelliteshort}} location](/docs/framework-financial-services?topic=framework-financial-services-satellite-architecture-connectivity-to-external)


- [Consumer connectivity to workload resources](/docs/framework-financial-services?topic=framework-financial-services-satellite-architecture-connectivity-workload)


- [Creating and connecting the management and workload VPCs](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-create-vpcs)


- [Accessing the public internet](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-to-internet)


- [Connecting application provider to the management VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-management)


- [Connectivity to {{site.data.keyword.cloud_notm}} services with private endpoints](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-to-services)


- [Consumer connectivity to workload VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-workload)






## NIST supplemental guidance
{: #nist-supplemental-guidance}

Managed interfaces include gateways, routers, firewalls, guards, network-based malicious code analysis, virtualization systems, or encrypted tunnels implemented within a security architecture. Subnetworks that are physically or logically separated from internal networks are referred to as demilitarized zones or DMZs. Restricting or prohibiting interfaces within organizational systems includes restricting external web traffic to designated web servers within managed interfaces, prohibiting external traffic that appears to be spoofing internal addresses, and prohibiting internal traffic that appears to be spoofing external addresses. Commercial telecommunications services are provided by network components and consolidated management systems shared by customers. These services may also include third party-provided access lines and other service elements. Such services may represent sources of increased risk despite contract security provisions. Boundary protection may be implemented as a common control for all or part of an organizational network such that the boundary to be protected is greater than a system-specific boundary (i.e., an authorization boundary).
