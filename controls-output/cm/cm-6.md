---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# CM-6 - Configuration Settings
{: #cm-6}

## Control requirements
{: #control-requirements}



### CM-6 (a)


Establish and document configuration settings for components employed within the system that reflect the most restrictive mode consistent with operational requirements using _[IBM Assignment: Requirement 1: The service provider must use the Center for Internet Security (CIS) and/or DISA STIG guidelines as a starting point to establish configuration settings.  If no recognized CIS or DISA STIGS are available for the technology in use, the CSP should create their own baseline and include a justification statement as to how they came up with the baseline configuration settings.]_.


### CM-6 (b)


Implement the configuration settings.


### CM-6 (c)


Identify, document, and approve any deviations from established configuration settings for _[Assignment: organization-defined system components]_ based on _[Assignment: organization-defined operational requirements]_.


### CM-6 (d)


Monitor and control changes to the configuration settings in accordance with organizational policies and procedures.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

Usage and configuration changes made to Virtual Machine Monitors (VMM) and hypervisors must be documented and maintained for customer review.

NIST SP 800-125A Security Recommendations for Server-based Hypervisor Platforms should be consulted for additional guidance.

Container Security Requirements: 
• Container images should only be stored on authorized managed registries. The use of unauthorized registries to store images must be forbidden (except for the tools responsible to internalize images).
• Container images must be free of any confidential or secret data.
• All images must be evaluated regarding their security level throughout their whole lifecycle by: 
 a. identifying vulnerabilities through regular scans. 
 b. identifying misconfiguration. 
 c. identifying unauthorized confidential or secret  data through scans.
 d. identifying/approving users with elevated privileges through periodic access reviews. 
For any identified discrepancies, remediation plans must be formalized and tracked to closure. 
• Registries must be maintained secured utilizing security best practices at both the infrastructure and application layers.
• Sensitive directories on the host file system must not be mounted onto containers, especially those containing configuration settings for the operating system (such as: /etc./, /usr/, /var/run/docker.sock). Tools must be used to monitor directories that are being mounted and deployment and containers that violate these policies must be prevented.
• Ensure that the memory and CPU usage for containers is appropriately limited, to prevent one container from consuming all host’s resources.
• Containers resources (namespaces & pods) must be defined and sized to guarantee the deployment & re-deployment of business services to deal with a disruption.
• Container images must be sized appropriately to be easily shipped and run on clusters and workers.
• To limit loss of data, persistent data must not be stored in container runtimes or nodes.
• To ensure good health of components, health checks and probes must be combined to cover both the application and its technical and middleware components, and then the container orchestration platform should be allowed to detect, adjust, and orchestrate containers over workers and Availability Zones
• All stored images must be signed by an authorized code signing service.
• Service/application based on containers must be deployed with anti-affinity through multiple Availability Zone (AZ) nodes to prevent all containers from failing at once in case of a major disruption.
• Container runtimes supporting core business service must be configured to limit the business service disruption during operational tasks (e.g., when the pods need to be rescheduled for some reason such as upgrades or routine maintenance).
• Ensure sufficient container runtime resources are available for critical business services before using resources to scale non-critical business services within an Availability Zone (AZ).




## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.


- [Compliance monitoring](/docs/framework-financial-services?topic=framework-financial-services-shared-monitoring-compliance)






## NIST supplemental guidance
{: #nist-supplemental-guidance}

Configuration settings are the parameters that can be changed in the hardware, software, or firmware components of the system that affect the security and privacy posture or functionality of the system. Information technology products for which configuration settings can be defined include mainframe computers, servers, workstations, operating systems, mobile devices, input/output devices, protocols, and applications. Parameters that impact the security posture of systems include registry settings; account, file, or directory permission settings; and settings for functions, protocols, ports, services, and remote connections. Privacy parameters are parameters impacting the privacy posture of systems, including the parameters required to satisfy other privacy controls. Privacy parameters include settings for access controls, data processing preferences, and processing and retention permissions. Organizations establish organization-wide configuration settings and subsequently derive specific configuration settings for systems. The established settings become part of the configuration baseline for the system.
Common secure configurations (also known as security configuration checklists, lockdown and hardening guides, and security reference guides) provide recognized, standardized, and established benchmarks that stipulate secure configuration settings for information technology products and platforms as well as instructions for configuring those products or platforms to meet operational requirements. Common secure configurations can be developed by a variety of organizations, including information technology product developers, manufacturers, vendors, federal agencies, consortia, academia, industry, and other organizations in the public and private sectors.
Implementation of a common secure configuration may be mandated at the organization level, mission and business process level, system level, or at a higher level, including by a regulatory agency. Common secure configurations include the United States Government Configuration Baseline [USGCB] and security technical implementation guides (STIGs), which affect the implementation of CM-6 and other controls such as AC-19 and CM-7. The Security Content Automation Protocol (SCAP) and the defined standards within the protocol provide an effective method to uniquely identify, track, and control configuration settings.
