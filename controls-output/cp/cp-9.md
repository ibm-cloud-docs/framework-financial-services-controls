---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-20"

keywords: 
subcollection: framework-financial-services-controls
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

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Business continuity and disaster recovery overview](/docs/framework-financial-services?topic=framework-financial-services-shared-bcdr)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

### Part b.
{: #part-b-scc-fs-cloud-profile}

- 3000051: Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated
- 3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region

### Part d.
{: #part-d-scc-fs-cloud-profile}

- 3000051: Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated
- 3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region

## NIST supplemental guidance
{: #supplemental-guidance}

System-level information includes, for example, system-state information, operating system and application software, and licenses. User-level information includes any information other than system-level information. Mechanisms employed by organizations to protect the integrity of information system backups include, for example, digital signatures and cryptographic hashes. Protection of system backup information while in transit is beyond the scope of this control. Information system backups reflect the requirements in contingency plans as well as other organizational requirements for backing up information.

