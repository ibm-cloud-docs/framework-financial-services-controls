---

copyright:
  years: 2020, 2023

lastupdated: "2023-04-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# AU-9 (2) - Audit Backup On Separate Physical Systems / Components
{: #au-9.2}

## Control requirements
{: #control-requirements}

AU-9 (2) - 0
    : The information system backs up audit records [IBM Assignment: at least weekly] onto a physically different system or system component than the system or component being audited.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- Check that any Cloud Object Storage buckets used by Activity Tracker Event Routing are configured as cross-region

## NIST supplemental guidance
{: #nist-supplemental-guidance}

This control enhancement helps to ensure that a compromise of the information system being audited does not also result in a compromise of the audit records.





