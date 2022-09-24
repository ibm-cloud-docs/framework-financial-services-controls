---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-24"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

         
# SC-6 - Resource Availability
{: #sc-6}

## Requirements
{: #requirements}

The information system protects the availability of resources by allocating _[organization-defined resources] by [priority; quota; organization-defined security safeguards]_.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [High availability overview](/docs/framework-financial-services?topic=framework-financial-services-shared-high-availability)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- 3000051: Check that Hyper Protect Crypto Services has failover units in at least 2 different regions that are Financial Services Validated 
- 3000117: Check that any Cloud Object Storage buckets used by Activity Tracker event routing are configured as cross-region 
- 3000233: Check whether Hyper Protect Crypto Services instance has at least # crypto units 
- 3000282: Check whether Cloud Object Storage quota enforcement is off for buckets that are configured to use Activity Tracker event routing 
- 3000428: Check whether Application Load Balancer for VPC is configured with multiple members in the pool 
- 3000429: Check whether Application Load Balancer for VPC listener is configured with default pool 
- 3000430: Check whether Application Load Balancer for VPC has health check configured when created 
- 3000466: Check whether Application Load Balancer for VPC is attached with an Auto Scale for VPC instance group provided with health check 
- 3000473: Check whether each Virtual Private Cloud is configured to use at least # zones 
- 3000474: Check whether each Application Load Balancer for VPC is configured to use at least # zones 
- 3000915: Check whether an OpenShift cluster has worker nodes across multiple zones

## NIST supplemental guidance
{: #supplemental-guidance}

Priority protection helps prevent lower-priority processes from delaying or interfering with the information system servicing any higher-priority processes. Quotas prevent users or processes from obtaining more than predetermined amounts of resources. This control does not apply to information system components for which there are only single users/roles.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| sc-6_prm_1 |  | organization-defined resources |
| sc-6_prm_2 |  | Choose one or more: priority; quota; organization-defined security safeguards |
| sc-6_prm_3 |  | organization-defined security safeguards |

