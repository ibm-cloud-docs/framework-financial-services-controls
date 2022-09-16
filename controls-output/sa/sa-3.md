---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-16"
keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# SA-3 - System Development Life Cycle
{: #sa-3}

## Requirements
{: #requirements}

The organization:

- \[a.\] Manages the information system using [organization-defined system development life cycle] that incorporates information security considerations;

- \[b.\] Defines and documents information security roles and responsibilities throughout the system development life cycle;

- \[c.\] Identifies individuals having information security roles and responsibilities; and

- \[d.\] Integrates the organizational information security risk management process into system development life cycle activities.

## Additional IBM Cloud for Financial Services specifications
{: #additional-fs-cloud-specifications}

The organization should ensure that all applications have a specific start and end date.  Milestones for keeping applications under development, production lifetime, and retirement (decommissioning) will be defined by the customer.  Deviations from the established milestones must be documented, approved and shared with customer.

## NIST supplemental guidance
{: #supplemental-guidance}

A well-defined system development life cycle provides the foundation for the successful development, implementation, and operation of organizational information systems. To apply the required security controls within the system development life cycle requires a basic understanding of information security, threats, vulnerabilities, adverse impacts, and risk to critical missions/business functions. The security engineering principles in SA-8 cannot be properly applied if individuals that design, code, and test information systems and system components (including information technology products) do not understand security. Therefore, organizations include qualified personnel, for example, chief information security officers, security architects, security engineers, and information system security officers in system development life cycle activities to ensure that security requirements are incorporated into organizational information systems. It is equally important that developers include individuals on the development team that possess the requisite security expertise and skills to ensure that needed security capabilities are effectively integrated into the information system. Security awareness and training programs can help ensure that individuals having key security roles and responsibilities have the appropriate experience, skills, and expertise to conduct assigned system development life cycle activities. The effective integration of security requirements into enterprise architecture also helps to ensure that important security considerations are addressed early in the system development life cycle and that those considerations are directly related to the organizational mission/business processes. This process also facilitates the integration of the information security architecture into the enterprise architecture, consistent with organizational risk management and information security strategies.


## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Development processes and software integrity](/docs/framework-financial-services?topic=framework-financial-services-shared-development-processes)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

### Part a.
{: #part-a-scc-fs-cloud-profile}

- 3000611: Check whether Container Registry Vulnerability Advisor scans images for OS vulnerability detection
- 3000625: Check whether Container Registry image pushes and pulls take place only over private endpoints

### Part d.
{: #part-d-scc-fs-cloud-profile}

- 3000611: Check whether Container Registry Vulnerability Advisor scans images for OS vulnerability detection
- 3000625: Check whether Container Registry image pushes and pulls take place only over private endpoints
