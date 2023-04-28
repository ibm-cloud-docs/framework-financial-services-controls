---

copyright:
  years: 2020, 2023

lastupdated: "2023-04-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# SA-8 - Security Engineering Principles
{: #sa-8}

## Control requirements
{: #control-requirements}

SA-8 - 0
    : The organization applies information system security engineering principles in the specification, design, development, implementation, and modification of the information system.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

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

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- Check whether DevSecOps Toolchain scans build artifacts to identify vulnerabilities 
- Check whether DevSecOps Toolchain verifies source code branch protection rules to enforce security policies 
- Check whether DevSecOps Toolchain validates code against Center for Internet Security (CIS) Docker benchmarks to ensure container runtimes are configured securely 
- Check whether DevSecOps Toolchain passes dynamic code scan to identify vulnerabilities in deployed artifacts 
- Check whether DevSecOps Toolchain scans source code and their dependencies to identify vulnerabilities 
- Check whether DevSecOps Toolchain source code contains no secrets 
- Check whether DevSecOps Toolchain passes static code scan to identify vulnerabilities in source code 
- Check whether DevSecOps Toolchain collects software bills of materials (SBOM) to provide transparency in build artifacts 
- Check whether DevSecOps Toolchain passes unit tests to validate all code changes 
- Check whether Toolchain is configured only with the allowed integration tools 
- Check whether DevSecOps Toolchain signs build artifacts to attest their provenance 
- Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Organizations apply security engineering principles primarily to new development information systems or systems undergoing major upgrades. For legacy systems, organizations apply security engineering principles to system upgrades and modifications to the extent feasible, given the current state of hardware, software, and firmware within those systems. Security engineering principles include, for example: (i) developing layered protections; (ii) establishing sound security policy, architecture, and controls as the foundation for design; (iii) incorporating security requirements into the system development life cycle; (iv) delineating physical and logical security boundaries; (v) ensuring that system developers are trained on how to build secure software; (vi) tailoring security controls to meet organizational and operational needs; (vii) performing threat modeling to identify use cases, threat agents, attack vectors, and attack patterns as well as compensating controls and design patterns needed to mitigate risk; and (viii) reducing risk to acceptable levels, thus enabling informed risk management decisions.





