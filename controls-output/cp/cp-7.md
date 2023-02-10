---

copyright:
  years: 2020, 2023

lastupdated: "2023-02-08"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# CP-7 - Alternate Processing Site
{: #cp-7}

## Control requirements
{: #control-requirements}

The organization:

CP-7 (a)
    : Establishes an alternate processing site including necessary agreements to permit the transfer and resumption of _[customer applications must failover production workload to an alternate site for a period of five (5) consecutive days]_ for essential missions/business functions within _[customer defined RTO/RPO for application]_ when the primary processing capabilities are unavailable;

CP-7 (b)
    : Ensures that equipment and supplies required to transfer and resume operations are available at the alternate processing site or contracts are in place to support delivery to the site within the organization-defined time period for transfer/resumption; and

CP-7 (c)
    : Ensures that the alternate processing site provides information security safeguards equivalent to those of the primary site.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- Where failover is used, applications must failover and maintain production workload to an alternate site for a period of five (5) consecutive days.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Business continuity and disaster recovery overview](/docs/framework-financial-services?topic=framework-financial-services-shared-bcdr)
- [High availability overview](/docs/framework-financial-services?topic=framework-financial-services-shared-high-availability)
- [Operational logging](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-operational)
- [Operational monitoring](/docs/framework-financial-services?topic=framework-financial-services-shared-monitoring-operational)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.1.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Rules |
|----------------|-------|
| CP-7 (a) | - Check whether Hyper Protect Crypto Services instance has at least # crypto units \n - Check whether each Application Load Balancer for VPC is configured to use at least # zones \n - Check whether an OpenShift cluster has worker nodes across multiple zones \n - Check that any Cloud Object Storage buckets used by Activity Tracker Event Routing are configured as cross-region \n - Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated \n - Check whether there are at least # instances of Direct Link in an account \n - Check whether OpenShift version is up-to-date \n - Check whether each Virtual Private Cloud is configured to use at least # zones | 
| CP-7 (b) | - Check whether each Application Load Balancer for VPC is configured to use at least # zones \n - Check whether an OpenShift cluster has worker nodes across multiple zones \n - Check that any Cloud Object Storage buckets used by Activity Tracker Event Routing are configured as cross-region \n - Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated \n - Check whether each Virtual Private Cloud is configured to use at least # zones | 
| CP-7 (c) | - Check whether Hyper Protect Crypto Services instance has at least # crypto units \n - Check whether Hyper Protect Crypto Services instance has at least # crypto units \n - Check whether each Application Load Balancer for VPC is configured to use at least # zones \n - Check whether an OpenShift cluster has worker nodes across multiple zones \n - Check that any Cloud Object Storage buckets used by Activity Tracker Event Routing are configured as cross-region \n - Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated \n - Check whether each Virtual Private Cloud is configured to use at least # zones | 
{: caption="Rules for CP-7 in IBM Cloud for Financial Services v1.1.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Alternate processing sites are sites that are geographically distinct from primary processing sites. An alternate processing site provides processing capability in the event that the primary processing site is not available. Items covered by alternate processing site agreements include, for example, environmental conditions at alternate sites, access rules, physical and environmental protection requirements, and coordination for the transfer/assignment of personnel. Requirements are specifically allocated to alternate processing sites that reflect the requirements in contingency plans to maintain essential missions/business functions despite disruption, compromise, or failure in organizational information systems.





