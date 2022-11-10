---

copyright:
  years: 2020, 2022

lastupdated: "2022-11-10"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# AU-9 (2) - Audit Backup On Separate Physical Systems / Components
{: #au-9.2}

## Control requirements
{: #control-requirements}

AU-9 (2) - 0
    : The information system backs up audit records [at least weekly] onto a physically different system or system component than the system or component being audited.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.6.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- 3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region

## NIST supplemental guidance
{: #nist-supplemental-guidance}

This control enhancement helps to ensure that a compromise of the information system being audited does not also result in a compromise of the audit records.





