---

copyright:
  years: 2020, 2022

lastupdated: "2022-10-06"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# SC-8 - Transmission Confidentiality and Integrity
{: #sc-8}

## Control requirements
{: #control-requirements}

SC-8 - 0
    : The information system protects the [confidentiality, integrity, AND availability] of transmitted information.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Connecting application provider to the management VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-management)
- [Consumer connectivity to workload VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-workload)
- [Creating and connecting the management and workload VPCs](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-create-vpcs)
- [Data encryption in transit](/docs/framework-financial-services?topic=framework-financial-services-shared-encryption-in-transit)
- [Working with {{site.data.keyword.openshiftlong_notm}}](/docs/framework-financial-services?topic=framework-financial-services-shared-containers-openshift)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.6.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- 3000103: Check whether Cloud Object Storage is accessible only through HTTPS 
- 3000407: Check whether Virtual Private Cloud (VPC) is configured with at least TLS v1.2 for all inbound traffic through a load balancer 
- 3000432: Check whether Application Load Balancer for VPC pool uses the HTTPS protocol for HTTPS listeners 
- 3000433: Check whether Application Load Balancer for VPC is configured to convert HTTP client requests to HTTPS 
- 3000434: Check whether Application Load Balancer for VPC uses HTTPS (SSL & TLS) instead of HTTP 
- 3000470: Check whether Cloud Internet Services (CIS) has TLS mode set to End-to-End CA signed 
- 3000701: Check whether App ID webhooks are using HTTPS only 
- 3000702: Check whether App ID email dispatchers are using HTTPS only 
- 3000703: Check whether App ID redirect URIs are using HTTPS only 
- 3000906: Check whether OpenShift Ingress is configured with at least TLS v1.2 for all inbound traffic

## NIST supplemental guidance
{: #nist-supplemental-guidance}

This control applies to both internal and external networks and all types of information system components from which information can be transmitted (e.g., servers, mobile devices, notebook computers, printers, copiers, scanners, facsimile machines). Communication paths outside the physical protection of a controlled boundary are exposed to the possibility of interception and modification. Protecting the confidentiality and/or integrity of organizational information can be accomplished by physical means (e.g., by employing protected distribution systems) or by logical means (e.g., employing encryption techniques). Organizations relying on commercial providers offering transmission services as commodity services rather than as fully dedicated services (i.e., services which can be highly specialized to individual customer needs), may find it difficult to obtain the necessary assurances regarding the implementation of needed security controls for transmission confidentiality/integrity. In such situations, organizations determine what types of confidentiality/integrity services are available in standard, commercial telecommunication service packages. If it is infeasible or impractical to obtain the necessary security controls and assurances of control effectiveness through appropriate contracting vehicles, organizations implement appropriate compensating security controls or explicitly accept the additional risk.





