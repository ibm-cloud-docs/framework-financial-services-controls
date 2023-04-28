---

copyright:
  years: 2020, 2023

lastupdated: "2023-04-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# SC-6 - Resource Availability
{: #sc-6}

## Control requirements
{: #control-requirements}

SC-6 - 0
    : The information system protects the availability of resources by allocating [Assignment: organization-defined resources] by [Selection (one or more): priority; quota; [Assignment: organization-defined security safeguards]].

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [High availability overview](/docs/framework-financial-services?topic=framework-financial-services-shared-high-availability)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.2.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- Check whether Hyper Protect Crypto Services instance has at least # crypto units 
- Check whether each Application Load Balancer for VPC is configured to use at least # zones 
- Check whether Application Load Balancer for VPC is attached with an Auto Scale for VPC instance group provided with health check 
- Check whether Application Load Balancer for VPC is configured with multiple members in the pool 
- Check whether an OpenShift cluster has worker nodes across multiple zones 
- Check that any Cloud Object Storage buckets used by Activity Tracker Event Routing are configured as cross-region 
- Check whether Application Load Balancer for VPC has health check configured when created 
- Check whether Application Load Balancer for VPC listener is configured with default pool 
- Check whether each Virtual Private Cloud is configured to use at least # zones

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Priority protection helps prevent lower-priority processes from delaying or interfering with the information system servicing any higher-priority processes. Quotas prevent users or processes from obtaining more than predetermined amounts of resources. This control does not apply to information system components for which there are only single users/roles.





