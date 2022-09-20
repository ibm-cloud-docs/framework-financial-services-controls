---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-20"

keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# CM-6 - Configuration Settings
{: #cm-6}

## Requirements
{: #requirements}

The organization:

- \[a.\] Establishes and documents configuration settings for information technology products employed within the information system using [see CM-6 (a) Additional Requirements and Guidance] that reflect the most restrictive mode consistent with operational requirements;

- \[b.\] Implements the configuration settings;

- \[c.\] Identifies, documents, and approves any deviations from established configuration settings for [organization-defined information system components] based on [organization-defined operational requirements]; and

- \[d.\] Monitors and controls changes to the configuration settings in accordance with organizational policies and procedures.

## Additional IBM Cloud for Financial Services specifications
{: #additional-fs-cloud-specifications}

Usage and configuration changes made to Virtual Machine Monitors (VMM) and hypervisors must be documented and maintained for customer review.

NIST SP 800-125A Security Recommendations for Server-based Hypervisor Platforms should be consulted for additional guidance.

CM-6(a) Additional Requirements and Guidance: 
Requirement 1: The service provider must use the Center for Internet Security (CIS) and/or DISA STIG guidelines as a starting point to establish configuration settings.  If no recognized CIS or DISA STIGS are available for the technology in use, the CSP should create their own baseline and include a justification statement as to how they came up with the baseline configuration settings.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Compliance monitoring](/docs/framework-financial-services?topic=framework-financial-services-shared-monitoring-compliance)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

### Part a.
{: #part-a-scc-fs-cloud-profile}

- 3000721: Check whether App ID email verification is enabled for Cloud Directory users
- 3000722: Check whether App ID customer-provided email service is used

## NIST supplemental guidance
{: #supplemental-guidance}

Configuration settings are the set of parameters that can be changed in hardware, software, or firmware components of the information system that affect the security posture and/or functionality of the system. Information technology products for which security-related configuration settings can be defined include, for example, mainframe computers, servers (e.g., database, electronic mail, authentication, web, proxy, file, domain name), workstations, input/output devices (e.g., scanners, copiers, and printers), network components (e.g., firewalls, routers, gateways, voice and data switches, wireless access points, network appliances, sensors), operating systems, middleware, and applications. Security-related parameters are those parameters impacting the security state of information systems including the parameters required to satisfy other security control requirements. Security-related parameters include, for example: (i) registry settings; (ii) account, file, directory permission settings; and (iii) settings for functions, ports, protocols, services, and remote connections. Organizations establish organization-wide configuration settings and subsequently derive specific settings for information systems. The established settings become part of the systems configuration baseline. Common secure configurations (also referred to as security configuration checklists, lockdown and hardening guides, security reference guides, security technical implementation guides) provide recognized, standardized, and established benchmarks that stipulate secure configuration settings for specific information technology platforms/products and instructions for configuring those information system components to meet operational requirements. Common secure configurations can be developed by a variety of organizations including, for example, information technology product developers, manufacturers, vendors, consortia, academia, industry, federal agencies, and other organizations in the public and private sectors. Common secure configurations include the United States Government Configuration Baseline (USGCB) which affects the implementation of CM-6 and other controls such as AC-19 and CM-7. The Security Content Automation Protocol (SCAP) and the defined standards within the protocol (e.g., Common Configuration Enumeration) provide an effective method to uniquely identify, track, and control configuration settings. OMB establishes federal policy on configuration requirements for federal information systems.

