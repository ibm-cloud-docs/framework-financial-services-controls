---

copyright:
  years: 2020, 2023

lastupdated: "2023-04-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# CM-9 - Configuration Management Plan
{: #cm-9}

## Control requirements
{: #control-requirements}

The organization develops, documents, and implements a configuration management plan for the information system that:

CM-9 (a)
    : Addresses roles, responsibilities, and configuration management processes and procedures;

CM-9 (b)
    : Establishes a process for identifying configuration items throughout the system development life cycle and for managing the configuration of the configuration items;

CM-9 (c)
    : Defines the configuration items for the information system and places the configuration items under configuration management; and

CM-9 (d)
    : Protects the configuration management plan from unauthorized disclosure and modification.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- ISV shall ensure that changes to customer data are subject to change control per customer requirements.  Changes of any type should be communicated to the customer as they arise.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Rules |
|----------------|-------|
| CM-9 (a) | - Check whether DevSecOps Toolchain verifies source code branch protection rules to enforce security policies \n - Check whether DevSecOps Toolchain passes acceptance tests to validate every deployment \n - Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis | 
| CM-9 (b) | - Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis | 
| CM-9 (c) | - Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis | 
| CM-9 (d) | - Check whether DevSecOps Toolchain verifies source code branch protection rules to enforce security policies \n - Check whether DevSecOps Toolchain source code contains no secrets | 
{: caption="Rules for CM-9 in IBM Cloud for Financial Services v1.2.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Configuration management plans satisfy the requirements in configuration management policies while being tailored to individual information systems. Such plans define detailed processes and procedures for how configuration management is used to support system development life cycle activities at the information system level. Configuration management plans are typically developed during the development/acquisition phase of the system development life cycle. The plans describe how to move changes through change management processes, how to update configuration settings and baselines, how to maintain information system component inventories, how to control development, test, and operational environments, and how to develop, release, and update key documents. Organizations can employ templates to help ensure consistent and timely development and implementation of configuration management plans. Such templates can represent a master configuration management plan for the organization at large with subsets of the plan implemented on a system by system basis. Configuration management approval processes include designation of key management stakeholders responsible for reviewing and approving proposed changes to information systems, and personnel that conduct security impact analyses prior to the implementation of changes to the systems. Configuration items are the information system items (hardware, software, firmware, and documentation) to be configuration-managed. As information systems continue through the system development life cycle, new configuration items may be identified and some existing configuration items may no longer need to be under configuration control.





