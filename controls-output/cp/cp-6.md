---

copyright:
  years: 2020, 2022

lastupdated: "2022-10-02"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# CP-6 - Alternate Storage Site
{: #cp-6}

## Control requirements
{: #control-requirements}

The organization:

CP-6 (a)
    : Establishes an alternate storage site including necessary agreements to permit the storage and retrieval of information system backup information; and

CP-6 (b)
    : Ensures that the alternate storage site provides information security safeguards equivalent to that of the primary site.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.6.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Goals |
|----------------|-------|
| CP-6 (a) | - 3000051: Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated \n - 3000116: Check whether Cloud Object Storage bucket resiliency is set to cross region \n - 3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region | 
| CP-6 (b) | - 3000051: Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated \n - 3000116: Check whether Cloud Object Storage bucket resiliency is set to cross region \n - 3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region | 
{: caption="Goals for CP-6 in IBM Cloud for Financial Services v0.6.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Alternate storage sites are sites that are geographically distinct from primary storage sites. An alternate storage site maintains duplicate copies of information and data in the event that the primary storage site is not available. Items covered by alternate storage site agreements include, for example, environmental conditions at alternate sites, access rules, physical and environmental protection requirements, and coordination of delivery/retrieval of backup media. Alternate storage sites reflect the requirements in contingency plans so that organizations can maintain essential missions/business functions despite disruption, compromise, or failure in organizational information systems.



