---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# SC-5 - Denial-of-service Protection
{: #sc-5}

## Control requirements
{: #control-requirements}



### SC-5 (a)


_[IBM Assignment: Protect against]_ the effects of the following types of denial-of-service events: _[IBM Assignment: application and volumetric based attacks (OSI layers 3, 4, 6, and 7)]_.


### SC-5 (b)


Employ the following controls to achieve the denial-of-service objective: _[IBM Assignment: annual testing of the documented DoS and DDoS mitigation technologies]_.









## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.


- [Connectivity to {{site.data.keyword.cloud_notm}} services with Satellite Link](/docs/framework-financial-services?topic=framework-financial-services-satellite-architecture-connectivity-to-services)


- [Ensuring isolation between {{site.data.keyword.satelliteshort}} management functions and workload functions](/docs/framework-financial-services?topic=framework-financial-services-satellite-architecture-connectivity-management-isolation)


- [Accessing external resources from the {{site.data.keyword.satelliteshort}} location](/docs/framework-financial-services?topic=framework-financial-services-satellite-architecture-connectivity-to-external)


- [Consumer connectivity to workload resources](/docs/framework-financial-services?topic=framework-financial-services-satellite-architecture-connectivity-workload)


- [Creating and connecting the management and workload VPCs](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-create-vpcs)


- [Accessing the public internet](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-to-internet)


- [Connectivity to {{site.data.keyword.cloud_notm}} services with private endpoints](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-to-services)


- [Consumer connectivity to workload VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-workload)






## NIST supplemental guidance
{: #nist-supplemental-guidance}

Denial-of-service events may occur due to a variety of internal and external causes, such as an attack by an adversary or a lack of planning to support organizational needs with respect to capacity and bandwidth. Such attacks can occur across a wide range of network protocols (e.g., IPv4, IPv6). A variety of technologies are available to limit or eliminate the origination and effects of denial-of-service events. For example, boundary protection devices can filter certain types of packets to protect system components on internal networks from being directly affected by or the source of denial-of-service attacks. Employing increased network capacity and bandwidth combined with service redundancy also reduces the susceptibility to denial-of-service events.
