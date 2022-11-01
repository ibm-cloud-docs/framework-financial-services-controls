---

copyright:
  years: 2020, 2022

lastupdated: "2022-11-01"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# CP-7 (1) - Separation from Primary Site
{: #cp-7.1}

## Control requirements
{: #control-requirements}

CP-7 (1) - 0
    : The organization identifies an alternate processing site that is separated from the primary processing site to reduce susceptibility to the same threats.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.6.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- 3000051: Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated 
- 3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region 
- 3000233: Check whether Hyper Protect Crypto Services instance has at least # crypto units 
- 3000473: Check whether each Virtual Private Cloud is configured to use at least # zones 
- 3000474: Check whether each Application Load Balancer for VPC is configured to use at least # zones 
- 3000479: Check whether there are at least two instances of Direct Link in an account 
- 3000915: Check whether an OpenShift cluster has worker nodes across multiple zones

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Threats that affect alternate processing sites are typically defined in organizational assessments of risk and include, for example, natural disasters, structural failures, hostile cyber attacks, and errors of omission/commission. Organizations determine what is considered a sufficient degree of separation between primary and alternate processing sites based on the types of threats that are of concern. For one particular type of threat (i.e., hostile cyber attack), the degree of separation between sites is less relevant.





