---

copyright:
  years: 2020, 2023

lastupdated: "2023-03-08"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# SA-3 - System Development Life Cycle
{: #sa-3}

## Control requirements
{: #control-requirements}

The organization:

SA-3 (a)
    : Manages the information system using _[Assignment: organization-defined system development life cycle]_ that incorporates information security considerations;

SA-3 (b)
    : Defines and documents information security roles and responsibilities throughout the system development life cycle;

SA-3 (c)
    : Identifies individuals having information security roles and responsibilities; and

SA-3 (d)
    : Integrates the organizational information security risk management process into system development life cycle activities.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- The organization should ensure that all applications have a specific start and end date.  Milestones for keeping applications under development, production lifetime, and retirement (decommissioning) will be defined by the customer.  Deviations from the established milestones must be documented, approved and shared with customer.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Development processes and software integrity](/docs/framework-financial-services?topic=framework-financial-services-shared-development-processes)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.1.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Rules |
|----------------|-------|
| SA-3 (a) | - Check whether Container Registry image pushes and pulls take place only over private endpoints | 
| SA-3 (d) | - Check whether Container Registry image pushes and pulls take place only over private endpoints | 
{: caption="Rules for SA-3 in IBM Cloud for Financial Services v1.1.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

A well-defined system development life cycle provides the foundation for the successful development, implementation, and operation of organizational information systems. To apply the required security controls within the system development life cycle requires a basic understanding of information security, threats, vulnerabilities, adverse impacts, and risk to critical missions/business functions. The security engineering principles in SA-8 cannot be properly applied if individuals that design, code, and test information systems and system components (including information technology products) do not understand security. Therefore, organizations include qualified personnel, for example, chief information security officers, security architects, security engineers, and information system security officers in system development life cycle activities to ensure that security requirements are incorporated into organizational information systems. It is equally important that developers include individuals on the development team that possess the requisite security expertise and skills to ensure that needed security capabilities are effectively integrated into the information system. Security awareness and training programs can help ensure that individuals having key security roles and responsibilities have the appropriate experience, skills, and expertise to conduct assigned system development life cycle activities. The effective integration of security requirements into enterprise architecture also helps to ensure that important security considerations are addressed early in the system development life cycle and that those considerations are directly related to the organizational mission/business processes. This process also facilitates the integration of the information security architecture into the enterprise architecture, consistent with organizational risk management and information security strategies.





