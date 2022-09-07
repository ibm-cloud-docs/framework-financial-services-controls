---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-07"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# CP-6 (1) - Separation From Primary Site
{: #cp-6.1}

## Requirements
{: #requirements}

The organization identifies an alternate storage site that is separated from the primary storage site to reduce susceptibility to the same threats.

## Control Supplemental Guidance
{: #supplemental-guidance}

Threats that affect alternate storage sites are typically defined in organizational assessments of risk and include, for example, natural disasters, structural failures, hostile cyber attacks, and errors of omission/commission. Organizations determine what is considered a sufficient degree of separation between primary and alternate storage sites based on the types of threats that are of concern. For one particular type of threat (i.e., hostile cyber attack), the degree of separation between sites is less relevant.



## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- [3000051: Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated](https://cloud.ibm.com/security-compliance/goals/3000051?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region](https://cloud.ibm.com/security-compliance/goals/3000117?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
