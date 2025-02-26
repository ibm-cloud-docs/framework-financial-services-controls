---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# CP-2 - Contingency Plan
{: #cp-2}

## Control requirements
{: #control-requirements}



### CP-2 (a)


Develop a contingency plan for the system that:
1. Identifies essential mission and business functions and associated contingency requirements;
2. Provides recovery objectives, restoration priorities, and metrics;
3. Addresses contingency roles, responsibilities, assigned individuals with contact information;
4. Addresses maintaining essential mission and business functions despite a system disruption, compromise, or failure;
5. Addresses eventual, full system restoration without deterioration of the controls originally planned and implemented;
6. Addresses the sharing of contingency information; and
7. Is reviewed and approved by _[IBM Assignment: designated senior management personnel who is not an author or contributor to the plan]_.


### CP-2 (b)


Distribute copies of the contingency plan to _[Assignment: organization-defined key contingency personnel (identified by name and/or by role) and organizational elements]_.


### CP-2 (c)


Coordinate contingency planning activities with incident handling activities.


### CP-2 (d)


Review the contingency plan for the system _[IBM Assignment: annually or within 90 calendar days of significant changes]_.


### CP-2 (e)


Update the contingency plan to address changes to the organization, system, or environment of operation and problems encountered during contingency plan implementation, execution, or testing.


### CP-2 (f)


Communicate contingency plan changes to _[Assignment: organization-defined key contingency personnel (identified by name and/or by role) and organizational elements]_.


### CP-2 (g)


Incorporate lessons learned from contingency plan testing, training, or actual contingency activities into contingency testing and training.


### CP-2 (h)


Protect the contingency plan from unauthorized disclosure and modification.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

Documentation includes plan and playbook(s).

The organization must provide required pre-test documentation prior to test initiation. The customer must provide the organization with what is included in pre-test documentation.




## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.


- [High availability overview](/docs/framework-financial-services?topic=framework-financial-services-shared-high-availability)


- [Business continuity and disaster recovery overview](/docs/framework-financial-services?topic=framework-financial-services-shared-bcdr)






## NIST supplemental guidance
{: #nist-supplemental-guidance}

Contingency planning for systems is part of an overall program for achieving continuity of operations for organizational mission and business functions. Contingency planning addresses system restoration and implementation of alternative mission or business processes when systems are compromised or breached. Contingency planning is considered throughout the system development life cycle and is a fundamental part of the system design. Systems can be designed for redundancy, to provide backup capabilities, and for resilience. Contingency plans reflect the degree of restoration required for organizational systems since not all systems need to fully recover to achieve the level of continuity of operations desired. System recovery objectives reflect applicable laws, executive orders, directives, regulations, policies, standards, guidelines, organizational risk tolerance, and system impact level.
Actions addressed in contingency plans include orderly system degradation, system shutdown, fallback to a manual mode, alternate information flows, and operating in modes reserved for when systems are under attack. By coordinating contingency planning with incident handling activities, organizations ensure that the necessary planning activities are in place and activated in the event of an incident. Organizations consider whether continuity of operations during an incident conflicts with the capability to automatically disable the system, as specified in IR-4(5). Incident response planning is part of contingency planning for organizations and is addressed in the IR (Incident Response) family.
