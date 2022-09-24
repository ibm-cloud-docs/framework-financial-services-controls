---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-24"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# CP-7 - Alternate Processing Site
{: #cp-7}

## Requirements
{: #requirements}

The organization:

&nbsp;&nbsp;&nbsp;&nbsp;(a) Establishes an alternate processing site including necessary agreements to permit the transfer and resumption of [customer applications must failover production workload to an alternate site for a period of five (5) consecutive days] for essential missions/business functions within [customer defined RTO/RPO for application] when the primary processing capabilities are unavailable;

&nbsp;&nbsp;&nbsp;&nbsp;(b) Ensures that equipment and supplies required to transfer and resume operations are available at the alternate processing site or contracts are in place to support delivery to the site within the organization-defined time period for transfer/resumption; and

&nbsp;&nbsp;&nbsp;&nbsp;(c) Ensures that the alternate processing site provides information security safeguards equivalent to those of the primary site.

## Additional IBM Cloud for Financial Services specifications
{: #additional-fs-cloud-specifications}

- Where failover is used, applications must failover and maintain production workload to an alternate site for a period of five (5) consecutive days.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [High availability overview](/docs/framework-financial-services?topic=framework-financial-services-shared-high-availability)
- [Business continuity and disaster recovery overview](/docs/framework-financial-services?topic=framework-financial-services-shared-bcdr)
- [Operational logging](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-operational)
- [Operational monitoring](/docs/framework-financial-services?topic=framework-financial-services-shared-monitoring-operational)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement | Goals |
|-------------|-------|
| Part a | - 3000051: Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated \n - 3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region \n - 3000233: Check whether Hyper Protect Crypto Services instance has at least # crypto units \n - 3000473: Check whether each Virtual Private Cloud is configured to use at least # zones \n - 3000474: Check whether each Application Load Balancer for VPC is configured to use at least # zones \n - 3000915: Check whether an OpenShift cluster has worker nodes across multiple zones | 
| Part b | - 3000051: Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated \n - 3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region \n - 3000233: Check whether Hyper Protect Crypto Services instance has at least # crypto units \n - 3000473: Check whether each Virtual Private Cloud is configured to use at least # zones \n - 3000474: Check whether each Application Load Balancer for VPC is configured to use at least # zones \n - 3000915: Check whether an OpenShift cluster has worker nodes across multiple zones | 
| Part c | - 3000051: Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated \n - 3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region \n - 3000233: Check whether Hyper Protect Crypto Services instance has at least # crypto units \n - 3000473: Check whether each Virtual Private Cloud is configured to use at least # zones \n - 3000474: Check whether each Application Load Balancer for VPC is configured to use at least # zones \n - 3000915: Check whether an OpenShift cluster has worker nodes across multiple zones | 
{: caption="Goals for CP-7" caption-side="top"}

## NIST supplemental guidance
{: #supplemental-guidance}

Alternate processing sites are sites that are geographically distinct from primary processing sites. An alternate processing site provides processing capability in the event that the primary processing site is not available. Items covered by alternate processing site agreements include, for example, environmental conditions at alternate sites, access rules, physical and environmental protection requirements, and coordination for the transfer/assignment of personnel. Requirements are specifically allocated to alternate processing sites that reflect the requirements in contingency plans to maintain essential missions/business functions despite disruption, compromise, or failure in organizational information systems.

