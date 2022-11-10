---

copyright:
  years: 2020, 2022

lastupdated: "2022-11-10"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# AU-4 - Audit Storage Capacity
{: #au-4}

## Control requirements
{: #control-requirements}

AU-4 - 0
    : The organization allocates audit record storage capacity in accordance with [organization-defined audit record storage requirements].

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Audit logging of application provider events and SIEM](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit-provider)
- [Audit logging of {{site.data.keyword.cloud_notm}} events](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit)
- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.6.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- 3000282: Check whether Cloud Object Storage quota enforcement is off for buckets that are configured to use Activity Tracker event routing 
- 3000283: Check whether Cloud Object Storage buckets with a quota have threshold-based alerts enabled

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Organizations consider the types of auditing to be performed and the audit processing requirements when allocating audit storage capacity. Allocating sufficient audit storage capacity reduces the likelihood of such capacity being exceeded and resulting in the potential loss or reduction of auditing capability.





