---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# CP-7 - Alternate Processing Site
{: #cp-7}

## Control requirements
{: #control-requirements}



### CP-7 (a)


Establish an alternate processing site, including necessary agreements to permit the transfer and resumption of _[IBM Assignment: customer applications must failover production workload to an alternate site for a period of five (5) consecutive days]_ for essential mission and business functions within _[IBM Assignment: customer defined RTO/RPO for application]_ when the primary processing capabilities are unavailable.


### CP-7 (b)


Make available at the alternate processing site, the equipment and supplies required to transfer and resume operations or put contracts in place to support delivery to the site within the organization-defined time period for transfer and resumption.


### CP-7 (c)


Provide controls at the alternate processing site that are equivalent to those at the primary site.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

Where failover is used, applications must failover and maintain production workload to an alternate site for a period of five (5) consecutive days.




## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.


- [High availability overview](/docs/framework-financial-services?topic=framework-financial-services-shared-high-availability)


- [Business continuity and disaster recovery overview](/docs/framework-financial-services?topic=framework-financial-services-shared-bcdr)


- [Operational logging](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-operational)


- [Operational monitoring](/docs/framework-financial-services?topic=framework-financial-services-shared-monitoring-operational)






## NIST supplemental guidance
{: #nist-supplemental-guidance}

Alternate processing sites are geographically distinct from primary processing sites and provide processing capability if the primary processing site is not available. The alternate processing capability may be addressed using a physical processing site or other alternatives, such as failover to a cloud-based service provider or other internally or externally provided processing service. Geographically distributed architectures that support contingency requirements may also be considered alternate processing sites. Controls that are covered by alternate processing site agreements include the environmental conditions at alternate sites, access rules, physical and environmental protection requirements, and the coordination for the transfer and assignment of personnel. Requirements are allocated to alternate processing sites that reflect the requirements in contingency plans to maintain essential mission and business functions despite disruption, compromise, or failure in organizational systems.
