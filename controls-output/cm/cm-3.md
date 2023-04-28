---

copyright:
  years: 2020, 2023

lastupdated: "2023-04-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# CM-3 - Configuration Change Control
{: #cm-3}

## Control requirements
{: #control-requirements}

The organization:

CM-3 (a)
    : Determines the types of changes to the information system that are configuration-controlled;

CM-3 (b)
    : Reviews proposed configuration-controlled changes to the information system and approves or disapproves such changes with explicit consideration for security impact analyses;

CM-3 (c)
    : Documents configuration change decisions associated with the information system;

CM-3 (d)
    : Implements approved configuration-controlled changes to the information system;

CM-3 (e)
    : Retains records of configuration-controlled changes to the information system for _[IBM Assignment: in accordance with record retention policies and procedures]_;

CM-3 (f)
    : Audits and reviews activities associated with configuration-controlled changes to the information system; and

CM-3 (g)
    : Coordinates and provides oversight for configuration change control activities through _[Assignment: organization-defined configuration change control element (e.g., committee, board)]_ that convenes _[Selection (one or more): [Assignment: organization-defined frequency]_; _[Assignment: organization-defined configuration change conditions]_].

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- The organization must notify impacted customers prior to implementing any changes.  The organization must validate changes after they have been implemented.
- All changes to the systems / applications / processes used by the customer must be under a formal change management/control process and must be communicated to the customer prior to implementation.
- All changes to the customer environment (including supporting process) must be configuration-controlled.
- The organization's change management process must address emergency changes.
- The organization shall ensure that changes to customer data are subject to change control per customer requirements.  Changes of any type should be communicated to the customer as they arise.
- Each change request must be properly documented to  ITIL v3 - Request for Change (RFC) Standards:  Each RFC must have the following fields:
- Unique ID :
- Date of submission :
- Change Owner :
- Initiator of the RFC :
- Proposed Change priority :
- Low
- Normal
- High
- Very High (Emergency Change)
- Reference to Change Proposal
- Description of the Change being applied for :
- Summary description :
- Business case :
- Reason for the Change to be implemented :
- Costs :
- Benefits :
- Consequences if the Change is not implemented :
- References (e.g. to a Problem Record triggering this RFC) :
- Business areas on the client-side affected by the Change :
- Services affected by the Change :
- IT infrastructure components (CIs) affected by the Change :
- Technology aspects (is a new technology being introduced?) :
- Risks : (Risks during the implementation of the Change)
- Identified risks :
- Counter-measures :
- Back-out strategy for the case of a failed Change implementation :
- Time schedule :
- Estimate of resources for the implementation :
- Required personnel resources :
- Estimated work effort for the required personnel resources :
- Cost estimate :
- Budget :
- Additional supporting documents :
- Approval or rejection :
- Date :
- Person/ body in charge of the approval :
- Change reviewers :
- Priority assigned by Change Management :
- Restrictions :
- If applicable, reasons for rejecting the RFC :.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Rules |
|----------------|-------|
| CM-3 (a) | - Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis | 
| CM-3 (b) | - Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis | 
| CM-3 (c) | - Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis | 
| CM-3 (d) | - Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis | 
| CM-3 (e) | - Check whether DevSecOps Toolchain collects software bills of materials (SBOM) to provide transparency in build artifacts \n - Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis | 
| CM-3 (f) | - Check whether DevSecOps Toolchain collects software bills of materials (SBOM) to provide transparency in build artifacts \n - Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis | 
| CM-3 (g) | - Check whether DevSecOps Toolchain deployment has approved change documentation including security impact analysis | 
{: caption="Rules for CM-3 in IBM Cloud for Financial Services v1.2.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Configuration change controls for organizational information systems involve the systematic proposal, justification, implementation, testing, review, and disposition of changes to the systems, including system upgrades and modifications. Configuration change control includes changes to baseline configurations for components and configuration items of information systems, changes to configuration settings for information technology products (e.g., operating systems, applications, firewalls, routers, and mobile devices), unscheduled/unauthorized changes, and changes to remediate vulnerabilities. Typical processes for managing configuration changes to information systems include, for example, Configuration Control Boards that approve proposed changes to systems. For new development information systems or systems undergoing major upgrades, organizations consider including representatives from development organizations on the Configuration Control Boards. Auditing of changes includes activities before and after changes are made to organizational information systems and the auditing activities required to implement such changes.





