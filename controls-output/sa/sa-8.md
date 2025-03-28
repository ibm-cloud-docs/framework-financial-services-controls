---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# SA-8 - Security and Privacy Engineering Principles
{: #sa-8}

## Control requirements
{: #control-requirements}



### SA-8 - 0


Apply the following systems security and privacy engineering principles in the specification, design, development, implementation, and modification of the system and system components: _[Assignment: organization-defined systems security and privacy engineering principles]_.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

Solutions must minimize the reliance on underlying network and operating system infrastructure to ensure system independence.

Develop applications to leverage cloud scalability capabilities, with service level obligations based on their availability requirements.

NIST Publication 800-144 - Guidelines on Security and Privacy in Public Cloud Computing emphasize logical separation of resources.  The organization must ensure applications are designed to separate each layer of the stack.  Access to each layer must ensure separation of duties.

API architecture must utilize HTTP (W3C) standards and use RESTful APIs. 

APIs shall be subject to the same security controls as any other resource within the system.

APIs shall be platform and operating system independent.




## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.


- [Development processes and software integrity](/docs/framework-financial-services?topic=framework-financial-services-shared-development-processes)






## NIST supplemental guidance
{: #nist-supplemental-guidance}

Systems security and privacy engineering principles are closely related to and implemented throughout the system development life cycle (see SA-3). Organizations can apply systems security and privacy engineering principles to new systems under development or to systems undergoing upgrades. For existing systems, organizations apply systems security and privacy engineering principles to system upgrades and modifications to the extent feasible, given the current state of hardware, software, and firmware components within those systems.
The application of systems security and privacy engineering principles helps organizations develop trustworthy, secure, and resilient systems and reduces the susceptibility to disruptions, hazards, threats, and the creation of privacy problems for individuals. Examples of system security engineering principles include: developing layered protections; establishing security and privacy policies, architecture, and controls as the foundation for design and development; incorporating security and privacy requirements into the system development life cycle; delineating physical and logical security boundaries; ensuring that developers are trained on how to build secure software; tailoring controls to meet organizational needs; and performing threat modeling to identify use cases, threat agents, attack vectors and patterns, design patterns, and compensating controls needed to mitigate risk.
Organizations that apply systems security and privacy engineering concepts and principles can facilitate the development of trustworthy, secure systems, system components, and system services; reduce risk to acceptable levels; and make informed risk management decisions. System security engineering principles can also be used to protect against certain supply chain risks, including incorporating tamper-resistant hardware into a design.
