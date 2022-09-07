---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-07"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# CP-7 - Alternate Processing Site
{: #cp-7}

## Requirements
{: #requirements}

The organization:

- \[a.\] Establishes an alternate processing site including necessary agreements to permit the transfer and resumption of [customer applications must failover production workload to an alternate site for a period of five (5) consecutive days] for essential missions/business functions within [customer defined RTO/RPO for application] when the primary processing capabilities are unavailable;

- \[b.\] Ensures that equipment and supplies required to transfer and resume operations are available at the alternate processing site or contracts are in place to support delivery to the site within the organization-defined time period for transfer/resumption; and

- \[c.\] Ensures that the alternate processing site provides information security safeguards equivalent to those of the primary site.

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

Where failover is used, applications must failover and maintain production workload to an alternate site for a period of five (5) consecutive days.

## Control Supplemental Guidance
{: #supplemental-guidance}

Alternate processing sites are sites that are geographically distinct from primary processing sites. An alternate processing site provides processing capability in the event that the primary processing site is not available. Items covered by alternate processing site agreements include, for example, environmental conditions at alternate sites, access rules, physical and environmental protection requirements, and coordination for the transfer/assignment of personnel. Requirements are specifically allocated to alternate processing sites that reflect the requirements in contingency plans to maintain essential missions/business functions despite disruption, compromise, or failure in organizational information systems.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| cp-7_prm_1 | customer applications must failover production workload to an alternate site for a period of five (5) consecutive days | organization-defined information system operations |
| cp-7_prm_2 | customer defined RTO/RPO for application | organization-defined time period consistent with recovery time and recovery point objectives |


## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

### Part a
{: #scc-fs-cloud-profile-a}

- [3000051: Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated](https://cloud.ibm.com/security-compliance/goals/3000051?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region](https://cloud.ibm.com/security-compliance/goals/3000117?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000233: Check whether Hyper Protect Crypto Services instance has at least # crypto units](https://cloud.ibm.com/security-compliance/goals/3000233?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000473: Check whether each Virtual Private Cloud is configured to use at least # zones](https://cloud.ibm.com/security-compliance/goals/3000473?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000474: Check whether each Application Load Balancer for VPC is configured to use at least # zones](https://cloud.ibm.com/security-compliance/goals/3000474?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000915: Check whether an OpenShift cluster has worker nodes across multiple zones](https://cloud.ibm.com/security-compliance/goals/3000915?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}

### Part b
{: #scc-fs-cloud-profile-b}

- [3000051: Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated](https://cloud.ibm.com/security-compliance/goals/3000051?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region](https://cloud.ibm.com/security-compliance/goals/3000117?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000233: Check whether Hyper Protect Crypto Services instance has at least # crypto units](https://cloud.ibm.com/security-compliance/goals/3000233?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000473: Check whether each Virtual Private Cloud is configured to use at least # zones](https://cloud.ibm.com/security-compliance/goals/3000473?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000474: Check whether each Application Load Balancer for VPC is configured to use at least # zones](https://cloud.ibm.com/security-compliance/goals/3000474?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000915: Check whether an OpenShift cluster has worker nodes across multiple zones](https://cloud.ibm.com/security-compliance/goals/3000915?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}

### Part c
{: #scc-fs-cloud-profile-c}

- [3000051: Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated](https://cloud.ibm.com/security-compliance/goals/3000051?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region](https://cloud.ibm.com/security-compliance/goals/3000117?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000233: Check whether Hyper Protect Crypto Services instance has at least # crypto units](https://cloud.ibm.com/security-compliance/goals/3000233?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000473: Check whether each Virtual Private Cloud is configured to use at least # zones](https://cloud.ibm.com/security-compliance/goals/3000473?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000474: Check whether each Application Load Balancer for VPC is configured to use at least # zones](https://cloud.ibm.com/security-compliance/goals/3000474?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000915: Check whether an OpenShift cluster has worker nodes across multiple zones](https://cloud.ibm.com/security-compliance/goals/3000915?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
