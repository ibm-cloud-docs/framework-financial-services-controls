---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# SC-8 - Transmission Confidentiality and Integrity
{: #sc-8}

## Control requirements
{: #control-requirements}



### SC-8 - 0


Protect the _[IBM Assignment: confidentiality, integrity, AND availability]_ of transmitted information.









## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.


- [Data encryption in transit](/docs/framework-financial-services?topic=framework-financial-services-shared-encryption-in-transit)


- [Working with {{site.data.keyword.openshiftlong_notm}}](/docs/framework-financial-services?topic=framework-financial-services-shared-containers-openshift)


- [Ensuring isolation between {{site.data.keyword.satelliteshort}} management functions and workload functions](/docs/framework-financial-services?topic=framework-financial-services-satellite-architecture-connectivity-management-isolation)


- [Consumer connectivity to workload resources](/docs/framework-financial-services?topic=framework-financial-services-satellite-architecture-connectivity-workload)


- [Creating and connecting the management and workload VPCs](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-create-vpcs)


- [Connecting application provider to the management VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-management)


- [Consumer connectivity to workload VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-workload)






## NIST supplemental guidance
{: #nist-supplemental-guidance}

Protecting the confidentiality and integrity of transmitted information applies to internal and external networks as well as any system components that can transmit information, including servers, notebook computers, desktop computers, mobile devices, printers, copiers, scanners, facsimile machines, and radios. Unprotected communication paths are exposed to the possibility of interception and modification. Protecting the confidentiality and integrity of information can be accomplished by physical or logical means. Physical protection can be achieved by using protected distribution systems. A protected distribution system is a wireline or fiber-optics telecommunications system that includes terminals and adequate electromagnetic, acoustical, electrical, and physical controls to permit its use for the unencrypted transmission of classified information. Logical protection can be achieved by employing encryption techniques.
Organizations that rely on commercial providers who offer transmission services as commodity services rather than as fully dedicated services may find it difficult to obtain the necessary assurances regarding the implementation of needed controls for transmission confidentiality and integrity. In such situations, organizations determine what types of confidentiality or integrity services are available in standard, commercial telecommunications service packages. If it is not feasible to obtain the necessary controls and assurances of control effectiveness through appropriate contracting vehicles, organizations can implement appropriate compensating controls.
