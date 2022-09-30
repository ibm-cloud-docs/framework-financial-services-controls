---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-27"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

         
# SA-8 - Security Engineering Principles
{: #sa-8}

## Control requirements
{: #control-requirements}

The organization applies information system security engineering principles in the specification, design, development, implementation, and modification of the information system.

## Additional IBM Cloud for Financial Services specifications
{: #additional-fs-cloud-specifications}

- Solutions must minimize the reliance on underlying network and operating system infrastructure to ensure system independence.
- Develop applications to leverage cloud scalability capabilities, with service level obligations based on their availability requirements.
- NIST Publication 800-144 - Guidelines on Security and Privacy in Public Cloud Computing emphasize logical separation of resources.  The organization must ensure applications are designed to separate each layer of the stack.  Access to each layer must ensure separation of duties.
- API architecture must utilize HTTP (W3C) standards and use RESTful APIs. 
- APIs shall be subject to the same security controls as any other resource within the system.
- APIs shall be platform and operating system independent.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Development processes and software integrity](/docs/framework-financial-services?topic=framework-financial-services-shared-development-processes)

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Organizations apply security engineering principles primarily to new development information systems or systems undergoing major upgrades. For legacy systems, organizations apply security engineering principles to system upgrades and modifications to the extent feasible, given the current state of hardware, software, and firmware within those systems. Security engineering principles include, for example: (i) developing layered protections; (ii) establishing sound security policy, architecture, and controls as the foundation for design; (iii) incorporating security requirements into the system development life cycle; (iv) delineating physical and logical security boundaries; (v) ensuring that system developers are trained on how to build secure software; (vi) tailoring security controls to meet organizational and operational needs; (vii) performing threat modeling to identify use cases, threat agents, attack vectors, and attack patterns as well as compensating controls and design patterns needed to mitigate risk; and (viii) reducing risk to acceptable levels, thus enabling informed risk management decisions.



