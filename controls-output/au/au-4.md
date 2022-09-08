---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-08"
keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# AU-4 - Audit Storage Capacity
{: #au-4}

## Requirements
{: #requirements}

The organization allocates audit record storage capacity in accordance with [organization-defined audit record storage requirements].

## Control Supplemental Guidance
{: #supplemental-guidance}

Organizations consider the types of auditing to be performed and the audit processing requirements when allocating audit storage capacity. Allocating sufficient audit storage capacity reduces the likelihood of such capacity being exceeded and resulting in the potential loss or reduction of auditing capability.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| au-4_prm_1 |  | organization-defined audit record storage requirements |


## Related Resources
{: #related_resources}

See the resources that follow to learn more about how to implement this control.

- [Audit logging of {{site.data.keyword.cloud_notm}} events](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit)
- [Audit logging of application provider events and SIEM](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit-provider)
- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)

## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- [3000282: Check whether Cloud Object Storage quota enforcement is off for buckets that are configured to use Activity Tracker event routing](https://cloud.ibm.com/security-compliance/goals/3000282?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000283: Check whether Cloud Object Storage buckets with a quota have threshold-based alerts enabled](https://cloud.ibm.com/security-compliance/goals/3000283?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
