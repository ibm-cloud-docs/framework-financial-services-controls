---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# CM-3 - Configuration Change Control
{: #cm-3}

## Control requirements
{: #control-requirements}



### CM-3 (a)


Determine and document the types of changes to the system that are configuration-controlled.


### CM-3 (b)


Review proposed configuration-controlled changes to the system and approve or disapprove such changes with explicit consideration for security and privacy impact analyses.


### CM-3 (c)


Document configuration change decisions associated with the system.


### CM-3 (d)


Implement approved configuration-controlled changes to the system.


### CM-3 (e)


Retain records of configuration-controlled changes to the system for _[IBM Assignment: in accordance with record retention policies and procedures]_.


### CM-3 (f)


Monitor and review activities associated with configuration-controlled changes to the system.


### CM-3 (g)


Coordinate and provide oversight for configuration change control activities through _[Assignment: organization-defined configuration change control element]_ that convenes _[Selection (one or more): _[Assignment: organization-defined frequency]_; when _[Assignment: organization-defined configuration change conditions]_.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

The organization must notify impacted customers prior to implementing any changes.  The organization must validate changes after they have been implemented.

All changes to the systems / applications / processes used by the customer must be under a formal change management/control process and must be communicated to the customer prior to implementation. 

All changes to the customer environment (including supporting process) must be configuration-controlled.

The organization's change management process must address emergency changes.

The organization shall ensure that changes to customer data are subject to change control per customer requirements.  Changes of any type should be communicated to the customer as they arise.

Each change request must be properly documented to  ITIL v3 - Request for Change (RFC) Standards:  Each RFC must have the following fields: 
Unique ID :
Date of submission :
Change Owner :
Initiator of the RFC :
(if not identical with Change Owner)
Proposed Change priority :
 Low
 Normal
 High
 Very High (Emergency Change)
(may be overruled by Change Management during Change assessment)
Reference to Change Proposal
(if the Change is related to a Change Proposal submitted at an earlier stage)
Description of the Change being applied for :
Summary description :
Business case :
Reason for the Change to be implemented :
Costs :
Benefits :
Consequences if the Change is not implemented :
References (e.g. to a Problem Record triggering this RFC) :
Business areas on the client-side affected by the Change :
Services affected by the Change :
IT infrastructure components (CIs) affected by the Change :
Technology aspects (is a new technology being introduced?) :
Risks : (Risks during the implementation of the Change)
Identified risks :
Counter-measures :
(e.g. reversion procedure)
Back-out strategy for the case of a failed Change implementation :
Time schedule :
(Predicted/suggested time schedule for the implementation)
Estimate of resources for the implementation :
Required personnel resources :
(from which areas?)
Estimated work effort for the required personnel resources :
Cost estimate :
(itemized for bigger Changes)
Budget :
(Statement as to whether a budget is allocated and cleared for this Change)
Additional supporting documents :
(If applicable, index of additional supporting documents, e.g. the Service Design Package for major additions or modifications to services)
Approval or rejection :
Date :
Person/ body in charge of the approval :
(Change Manager/ CAB/ ECAB)
Change reviewers :
Priority assigned by Change Management :
Restrictions :
If applicable, reasons for rejecting the RFC :.







## NIST supplemental guidance
{: #nist-supplemental-guidance}

Configuration change control for organizational systems involves the systematic proposal, justification, implementation, testing, review, and disposition of system changes, including system upgrades and modifications. Configuration change control includes changes to baseline configurations, configuration items of systems, operational procedures, configuration settings for system components, remediate vulnerabilities, and unscheduled or unauthorized changes. Processes for managing configuration changes to systems include Configuration Control Boards or Change Advisory Boards that review and approve proposed changes. For changes that impact privacy risk, the senior agency official for privacy updates privacy impact assessments and system of records notices. For new systems or major upgrades, organizations consider including representatives from the development organizations on the Configuration Control Boards or Change Advisory Boards. Auditing of changes includes activities before and after changes are made to systems and the auditing activities required to implement such changes. See also SA-10.
