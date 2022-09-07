---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-07"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# CP-9 - Information System Backup
{: #cp-9}

## Requirements
{: #requirements}

The organization:

- \[a.\] Conducts backups of user-level information contained in the information system [daily incremental; weekly full];

- \[b.\] Conducts backups of system-level information contained in the information system [daily incremental; weekly full];

- \[c.\] Conducts backups of information system documentation including security-related documentation [daily incremental; weekly full]; and

- \[d.\] Protects the confidentiality, integrity, and availability of backup information at storage locations.

## Control Supplemental Guidance
{: #supplemental-guidance}

System-level information includes, for example, system-state information, operating system and application software, and licenses. User-level information includes any information other than system-level information. Mechanisms employed by organizations to protect the integrity of information system backups include, for example, digital signatures and cryptographic hashes. Protection of system backup information while in transit is beyond the scope of this control. Information system backups reflect the requirements in contingency plans as well as other organizational requirements for backing up information.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| cp-9_prm_1 | daily incremental; weekly full | organization-defined frequency consistent with recovery time and recovery point objectives |
| cp-9_prm_2 | daily incremental; weekly full | organization-defined frequency consistent with recovery time and recovery point objectives |
| cp-9_prm_3 | daily incremental; weekly full | organization-defined frequency consistent with recovery time and recovery point objectives |


## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

### Part b
{: #scc-fs-cloud-profile-b}

- [3000051: Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated](https://cloud.ibm.com/security-compliance/goals/3000051?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region](https://cloud.ibm.com/security-compliance/goals/3000117?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}

### Part d
{: #scc-fs-cloud-profile-d}

- [3000051: Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated](https://cloud.ibm.com/security-compliance/goals/3000051?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region](https://cloud.ibm.com/security-compliance/goals/3000117?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
