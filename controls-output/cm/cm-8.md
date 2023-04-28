---

copyright:
  years: 2020, 2023

lastupdated: "2023-04-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# CM-8 - Information System Component Inventory
{: #cm-8}

## Control requirements
{: #control-requirements}

The organization:

CM-8 (a)
    : Develops and documents an inventory of information system components that:
      1. Accurately reflects the current information system;
      2. Includes all components within the authorization boundary of the information system;
      3. Is at the level of granularity deemed necessary for tracking and reporting; and
      4. Includes _[Assignment: organization-defined information deemed necessary to achieve effective information system component accountability]_; and

CM-8 (b)
    : Reviews and updates the information system component inventory _[IBM Assignment: at least monthly]_.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Rules |
|----------------|-------|
| CM-8 (a) | - Check whether DevSecOps Toolchain collects software bills of materials (SBOM) to provide transparency in build artifacts \n - Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis | 
| CM-8 (b) | - Check whether DevSecOps Toolchain collects software bills of materials (SBOM) to provide transparency in build artifacts \n - Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis | 
{: caption="Rules for CM-8 in IBM Cloud for Financial Services v1.2.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Organizations may choose to implement centralized information system component inventories that include components from all organizational information systems. In such situations, organizations ensure that the resulting inventories include system-specific information required for proper component accountability (e.g., information system association, information system owner). Information deemed necessary for effective accountability of information system components includes, for example, hardware inventory specifications, software license information, software version numbers, component owners, and for networked components or devices, machine names and network addresses. Inventory specifications include, for example, manufacturer, device type, model, serial number, and physical location.





