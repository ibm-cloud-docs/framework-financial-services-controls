---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-08"
keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# SC-8 - Transmission Confidentiality And Integrity
{: #sc-8}

## Requirements
{: #requirements}

The information system protects the [confidentiality, integrity, AND availability] of transmitted information.

## Control Supplemental Guidance
{: #supplemental-guidance}

This control applies to both internal and external networks and all types of information system components from which information can be transmitted (e.g., servers, mobile devices, notebook computers, printers, copiers, scanners, facsimile machines). Communication paths outside the physical protection of a controlled boundary are exposed to the possibility of interception and modification. Protecting the confidentiality and/or integrity of organizational information can be accomplished by physical means (e.g., by employing protected distribution systems) or by logical means (e.g., employing encryption techniques). Organizations relying on commercial providers offering transmission services as commodity services rather than as fully dedicated services (i.e., services which can be highly specialized to individual customer needs), may find it difficult to obtain the necessary assurances regarding the implementation of needed security controls for transmission confidentiality/integrity. In such situations, organizations determine what types of confidentiality/integrity services are available in standard, commercial telecommunication service packages. If it is infeasible or impractical to obtain the necessary security controls and assurances of control effectiveness through appropriate contracting vehicles, organizations implement appropriate compensating security controls or explicitly accept the additional risk.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| sc-8_prm_1 | confidentiality, integrity, AND availability | Choose one or more: confidentiality; integrity |


## Related Resources
{: #related_resources}

See the resources that follow to learn more about how to implement this control.

- [Data encryption in transit](/docs/framework-financial-services?topic=framework-financial-services-shared-encryption-in-transit)
- [Working with {{site.data.keyword.openshiftlong_notm}}](/docs/framework-financial-services?topic=framework-financial-services-shared-containers-openshift)

## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- [3000103: Check whether Cloud Object Storage is accessible only through HTTPS](https://cloud.ibm.com/security-compliance/goals/3000103?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000407: Check whether Virtual Private Cloud (VPC) is configured with at least TLS v1.2 for all inbound traffic through a load balancer](https://cloud.ibm.com/security-compliance/goals/3000407?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000432: Check whether Application Load Balancer for VPC pool uses the HTTPS protocol for HTTPS listeners](https://cloud.ibm.com/security-compliance/goals/3000432?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000433: Check whether Application Load Balancer for VPC is configured to convert HTTP client requests to HTTPS](https://cloud.ibm.com/security-compliance/goals/3000433?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000434: Check whether Application Load Balancer for VPC uses HTTPS (SSL & TLS) instead of HTTP](https://cloud.ibm.com/security-compliance/goals/3000434?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000470: Check whether Cloud Internet Services (CIS) has TLS mode set to End-to-End CA signed](https://cloud.ibm.com/security-compliance/goals/3000470?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000701: Check whether App ID webhooks are using HTTPS only](https://cloud.ibm.com/security-compliance/goals/3000701?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000702: Check whether App ID email dispatchers are using HTTPS only](https://cloud.ibm.com/security-compliance/goals/3000702?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000703: Check whether App ID redirect URIs are using HTTPS only](https://cloud.ibm.com/security-compliance/goals/3000703?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000906: Check whether OpenShift Ingress is configured with at least TLS v1.2 for all inbound traffic](https://cloud.ibm.com/security-compliance/goals/3000906?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
