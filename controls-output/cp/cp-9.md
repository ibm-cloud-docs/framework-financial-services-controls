---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-08"
keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# CP-9 - Information System Backup
{: #cp-9}

## Requirements
{: #requirements}

The organization:

- a. Conducts backups of user-level information contained in the information system [daily incremental; weekly full];

- b. Conducts backups of system-level information contained in the information system [daily incremental; weekly full];

- c. Conducts backups of information system documentation including security-related documentation [daily incremental; weekly full]; and

- d. Protects the confidentiality, integrity, and availability of backup information at storage locations.

## Control Supplemental Guidance
{: #supplemental-guidance}

System-level information includes, for example, system-state information, operating system and application software, and licenses. User-level information includes any information other than system-level information. Mechanisms employed by organizations to protect the integrity of information system backups include, for example, digital signatures and cryptographic hashes. Protection of system backup information while in transit is beyond the scope of this control. Information system backups reflect the requirements in contingency plans as well as other organizational requirements for backing up information.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| cp-9_prm_1 | daily incremental; weekly full | organization-defined frequency consistent with recovery time and recovery point objectives |
| cp-9_prm_2 | daily incremental; weekly full | organization-defined frequency consistent with recovery time and recovery point objectives |
| cp-9_prm_3 | daily incremental; weekly full | organization-defined frequency consistent with recovery time and recovery point objectives |


## Related Resources
{: #related_resources}

See the resources that follow to learn more about how to implement this control.

- [Business continuity and disaster recovery overview](/docs/framework-financial-services?topic=framework-financial-services-shared-bcdr)

