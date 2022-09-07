---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-07"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# AU-9 (2) - Audit Backup On Separate Physical Systems / Components
{: #au-9.2}

## Requirements
{: #requirements}

The information system backs up audit records [at least weekly] onto a physically different system or system component than the system or component being audited.

## Control Supplemental Guidance
{: #supplemental-guidance}

This control enhancement helps to ensure that a compromise of the information system being audited does not also result in a compromise of the audit records.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| au-9.2_prm_1 | at least weekly | organization-defined frequency |


## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- [3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region](https://cloud.ibm.com/security-compliance/goals/3000117?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
