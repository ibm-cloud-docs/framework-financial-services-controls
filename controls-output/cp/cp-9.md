---

copyright:
  years: 2020, 2022

lastupdated: "2022-11-10"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# CP-9 - Information System Backup
{: #cp-9}

## Control requirements
{: #control-requirements}

The organization:

CP-9 (a)
    : Conducts backups of user-level information contained in the information system _[daily incremental; weekly full]_;

CP-9 (b)
    : Conducts backups of system-level information contained in the information system _[daily incremental; weekly full]_;

CP-9 (c)
    : Conducts backups of information system documentation including security-related documentation _[daily incremental; weekly full]_; and

CP-9 (d)
    : Protects the confidentiality, integrity, and availability of backup information at storage locations.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Business continuity and disaster recovery overview](/docs/framework-financial-services?topic=framework-financial-services-shared-bcdr)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.6.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Goals |
|----------------|-------|
| CP-9 (b) | - 3000051: Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated \n - 3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region | 
| CP-9 (d) | - 3000051: Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated \n - 3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region | 
{: caption="Goals for CP-9 in IBM Cloud for Financial Services v0.6.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

System-level information includes, for example, system-state information, operating system and application software, and licenses. User-level information includes any information other than system-level information. Mechanisms employed by organizations to protect the integrity of information system backups include, for example, digital signatures and cryptographic hashes. Protection of system backup information while in transit is beyond the scope of this control. Information system backups reflect the requirements in contingency plans as well as other organizational requirements for backing up information.





