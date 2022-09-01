---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-01"
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